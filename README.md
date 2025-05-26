🎮 GameList API – Projeto Java + Spring Boot

Este projeto foi desenvolvido como parte do intensivo da DevSuperior com foco em backend utilizando Java e Spring Boot.
A proposta consiste em uma API para gerenciamento de jogos, com destaque para a funcionalidade de reordenação da lista de jogos.

🛠️ Tecnologias Utilizadas
Java 17

Spring Boot

Spring Data JPA

Banco de dados H2

Maven

Postman (para testes dos endpoints)

📌 Funcionalidade principal: Reordenar Jogos
O endpoint implementado permite mover um jogo de uma posição para outra dentro da lista.
Para isso, foi criado um DTO específico (ReplacementDTO) que recebe os índices sourceIndex e destinationIndex no corpo da requisição.

🧠 Lógica aplicada:
Buscar todos os jogos ordenados por posição (position)

Remover o item da posição original

Inserir o item na nova posição

Atualizar todos os índices no banco de dados
