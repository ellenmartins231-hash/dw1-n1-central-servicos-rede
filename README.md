# Central de Serviços

Esse projeto foi feito para a avaliação de Desenvolvimento Web I.

A ideia foi criar uma Central de Serviços onde o usuário pode ver os
serviços disponíveis, consultar chamados e também abrir um novo chamado.

O projeto foi feito usando HTML e CSS, sem JavaScript, banco de dados ou
servidor.

## Páginas

### Início

Na página inicial tem:

- Nome e descrição da Central de Serviços;
- Menu de navegação;
- Apresentação;
- Botão para solicitar suporte;
- 4 cartões de serviços;
- Imagens, categorias, títulos e descrições;
- Links para abrir um chamado.

### Chamados

Na página de chamados foram colocados:

- Indicadores de chamados abertos, pendentes e concluídos;
- Campo de pesquisa;
- Filtros de categoria, prioridade e status;
- Data inicial;
- Data final;
- Horário;
- Botão para pesquisar;
- Botão para limpar os filtros;
- 6 chamados fictícios;
- Número, título, categoria, prioridade, solicitante, data e horário;
- Status dos chamados.

Os filtros não alteram os chamados porque não foi necessário usar JavaScript
nessa atividade.

### Abrir chamado

Foi criado um formulário com:

- Nome completo;
- E-mail;
- Telefone;
- Data e hora da ocorrência;
- Categoria;
- Prioridade;
- Descrição do problema;
- Equipamentos ou serviços afetados;
- Anexo de arquivo;
- Confirmação das informações;
- Botão para limpar;
- Botão para enviar.

Também foram utilizadas algumas validações próprias do HTML, como `required`,
`minlength`, `maxlength` e `accept`.

## Tecnologias

- HTML5;
- CSS3;
- Flexbox;
- Git;
- GitHub;
- GitHub Pages;
- Visual Studio Code;
- Prettier.

## Estrutura

```text
dw1-n1-central-servicos-rede/

├── assets/
│   ├── css/
│   │   ├── reset.css
│   │   ├── global.css
│   │   ├── index.css
│   │   ├── chamados.css
│   │   └── abrir-chamado.css
│   │
│   └── img/
│       ├── computador.jpg
│       ├── rede.jpg
│       ├── sistema.jpg
│       └── acesso.jpg
│
├── index.html
├── chamados.html
├── abrir-chamado.html
└── README.md