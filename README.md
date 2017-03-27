# Trabalho Final DEW - Tutorial Spring

Esse tutorial foi realizado pelos alunos Vítor Carvalho Fonseca e Mariana Eugênio Santos como trabalho final na disciplina de arquitetura de desenvolvimento WEB.

Como utilizar o programar utilizando ambiente LINUX:

1- Instale o Eclipse Neon versão 4.6.3

2- Verifique se o Eclipse possui os plugins Maven e Spring Tool Suite(STS)

3- Realize o checkout deste código no github.

URL: https://github.com/vcarvalho92/trabalhoFinalSpringDEW

4- Abra a linha de comando e digite "./mvnw spring-boot:run" para inicializar a aplicação

5- Visite o site http://localhost:8080 para visualziar a aplicação

Como alterar a aplicação em runtime:

6- Instale o Curl

7- Caso queira inserir um novo membro na tabela, utilize o comando "curl -X POST localhost:8080/api/employees -d "{\"firstName\": \"Primeiro Nome\", \"lastName\": \"Sobrenome\", \"description\": \"Descrição\"}" -H "Content-Type:application/json""

8- Para visualizar o novo membro, atualize a página WEB

Importante ressaltar que apenas a parte "basic" do código foi realizada, em caso de erros com algumas da dependência, sugiro a utilização do Maven Clean seguido do Maven Install para garantir que todas as dependências estão sendo seguidas.
