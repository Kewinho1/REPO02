# REPO02
 
### Perguntas para Entrevista

1. **Qual a função do `express.json()` neste projeto?**  
R:Ele permite que o Express interprete dados no formato JSON enviados nas requisições, facilitando o acesso a req.body.

2. **Como o Prisma se conecta ao banco de dados SQLite neste projeto?**  
R:O Prisma usa o arquivo schema.prisma para configurar a conexão com o banco de dados SQLite, que é especificado na propriedade datasource db.

3. **Explique o que acontece quando uma requisição POST é feita para `/users`.**  
R:O servidor cria um novo usuário com os dados fornecidos (name e email) e retorna os detalhes do usuário criado em resposta.

4. **Quais são as vantagens de usar o Express em comparação com o uso apenas do módulo HTTP nativo do Node.js?**  
R:O Express simplifica a criação de rotas e o tratamento de requisições, tornando o código mais organizado e o desenvolvimento mais ágil.

5. **O que acontece se tentarmos atualizar um usuário inexistente na rota `PUT /users/:id`?**  
R:A API retorna um erro 404, indicando que o usuário não foi encontrado.

6. **Como você expandiria essa API para incluir autenticação de usuários?**  
R:Adicionando um middleware de autenticação que valide tokens JWT ou sessões de usuário antes de permitir acesso às rotas.

7. **Quais são os benefícios de usar TypeScript neste projeto?**  
R:TypeScript melhora a segurança do código, oferece autocompletar e ajuda a evitar erros com verificações de tipo.

8. **Se você quisesse adicionar validações adicionais nos campos `name` e `email`, onde você faria isso no código?**  
R:No corpo das rotas, antes de criar ou atualizar um usuário, verificando os valores de name e email para garantir que sejam válidos.

9. **Por que optamos por usar SQLite como banco de dados nesse projeto?**  
R:O SQLite é leve e fácil de configurar, ideal para projetos pequenos ou protótipos.

10. **Como Prisma lida com migrações de banco de dados e por que isso é importante?**  
R:Prisma permite criar migrações para atualizar o banco de dados conforme o modelo de dados evolui, garantindo a consistência entre o código e o banco de dados.

Essas perguntas ajudarão a avaliar o entendimento do candidato sobre o uso de Node.js, Express, Prisma e SQLite no desenvolvimento de APIs, além de medir sua capacidade de expandir e manter o projeto de forma eficiente.
