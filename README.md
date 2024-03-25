# Curso Full Cycle 3.0 - Módulo Integração Contínua

<div>
    <img alt="Criado por Alcir Junior [Caju]" src="https://img.shields.io/badge/criado%20por-Alcir Junior [Caju]-%23f08700">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23f08700">
</div>

---

## Descrição

O Curso Full Cycle é uma formação completa para fazer com que pessoas desenvolvedoras sejam capazes de trabalhar em projetos expressivos sendo capazes de desenvolver aplicações de grande porte utilizando de boas práticas de desenvolvimento.

---

## Repositório Pai
https://github.com/alcir-junior-caju/study-full-cycle-3-0

---

## Visualizar o projeto na IDE:

Para quem quiser visualizar o projeto na IDE clique no teclado a tecla `ponto`, esse recurso do GitHub é bem bacana

---

### O que é?

É o processo de integrar modificações do codebase de forma contínua e automatizada, evitando assim erros humanos de verificação, garantindo mais agilidade e segurança no processo de desenvolvimento de software.

### Principais Processos
- Execução de testes;
- Linter;
- Verificações de qualidade de código;
- Verificações de segurança;
- Geração de artefatos prontos para o processo de deploy;
- Identificação da próxima versão a ser gerada no software;
- Geração de Tags e Releases;

### Status Check
- É a garantia de que uma Pull Request não poderá ser mergeada ao repositório sem antes ter passado pelo processo de CI ou mesmo no processo de Code Review.

### Ferramentas Populares
- Jenkins;
- Github Actions;
- Circle CI;
- AWS Code Build;
- Azure Devops;
- Google Cloud Build;
- GitLab Pipelines / CI;

### O que é o Github Actions
O Github Actions é um automatizador de workflow de desenvolvimento de software. Ele utiliza os principais eventos gerados pelo Github para que possamos executar tarefas dos mais variados tipos, incluindo processos de CI.

- Workflow;
    - São conjuntos de processos definidos por você. Ex.: Fazer Build + Rodar os testes;
    - É possível ter mais de um workflow por repositórios;
    - Definidos em arquivos `.yml` em `.github/workflows`;
    - Possuí um ou mais `Jobs`;
    - É iniciado em eventos do Github ou agendamentos;
- Evento;
    - on: push;
- Filtros;
    - branches: - master;
- Ambiente;
    - runs-on: ubuntu;
- Ações;
    - steps: - uses: action/run-composer, - run: npm run prod;

### Actions
É a ação que de fato será executada em um dos Steps de um Job em um Workflow. Ela pode ser criada do zero ou ser reutilizada de actions pre-existentes;

#### Action pode ser desenvolvida:
- Javascript;
- Docker Image;
