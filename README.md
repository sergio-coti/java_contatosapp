# ContatosApp - Sistema de Gerenciamento de Contatos

O ContatosApp é uma aplicação web desenvolvida com o framework Spring MVC que permite aos usuários gerenciar uma lista de contatos. Esta aplicação oferece funcionalidades básicas de CRUD (Criar, Ler, Atualizar e Excluir) para manter informações de contato.

## Tarefas

- Construa o banco de dados do projeto no PostGreSQL, criando as tabelas de acordo com o modelo de entidades do projeto.
- Configure o DATA SOURCE para conexão com o banco de dados e desenvolva os repositórios
- Implemente o cadastro de conta de usuário
- Implemente a autenticação dos usuários, utilize gerenciamento de sessão e filters para proteção de rotas e cache.
- Crie as funcionalidades de cadastro, consulta, exclusão e edição de contatos. A página de cadastro de contatos deverá permitir ao usuário selecionar a categoria do contato (família, amigos, trabalho etc.). A listagem de categorias deverá ser obtida do banco de dados (tabela de categorias). Ao cadastrar o contato, o mesmo deverá ser associado a uma categoria.
- A consulta deverá permitir ao usuário buscar contatos por nome, e exibir um grid DataTable com as opções de exclusão e edição.
- Construa uma página home.jsp contendo um dashboard mostrando dados de sua escolha. Você pode aqui por exemplo exibir gráficos mostrando a quantidade de contatos por categoria.

## Tecnologias Utilizadas

- [Spring Framework](https://spring.io/projects/spring-framework) - Plataforma base para desenvolvimento Java.
- [Spring MVC](https://spring.io/guides/gs/serving-web-content/) - Framework para desenvolvimento de aplicativos web.
- [Bootstrap](https://getbootstrap.com/) - Framework de design e CSS responsivo.

