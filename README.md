# Angular Blog desafio DIO

Este é um projeto de blog simples desenvolvido com Angular. O objetivo é demonstrar a criação de um blog básico com componentes reutilizáveis para exibir posts em diferentes formatos.

## Funcionalidades

- **Página Inicial (Home)**: Exibe uma lista de posts com cartões grandes e pequenos.
- **Página de Conteúdo**: Mostra o conteúdo completo de um post selecionado.
- **Componentes Reutilizáveis**:
  - `big-card`: Cartão grande para destaques.
  - `small-card`: Cartão pequeno para listas.
  - `menu-bar`: Barra de navegação.
  - `menu-title`: Título do menu.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- [npm](https://www.npmjs.com/) (geralmente incluído com o Node.js)
- [Angular CLI](https://angular.io/cli) (instale globalmente com `npm install -g @angular/cli`)

## Instalação

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   cd angular-blog
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

## Como Executar

Para iniciar o servidor de desenvolvimento:

```bash
npm start
```

O aplicativo estará disponível em `http://localhost:4200/`. Ele será recarregado automaticamente sempre que você modificar os arquivos fonte.

## Como Testar

Para executar os testes unitários com Vitest:

```bash
npm test
```

## Build de Produçãogi

Para compilar o projeto para produção:

```bash
npm run build
```

Os arquivos de build serão armazenados no diretório `dist/`.

## Estrutura do Projeto

```
src/
├── app/
│   ├── components/
│   │   ├── big-card/          # Componente para cartões grandes
│   │   ├── menu-bar/          # Barra de navegação
│   │   ├── menu-title/        # Título do menu
│   │   └── small-card/        # Componente para cartões pequenos
│   ├── data/
│   │   └── dataFake.ts        # Dados fictícios para os posts
│   ├── pages/
│   │   ├── content/           # Página de conteúdo do post
│   │   └── home/              # Página inicial
│   ├── app.config.ts          # Configuração da aplicação
│   ├── app.routes.ts          # Definição das rotas
│   └── app.ts                 # Componente raiz
├── index.html
├── main.ts
└── styles.css
```

## Tecnologias Utilizadas

- **Angular**: Framework para desenvolvimento de aplicações web.
- **TypeScript**: Linguagem de programação.
- **RxJS**: Biblioteca para programação reativa.
- **Vitest**: Framework de testes.
- **Prettier**: Ferramenta de formatação de código.

## Scripts Disponíveis

- `npm start`: Inicia o servidor de desenvolvimento.
- `npm run build`: Compila o projeto para produção.
- `npm test`: Executa os testes unitários.
- `npm run watch`: Compila o projeto em modo de observação.

## Contribuição

Sinta-se à vontade para contribuir com melhorias. Para isso:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto é licenciado sob a MIT License.

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
