# ecommerce-back

## Link do Swagger 
https://app.swaggerhub.com/apis-docs/RAFAELCAMILO21/E-commerce-API/1.0

## Como executar o projeto
 Basta baixa-lo no computador e abrir a pasta em um editor de código que dê suporte ao Java, muito importante aguardar que as dependências sejam baixadas corretamente

## Tecnologias Usadas
- **Mysql** 
- Hibernate
- JPA
- **Spring Boot**  
- **Spring Security**
-  Java JWT
- Openpdf
- Thymeleaf
- Spring boot validation
- mysql-connector-j
-  **Maven**

## Objetivo do projeto 
 O desafio era para que fosse criado um e-commerce de nicho que pudesse competir com os grandes e-commerces como Mercado Livre , Amazon e afins . O cliente seria o **Administrador** da aplicação e teria como cliente os **Empreendedores** que colocaria seus **Produtos** a venda na aplicação e assim o **Cliente** poderia fazer a compra destes Produtos. Existem 2 Repositorios referente ao projeto  
Repositorio de Front - end : https://github.com/Rafael-co/E-commerce-Front

## Objetivo do Back -          End neste projeto
 Esta Api é responável por todo o CRUD de usuarios , produtos, alem de várias Querys para alimentação de gráficos, filtros e afins e tambem a segurança de rotas , de requisições, e armazenamento dos dados no banco de dados 
 
 ## Níveis de acesso da aplicação
O nivel de Acesso foi feito a partir de **Login** e **Token JWT** 

**Perfis:** Admin, Empreendedor e Consumidor;
 Aqui no link tem o detalhe de permissões e regras detalhados de cada Perfil :https://github.com/Rafael-co/E-commerce-Back/new/main/src/main/java/org/soulcodeacademy/Ecommerce/domain
### Diagrama de segurança
![Diagrama de segurança](https://user-images.githubusercontent.com/108190323/234932014-2916527d-be4d-4133-94a2-e1a57e4d31f2.jpg)


## Modelagem de Banco de Dados
![Modelo de banco de dados](https://user-images.githubusercontent.com/108190323/234910242-7e468383-aa27-42f2-9c3a-e67b67a1010f.jpg)






