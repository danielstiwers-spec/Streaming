# Streaming

ATIVIDADE PRÁTICA — OPERAÇÕES NO MONGODB 
Aluno(a): Turma: Data: ____ / ____ / ________ Nota: 
Instruções iniciais: Acesse o terminal do Codespace, entre no mongosh e utilize um novo banco de dados chamado streaming . Todas as operações abaixo devem ser realizadas na coleção filmes .  
Etapa 1 — Inserção de Documentos 
1. Insira um único documento representando um filme com os seguintes dados:  •  
titulo: "Matrix"  |  genero: "Ficção Científica"  |  ano: 1999  |  nota: 9.0 
2. Em um único comando, insira os quatro filmes abaixo na mesma coleção (observe que cada documento possui estruturas diferentes):  
•  
titulo: "O Poderoso Chefão"  |  genero: "Drama"  |  ano: 1972  |  nota: 9.5  |  oscars: 3 •  
titulo: "Toy Story"  |  genero: "Animação"  |  ano: 1995  |  nota: 8.5  |  idiomas: ["Português", "Inglês", "Espanhol"] 
•  
titulo: "Vingadores: Ultimato"  |  genero: "Ação"  |  ano: 2019  |  nota: 8.8 
• 
titulo: "Lanterna Verde"  |  genero: "Ação"  |  ano: 2011  |  nota: 5.5 
Etapa 2 — Consultas 
3. Exiba todos os documentos cadastrados na coleção filmes .  
4. Busque apenas os filmes cujo gênero seja "Ação" .  
5. Busque todos os filmes lançados a partir do ano 2000 (maior ou igual a 2000).  
6. Liste todos os filmes exibindo apenas os campos titulo e nota , ocultando o identificador único ( _id ) da saída.  
7. Exiba a quantidade total de filmes cadastrados no momento.  
Etapa 3 — Atualização e Remoção 
8. Atualize a nota do filme "Matrix" para 9.2.  
9. Adicione 0.5 ponto à nota atual de todos os filmes do gênero "Ação" em uma única operação.  
10. Adicione o campo destaque com o valor booleano true para todos os filmes que possuem nota maior ou igual a 9.0.  
11. Confira quais filmes possuem nota menor que 7.0 e, em seguida, remova-os da coleção.  
12. Verifique quantos filmes restaram na coleção após a remoção.  
13. Desafio de conceito: Escreva abaixo qual comando apaga todos os documentos de uma coleção mantendo a estrutura dela vazia, e qual comando exclui a coleção por completo do banco de dados.  
Banco de Dados NoSQL — Prática de CRUD no MongoDB (mongosh) 
