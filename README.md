💻 Sobre o Projeto
O Linkpedia é uma aplicação web focada em salvar, organizar e gerenciar links úteis. O grande diferencial deste projeto não é apenas o que ele faz, mas como foi construído: toda a base de código foi desenvolvida utilizando a metodologia TDD (Test-Driven Development).

Nenhuma funcionalidade de banco de dados ou renderização de tela foi implementada sem que um teste automatizado fosse escrito e falhasse primeiro (Fase Vermelha), garantindo uma aplicação totalmente testada e à prova de regressões.

✨ Funcionalidades (CRUD)
🔐 Autenticação: Apenas usuários logados têm acesso ao Painel de Ações.
🟢 Cadastrar (Create): Inserção de novos links com validação nativa de URL.
🔵 Listar (Read): Leitura dinâmica do banco de dados e listagem na interface.
🟡 Editar (Update): Recuperação de dados antigos e atualização de registros via ID.
🔴 Deletar (Delete): Exclusão rápida e segura de links do banco de dados.
