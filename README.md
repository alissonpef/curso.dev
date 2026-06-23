<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/alissonpef/curso.dev">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/8e/Nextjs-logo.svg" alt="Logo Next.js" width="120">
  </a>

  <h3 align="center">Jornada com o curso.dev</h3>

  <p align="center">
    Repositório para documentar minha jornada de aprendizado com o curso.dev!
    <br />
    <a href="https://github.com/alissonpef/curso.dev"><strong>Explore os códigos »</strong></a>
    <br />
    <br />
    <a href="https://github.com/alissonpef/curso.dev/issues">Reportar Bug</a>
    ·
    <a href="https://github.com/alissonpef/curso.dev/issues">Solicitar Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Sumário</summary>
  <ol>
    <li>
      <a href="#sobre-o-projeto">Sobre o Projeto</a>
      <ul>
        <li><a href="#tecnologias-e-ferramentas">Tecnologias e Ferramentas</a></li>
      </ul>
    </li>
    <li><a href="#a-jornada-construindo-um-clone-do-tabnews">A Jornada: Construindo um Clone do TabNews</a></li>
    <li>
      <a href="#como-iniciar">Como Iniciar</a>
      <ul>
        <li><a href="#pré-requisitos">Pré-requisitos</a></li>
        <li><a href="#instalação">Instalação</a></li>
      </ul>
    </li>
    <li><a href="#contato">Contato</a></li>
    <li><a href="#agradecimentos">Agradecimentos</a></li>
  </ol>
</details>

<!-- SOBRE O PROJETO -->
## Sobre o Projeto

Olá! Meu nome é **Alisson** e este repositório documenta minha jornada de aprendizado com o **[curso.dev](https://curso.dev/)**, do Filipe Deschamps.

O projeto central do curso é a construção de um clone completo e funcional do **TabNews**, e é exatamente isso que você verá aqui. Diferente de um curso tradicional, o objetivo não é apenas seguir uma lista de aulas, mas sim absorver uma **filosofia de desenvolvimento de software**. Este espaço registrará o processo, os erros, as descobertas e a construção deste projeto, do zero, com foco nos fundamentos.

Sinta-se à vontade para acompanhar a evolução e o raciocínio por trás de cada commit. 🚀

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

### Tecnologias e Ferramentas

Estas são as tecnologias que estou aprendendo e utilizando ao longo desta jornada:

**Stack Principal:**
* ![Next JS](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
* ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
* ![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
* ![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

**Banco de Dados:**
* ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

**Testes:**
* ![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

**DevOps & Cloud:**
* ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
* ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
* ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Ferramentas de Desenvolvimento:**
* ![Git](https://img.shields.io/badge/GIT-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
* ![VSCode](https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
* ![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black)
* ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
* ![Husky](https://img.shields.io/badge/Husky-black?style=for-the-badge&logo=npm)
* ![Commitizen](https://img.shields.io/badge/Commitizen-black?style=for-the-badge&logo=npm)

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- MÓDULOS -->
## A Jornada: Construindo um Clone do TabNews

Este repositório seguirá a metodologia do curso, focada em construir um software robusto e bem arquitetado, entendendo o "porquê" de cada decisão. A estrutura do meu aprendizado será:

- 🧠 **Filosofia e Fundamentos:** Entendendo os princípios essenciais para criar software de qualidade. Mais do que aprender uma linguagem, o foco é em como pensar como um engenheiro de software: a importância dos testes, da clareza do código e das decisões de arquitetura.
- 🏗️ **Estruturando o Projeto do Zero:** Configuração do ambiente de desenvolvimento, inicialização do controle de versão com Git e a criação da estrutura base da aplicação com Next.js, preparando o terreno para um desenvolvimento sustentável.
- 🧪 **Desenvolvimento Guiado por Testes (TDD):** Adotando a prática de escrever testes _antes_ do código de produção. O objetivo é garantir que a aplicação seja testável, confiável e que cada nova funcionalidade (como a criação de um `endpoint` da API) seja adicionada com segurança.
- 💻 **Construindo a API e o Backend:** Desenvolvimento do núcleo da aplicação em Node.js, implementando as regras de negócio, criando os `endpoints` da API e conectando com o banco de dados PostgreSQL.
- 🎨 **Desenvolvendo a Interface (Frontend):** Construção da interface de usuário com React e Next.js, consumindo a API que criamos e tornando a aplicação interativa e funcional para o usuário final.
- 🐳 **Containerização com Docker:** Empacotando a aplicação e o banco de dados em containers Docker para garantir que o ambiente de desenvolvimento seja consistente, portátil e fácil de reproduzir.
- ⚙️ **Integração e Entrega Contínua (CI/CD):** Automatizando o processo de testes e deploy. Configuração de uma esteira com GitHub Actions para que cada alteração no código principal seja testada e, se aprovada, enviada para produção automaticamente.
- 🚀 **Deploy na Nuvem:** Colocando o projeto no ar em um provedor de nuvem (como a Vercel), aprendendo os conceitos práticos para que o mundo possa acessar a aplicação.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- GETTING STARTED -->
## Como Iniciar

Siga as instruções abaixo para executar o projeto deste repositório localmente.

### Pré-requisitos

Certifique-se de ter o Node.js e Docker instalados na sua máquina.
* Node.js (v18.x ou superior)
  Faça o download no site oficial: [nodejs.org](https://nodejs.org/)
* Docker
  Faça o download no site oficial: [docker.com](https://www.docker.com/)

### Instalação

1. Clone o repositório
   ```sh
   git clone https://github.com/alissonpef/curso.dev.git
   ```
2. Instale os pacotes NPM
   ```sh
   cd curso.dev
   npm install
   ```
3. Inicie o projeto (esse comando subirá os containers Docker, rodará as migrações e iniciará o Next.js)
   ```sh
   npm run dev
   ```

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- CONTATO -->
## Contato

Alisson Pereira Ferreira

[![LinkedIn][linkedin-shield]][linkedin-url]
[![Gmail][gmail-shield]](mailto:alissonpef@gmail.com)

Link do Projeto: [https://github.com/alissonpef/curso.dev](https://github.com/alissonpef/curso.dev)

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- AGRADECIMENTOS -->
## Agradecimentos

* [curso.dev](https://curso.dev/) - Por disponibilizar o conteúdo incrível.
* [Othneil Drew - Best README Template](https://github.com/othneildrew/Best-README-Template) - Pelo template original deste README.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/alissonpef/curso.dev.svg?style=for-the-badge
[contributors-url]: https://github.com/alissonpef/curso.dev/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/alissonpef/curso.dev.svg?style=for-the-badge
[forks-url]: https://github.com/alissonpef/curso.dev/network/members
[stars-shield]: https://img.shields.io/github/stars/alissonpef/curso.dev.svg?style=for-the-badge
[stars-url]: https://github.com/alissonpef/curso.dev/stargazers
[issues-shield]: https://img.shields.io/github/issues/alissonpef/curso.dev.svg?style=for-the-badge
[issues-url]: https://github.com/alissonpef/curso.dev/issues

[linkedin-shield]: https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/alisson-pereira-ferreira-450223b/
[gmail-shield]: https://img.shields.io/badge/Gmail-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white
