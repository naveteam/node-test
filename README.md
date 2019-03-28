# Teste para desenvolvedor back-end Node.js
### Desenvolver uma RESTful API

#### Premissas

- Utilizar banco de dados relacional
- Utilizar ultima versão LTS do Node.js
- Documentação dos endpoints da API
- Utilizar testes (No mínimo teste de integração)

#### Desafio

Desenvolver a API de um produto similar ao twitter. O objetivo é que usuários possam se cadastrar, e após cadastro publicar postagens. Essas postagens podem ser comentadas tanto pelo proprio usuário, como tambem por outros usários logados. Por fim, é preciso que todas essas postagens, de todos usuários, sejam exibidas em uma timeline ordenadas da mais nova para a mais antiga. 

#### Funcionalidades

1. O usuário pode criar, excluir, editar e visualizar sua conta. 
2. O usuário pode criar, excluir, editar e visualizar suas publicações.
3. O usuário pode criar, excluir, editar e visualizar comentários em suas publicações.
3. O usuário pode criar, excluir, editar e visualizar comentários em publicações de outros usuários.
3. O usuário pode visualizar a listagem de todas as publicações de todos usuários, ordenadas por data. 

### Restrições

1. O usuário NÃO PODE excluir e editar a conta de outros usuários.
2. O usuário NÃ0 PODE excluir e editar as publicações de outros usuários.
3. O usuário NÃ0 PODE excluir e editar as comentários de outros usuários.

#### Observações

Sinta-se livre para criar os campos de cada entidade da forma que considerar adequado. Apenas pedimos para que sejam criados os campos suficientes para testar a API com uma situação real.

#### Entrega

A entrega deve ser feita através de um repositório Git na plataforma de sua preferência.
Enviar convite de acesso para os emails: matheus@nave.rs e joaopedro@nave.rs
