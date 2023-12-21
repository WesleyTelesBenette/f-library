# Monólito

## ✨ Visão Geral
A arquitetura mais comum e famosa do desenvolvimento de software, que se baseia em ter todo sistema e funcionalidades do projeto, numa única base de código.

<img src="monolito.png" width="600" />

É claro que você pode utilizar outros serviços e APIs externas, ou até mesmo vários bancos de dados, desde que tudo se concentre na aplicação única, onde somente ela deve fornecer ao cliente todas as funcionalidades, acesso a dados e camadas de apresentação.

Para um melhor entendimento, vamos exemplificar a arquitetura.

## 🪄 Exemplo Prático
A arquitetura de uma aplicações de anotações (similar ao Notion ou Obsidian), que precisa de:
- Login com a conta do Google.
- Sistema de pagamento (para versões PRO e recursos diversos).
- Armazenar dados pessoais e das anotações, dos usuários.

<img src="exemplo-monolito.png" width="600" />
