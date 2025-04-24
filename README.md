# 🛠️ Script de Configuração de Infraestrutura

Este projeto tem como objetivo automatizar a criação de usuários, grupos de usuários, diretórios e permissões em um ambiente Linux. O script facilita a padronização de ambientes, sendo útil especialmente para máquinas virtuais recém-instaladas.

## 📦 Funcionalidades

- Criação de grupos de usuários
- Criação de usuários com senhas criptografadas
- Criação de diretórios específicos por grupo
- Atribuição de permissões adequadas
- Ambiente pronto para uso após a execução do script

## 📁 Estrutura Criada

- `/publico` — acesso livre para todos os usuários
- `/adm` — acesso restrito ao grupo `GRP_ADM`
- `/ven` — acesso restrito ao grupo `GRP_VEN`
- `/sec` — acesso restrito ao grupo `GRP_SEC`

## 👥 Grupos e Usuários Criados

| Grupo    | Usuários                     |
|----------|------------------------------|
| GRP_ADM  | carlos, maria, joao          |
| GRP_VEN  | debora, sebastiana, roberto  |
| GRP_SEC  | josefina, amanda, rogerio    |

## ▶️ Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git
   cd seu-repo
