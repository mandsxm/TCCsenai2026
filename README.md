# Sistema de Controle de Almoxarifado

> Sistema web e mobile para controle de entrada e saída de itens do almoxarifado, com autenticação e dois níveis de acesso.

## Sobre o projeto

O Sistema de Controle de Almoxarifado permite gerenciar os itens cadastrados no estoque de forma simples e segura. O acesso é feito por uma tela de login com autenticação e controle de sessão, e as permissões variam conforme o perfil do usuário: **administrador** ou **usuário comum**.

## Funcionalidades

- Tela de login com autenticação e controle de sessão
- Senhas protegidas com hash **bcrypt** (nunca em texto puro)
- Dois níveis de acesso: administrador e usuário comum
- Tabela de itens cadastrados no almoxarifado
- Tela de edição de itens, com opção de **entrada** e **saída** de estoque
- Tabela de usuários cadastrados *(somente administrador)*
- Tela de cadastro de novos usuários *(somente administrador)*
- Interface responsiva, para uso em computador e celular

## Tecnologias utilizadas

- **Back-end:** Python / Flask
- **Front-end:** HTML, CSS e JavaScript / TypeScript
- **Banco de dados:** MySQL
- **Containerização:** Docker

## Autores

- [Amanda](https://github.com/mandsxm)
- [Micaella](https://github.com/mimiiz20)
- [Ana Julia](https://github.com/anajuliasspj-ui)

## Orientação

Trabalho de Conclusão de Curso apresentado no SENAI Afonso Pena, 2026, sob orientação de Roger e Vivianne.
