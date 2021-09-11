<h1>Digital Innovation: Final Class - Gerenciador de salas de aula com java e Angular</h1>

Uma _live coding_ em que foi desenvolvido um pequeno sistema de gerenciamento de sala de reunião através de uma API REST, criada com Spring Boot e uma frontend type script com Angular

Durante as aulas foram desenvolvidos e abordados os seguintes tópicos:

* Setup inicial de projeto com o Spring Boot Initialzr
* Criação de modelo de dados para mapeamento de entidades em banco de dados
* Desenvolvimento de operações de gerenciamento das salas
  * Cadastro, Leitura, Atualização e Remoção.
* Setup do frontend através do Angular/Cli
* Criação das páginas de apresentação da lista de salas cadastradas
* Instalação e integração do bootstrap e jquery

Para executar o backend no terminal, digite o comando:

```shell script
mvn spring-boot:run
```

Acesso ao backend pelo navegador:

```uri
http://localhost:8082/api/v1/rooms
```

Execução do frontend no terminal, digite o comando:

```shel script
ng serve
```

Com isso, o projeto pode ser acessado pelo endereço:

```uri
http://localhost:4200/
```

O que eu utilizei para acompanhar este projeto:

* CRUD REST API:
  * Spring Boot 2.5.4
  * Maven 3.8.1
  * Java 11
* FrontEnd:
  * @Angular 12.2.3
  * Bootstrap css
* Outros Apps de suporte:
  * VSCode 1.60.0
  * NodeJs 12.22.5
  * Npm 6.14.14
  * Controle de versão GIT
  * Conta GITHUB para armazenamento do projeto