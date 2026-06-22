# TypeScript Lesson

Este repositório contém um projeto de estudos desenvolvido com **TypeScript** e **Angular**, com o objetivo de praticar conceitos fundamentais da linguagem, organização de código e criação de aplicações front-end.

O projeto foi gerado com **Angular CLI** e pode ser utilizado como base para executar exemplos, testar funcionalidades e evoluir conhecimentos em TypeScript, Angular, componentes, serviços e estruturação de projetos web.

## Project Overview

O objetivo deste projeto é reunir exemplos e lições práticas sobre TypeScript em um ambiente Angular.

Neste repositório, é possível estudar conceitos como:

- Tipagem em TypeScript;
- Componentes Angular;
- Estrutura de projetos Angular;
- Organização de arquivos;
- Execução local de aplicações;
- Build da aplicação;
- Testes unitários;
- Boas práticas iniciais de desenvolvimento front-end.

Este projeto pode ser utilizado por estudantes, colaboradores e desenvolvedores que desejam revisar ou praticar conceitos básicos e intermediários de TypeScript com Angular.

## Prerequisites

Antes de executar o projeto, é necessário ter instalado em sua máquina:

- Node.js;
- NPM;
- Angular CLI;
- Git.

Versões recomendadas:

- Node.js 18 ou superior;
- NPM 9 ou superior;
- Angular CLI compatível com Angular 17.

Para verificar as versões instaladas, execute:

```bash
node -v
npm -v
ng version
```

Caso ainda não tenha o Angular CLI instalado, utilize:

```bash
npm install -g @angular/cli
```

## Setup

Clone este repositório:

```bash
git clone https://github.com/MiguelMartinazzo/typescript_lesson.git
```

Acesse a pasta do projeto:

```bash
cd typescript_lesson
```

Instale as dependências:

```bash
npm install
```

## Usage

Para executar o projeto localmente, utilize:

```bash
ng serve
```

Depois acesse no navegador:

```text
http://localhost:4200/
```

A aplicação será recarregada automaticamente sempre que houver alterações nos arquivos do projeto.

## Quick Start

Exemplo rápido para baixar, instalar e executar o projeto:

```bash
git clone https://github.com/MiguelMartinazzo/typescript_lesson.git
cd typescript_lesson
npm install
ng serve
```

Após executar os comandos acima, abra o navegador em:

```text
http://localhost:4200/
```

Resultado esperado:

- O servidor de desenvolvimento Angular será iniciado;
- A aplicação estará disponível localmente;
- Alterações feitas no código serão refletidas automaticamente no navegador.

## Build

Para gerar a versão de produção do projeto, execute:

```bash
ng build
```

Os arquivos gerados serão armazenados no diretório:

```text
dist/
```

## Running Unit Tests

Para executar os testes unitários, utilize:

```bash
ng test
```

Os testes serão executados utilizando o ambiente configurado pelo Angular.

## Code Scaffolding

Para gerar um novo componente Angular, utilize:

```bash
ng generate component nome-do-componente
```

Também é possível gerar outros recursos:

```bash
ng generate directive|pipe|service|class|guard|interface|enum|module
```

## Project Structure

Estrutura principal do projeto:

```text
typescript_lesson
├── src
│   ├── app
│   ├── assets
│   ├── index.html
│   ├── main.ts
│   └── styles.css
├── angular.json
├── package.json
├── package-lock.json
├── tsconfig.json
└── README.md
```

## Contribution Guidelines

Contribuições são bem-vindas.

Para contribuir com o projeto:

1. Faça um fork do repositório;
2. Crie uma branch para sua alteração:

```bash
git checkout -b feature/nome-da-feature
```

3. Faça as alterações necessárias;
4. Execute os testes, se aplicável:

```bash
ng test
```

5. Faça o commit das alterações:

```bash
git commit -m "Adiciona nova lição de TypeScript"
```

6. Envie para sua branch:

```bash
git push origin feature/nome-da-feature
```

7. Abra um Pull Request descrevendo as alterações realizadas.

## Reporting Issues

Caso encontre problemas, bugs ou tenha sugestões de melhoria, abra uma issue no repositório informando:

- Descrição do problema;
- Passos para reproduzir;
- Resultado esperado;
- Resultado obtido;
- Prints ou logs, se necessário.

## License

Este projeto ainda não possui uma licença definida.

Caso uma licença seja adicionada futuramente, as informações serão atualizadas nesta seção.
