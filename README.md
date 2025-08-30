<div align="center"><img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png">Digital Innovation One</div> 
 
## :octocat: Sobre mim
Meu nome é **Gilberto Ferrari**<br/>
Sou um iniciante em programação e estou atualmente realizando uma trilha de aprendizado, com o foco em desenvolvimento **back-end** usando a linguagem **Java**  
# Java RESTful API  
## Diagrama de Classes (Domínio da API)

```mermaid
classDiagram
  class User {
    -String name
    -Account account
    -Feature[] features
    -Card card
    -News[] news
  }

  class Account {
    -String number
    -String agency
    -Number balance
    -Number limit
  }

  class Feature {
    -String icon
    -String description
  }

  class Card {
    -String number
    -Number limit
  }

  class News {
    -String icon
    -String description
  }

  User "1" *-- "1" Account
  User "1" *-- "N" Feature
  User "1" *-- "1" Card
  User "1" *-- "N" News
```
