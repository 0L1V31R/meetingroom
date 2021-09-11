<h1>Digital Innovation: Final Class - Gerenciador de salas de aula com java e Angular</h1>

Uma _live coding_ em que foi desenvolvido um pequeno sistema de gerenciamento de sala de reunião através de uma API REST, criada com Spring Boot e uma frontend type script com Angular

Durante as aulas foram desenvolvidos e abordados os seguintes tópicos:

* Setup inicial de projeto com o Spring Boot Initialzr
* Criação de modelo de dados para mapeamento de entidades em banco de dados
* Desenvolvimento de operações de gerenciamento das salas
  * Cadastro, Leitura, Atualização e Remoção.
* Relação de cada uma das operações acima com o padrão arquitetural REST, e a explicação de cada um dos conceitos REST envolvidos durante o desenvolvimento do projeto

Para executar o projeto no terminal, digite o comando:

```shell script
mvn spring-boot:run
```

Com isso, o projeto pode ser visto em execução no navegador:

```uri
http://localhost:8082/api/v1/rooms
```

O que eu utilizei para acompanhar este projeto:

* Java 11
* Maven 3.8.1
* VSCode
* Controle de versão GIT
* Conta GITHUB para armazenamento do projeto