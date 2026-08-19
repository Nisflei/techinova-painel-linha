# 🚀 DevOps TB

Projeto desenvolvido como parte dos estudos de **Desenvolvimento e DevOps**, com o objetivo de aplicar conceitos de desenvolvimento web, organização de código e boas práticas utilizando Git e GitHub.

## 📋 Sobre o projeto

O **devops_tb** é uma aplicação web desenvolvida para colocar em prática conceitos fundamentais de desenvolvimento e gerenciamento de projetos utilizando ferramentas de versionamento.

O projeto também serve como exercício para utilização de **branches, commits e Pull Requests**, seguindo um fluxo de desenvolvimento colaborativo.

## 🛠️ Tecnologias utilizadas

* HTML5
* Git
* GitHub

## 📁 Estrutura do projeto

```text
devops_tb/
├── .github/
├── index.html
└── README.md
```

### `.github/`

Diretório destinado às configurações e recursos relacionados ao GitHub, como templates e configurações do projeto.

### `index.html`

Página principal da aplicação.

### `README.md`

Documentação do projeto e instruções para utilização.

## ▶️ Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/richardsgarcia/devops_tb.git
```

### 2. Acesse a pasta

```bash
cd devops_tb
```

### 3. Execute o projeto

Como o projeto utiliza HTML, você pode abrir o arquivo `index.html` diretamente no navegador.

Uma alternativa é utilizar uma extensão como **Live Server** no Visual Studio Code.

## 🌿 Fluxo de desenvolvimento

O projeto utiliza Git para controle de versão.

Um fluxo básico utilizado é:

```text
main
  │
  ├── feature/nova-funcionalidade
  │
  └── Pull Request
          │
          ▼
        main
```

### Criando uma nova branch

```bash
git checkout -b feature/nome-da-feature
```

### Salvando as alterações

```bash
git add .
git commit -m "feat: adiciona nova funcionalidade"
```

### Enviando a branch

```bash
git push origin feature/nome-da-feature
```

Depois disso, deve ser aberto um **Pull Request** para revisão e posterior merge na branch `main`.

## 🔀 Pull Requests

Os Pull Requests são utilizados para organizar e revisar as alterações antes que elas sejam incorporadas à branch principal.

Cada PR deve informar:

* O que foi alterado;
* Por que a alteração foi realizada;
* Como a alteração foi implementada;
* Como testar;
* Quais testes foram realizados.

## 🧪 Testes

Antes de abrir um Pull Request, verifique se:

* A aplicação abre corretamente;
* Não existem erros no console do navegador;
* As alterações funcionam conforme esperado;
* O código foi revisado antes do envio;
* A branch contém apenas as alterações relacionadas à tarefa.

## 📌 Status do projeto

🚧 **Em desenvolvimento**

Este projeto está sendo desenvolvido com finalidade de estudo e aplicação prática dos conceitos de desenvolvimento e DevOps.

## 👨‍💻 Autor

**Richard Sousa Garcia**

GitHub: [@richardsgarcia](https://github.com/richardsgarcia)

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais.
