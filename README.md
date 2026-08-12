Baozi Store API
API REST desenvolvida em Java com Spring Boot para o controle de uma loja de pães chineses (Baozi Store), parte da atividade prática de Desenvolvimento Web Back-End.

📌 Situação Fictícia
A Baozi Store é uma pequena loja que vende pão chinês. Para melhorar a organização do negócio, foi criado um sistema simples para controlar clientes, produtos e pedidos.
Um cliente chamado Genilson5120863 realizou seu cadastro no sistema. O produto vendido pela loja chama-se Baozi Tradicional e é vendido por unidade. Em um determinado momento, 
o cliente realizou o pedido de 2 unidades do produto, facilitando o controle da loja.

🛠️ Tecnologias
Java & Spring Boot

Spring Data JPA

Banco Relacional (H2 / MySQL)

Arquitetura MVC (model, repository, controller)

🔗 Endpoints
Clientes: GET /clientes, POST /clientes, GET /clientes/{id}, DELETE /clientes/{id}

Produtos: GET /produtos, POST /produtos, GET /produtos/{id}, DELETE /produtos/{id}

Pedidos: GET /pedidos, POST /pedidos, GET /pedidos/{id}, DELETE /pedidos/{id}

Desenvolvido por Genilson (RU: 5120863)

Produtos
POST /produtos - Cadastra um novo produto.

GET /produtos - Lista todos os produtos.

GET /produtos/{id} - Busca um produto pelo ID.

DELETE /produtos/{id} - Remove um produto do sistema.

Pedidos
POST /pedidos - Registra um novo pedido.

GET /pedidos - Lista todos os pedidos.

GET /pedidos/{id} - Busca um pedido pelo ID.

DELETE /pedidos/{id} - Remove um pedido do sistema.

👤 Autor
Genilson (RU: 5120863)
