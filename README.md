# swagger-ui-demo

## Sumário

- [swagger-ui-demo](#swagger-ui-demo)
  - [Sumário](#sumário)
  - [Motivação](#motivação)
  - [Pilha de tecnologia](#pilha-de-tecnologia)
  - [Como rodar](#como-rodar)
    - [Pré-requisitos](#pré-requisitos)
    - [Passo a passo](#passo-a-passo)

## Motivação

Este app é uma API de lista de tarefas estilo [TaskBoard](https://tasksboard.com/), cuidadosamente projetada para oferecer uma experiência fluida e eficaz na gestão de tarefas. Proporcionando uma interface intuitiva e eficiente, esta aplicação se destina a simplificar a organização de tarefas, tornando o processo de planejamento e acompanhamento mais acessível e conveniente.

Além de sua eficácia inerente, nossa API de lista de tarefas é acompanhada de uma documentação detalhada e interativa disponibilizada por meio do [Swagger](https://swagger.io/). Essa integração com o Swagger não apenas simplifica o processo de entendimento da API, mas também fornece aos desenvolvedores uma maneira eficaz de explorar, testar e personalizar os recursos da aplicação. A documentação Swagger oferece uma visão clara e abrangente de cada ponto final, parâmetros, métodos e exemplos práticos de uso, garantindo que os usuários possam tirar o máximo proveito da API de lista de tarefas.

Este foi o terceiro repositório de código apresentado no [Curso Superior de TSI do IFMS](https://www.ifms.edu.br/campi/campus-aquidauana/cursos/graduacao/sistemas-para-internet/sistemas-para-internet) como requisito para obtenção da nota parcial das atividades da unidade curricular Web Services.

| [&larr; Repositório anterior](https://github.com/mdccg/blog-api) | [Próximo repositório &rarr;](#) |
|-|-|

## Pilha de tecnologia

| Papel | Tecnologia |
|-|-|
| Linguagem de programação | [TypeScript](https://www.typescriptlang.org/) |
| Framework back-end | [Express.js](https://expressjs.com/pt-br/) |
| Banco de dados | [SQLite](https://www.sqlite.org/) |
| Mapeamento Objeto-Relacional | [TypeORM](https://typeorm.io/) |
| API de documentação dinâmica | [Swagger](https://swagger.io/) |

## Como rodar

### Pré-requisitos

- [Node](https://nodejs.org/en/download/);
- [Yarn](https://yarnpkg.com/) (opcional).

### Passo a passo

1. Clone o repositório de código em sua máquina;
   
2. Abra um shell de comando de sua preferência (prompt de comando, PowerShell, terminal _etc_.);

3. Instale as dependências do projeto através do seguinte comando:

```console
$ npm install
```

Caso esteja utilizando o gerenciador de pacotes Yarn, execute o seguinte comando como alternativa:

```console
$ yarn
```

4. Execute o seguinte comando para executar o app:

Para npm:

```console
$ npm run start
```

Para Yarn:

```console
$ yarn start
```

5. Acesse o endereço de URL http://localhost:3001/docs para conferir a documentação da API gerada pelo Swagger a partir dos arquivos YAML.