# Case---Hexagon

Para que cada parte do sistema tenha uma função e tendo aplicação modular e escalável, foi necessáriaa separação das responsabilidades para a criação desses códigos.

O backend funciona como o cérebro da aplicação, processando as solicitações do frontend e acessando os bancosde dados:
1 - O usuário interage com o frontend
2 - O frontend envia a requisição  para o backend via API REST
3 - O backend processa a requisição e comunica-se com o banco de dados
4 - O banco de dados salva a informação e responde ao backend
5 - O backend retorna a resposta para o frontend que atualiza a interface para o usuário
