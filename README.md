# Segurança e Identidade no Azure
---
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab Segurança e Identidade na Azure na plataforma DIO

---
## Introdução
Este módulo aborda temas como arquitetura, segurança, métodos de autenticação, controle de acesso e monitoramento.

## 1. Arquitetura e Serviços do Azure
- **Identidade e Acesso:** A gestão de identidade no Azure é feita pelo Microsoft Entra ID (antigo Azure AD). Ele oferece serviços como logon único (SSO), autenticação multifator (MFA) e gerenciamento de identidades externas para empresas (B2B).
- **Serviços de Diretório:** O Microsoft Entra Domain Services permite o uso de serviços de diretório baseados em nuvem, sem a necessidade de gerenciar controladores de domínio. É ideal para aplicações legadas que não suportam autenticação moderna.

## 2. Métodos de Autenticação
- **Autenticação Multifator (MFA):** A MFA fornece uma camada adicional de segurança exigindo dois ou mais fatores (algo que o usuário sabe, algo que ele possui, e algo que ele é). Isso reduz o risco de acesso não autorizado.
- **Logon Único (SSO):** O SSO permite que os usuários se autentiquem uma única vez para acessar vários serviços, simplificando o gerenciamento de identidade e reduzindo as barreiras de acesso.

## 3. Modelos de Segurança
- **Confiança Zero:** Este modelo parte do princípio de que nenhuma entidade dentro ou fora da rede deve ser automaticamente confiável. A confiança deve ser continuamente verificada através da autenticação, autorização e controle de políticas de acesso.
- **Defesa em Profundidade:** Consiste em múltiplas camadas de proteção, onde cada camada oferece um nível de segurança independente para proteger os recursos e dados da empresa.
- **Acesso Condicional:** Utilizado para impor políticas de segurança baseadas em condições específicas como a localização do IP, o dispositivo utilizado ou o nível de risco associado ao acesso.

## 4. Controle de Acesso Baseado em Funções (RBAC)
O RBAC permite o gerenciamento de acessos de maneira granular, garantindo que os usuários recebam apenas o nível de acesso necessário para realizar suas funções. Isso melhora a segurança e o controle dentro da organização, evitando privilégios excessivos.

## 5. Microsoft Defender para Nuvem
O Microsoft Defender para Nuvem é um serviço que oferece monitoramento e proteção contra ameaças tanto para ambientes de datacenter no Azure quanto on-premises. Ele fornece recomendações de segurança, detecção de malwares e controle de acesso just-in-time para portas críticas.
