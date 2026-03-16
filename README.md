# ConectaNetCRM 🌐🛰️

O **ConectaNetCRM** é um sistema de gerenciamento de clientes e mensalidades desenvolvido especificamente para pequenos provedores de internet (ISPs). O sistema automatiza o controle financeiro e a gerência de acesso via integração direta com roteadores **MikroTik**.

## 🚀 Funcionalidades Principais
* **Gestão de Clientes:** Cadastro completo com informações de contato e dados de conexão PPPoE.
* **Controle Financeiro:** Monitoramento de mensalidades e datas de vencimento.
* **Automação de Bloqueio:** Integração com a API do RouterOS para desativar automaticamente usuários inadimplentes no MikroTik.
* **Interface Gráfica:** Ambiente amigável desenvolvido em Java Swing para facilitar o uso operacional.

* ## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Java (JDK 17+)
* **Interface:** Java Swing (GUI)
* **Banco de Dados:** MySQL
* **Integração:** MikroTik RouterOS API / SSH
* **Controle de Versão:** Git & GitHub

* ## 🏗️ Arquitetura do Sistema
O projeto segue o padrão **MVC (Model-View-Controller)** para garantir organização e facilidade na manutenção:
* `Model`: Classes que representam as entidades (Cliente, Mensalidade) e a lógica de negócios.
* `View`: Telas desenvolvidas em Swing para interação com o usuário.
* `Controller/DAO`: Classes responsáveis pela persistência no MySQL e comunicação com o MikroTik.

* ---
**Status do Projeto:** Em desenvolvimento 🏗️
Desenvolvido por **MicaelMarcos** - Estudante de Análise e Desenvolvimento de Sistemas.
