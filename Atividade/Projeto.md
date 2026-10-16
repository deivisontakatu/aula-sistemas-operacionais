# Projeto Integrador — Sistemas Operacionais

## 1. Objetivo do Projeto

Desenvolver, em grupo, uma aplicação funcional de baixa complexidade que demonstre a aplicação prática dos conceitos estudados na disciplina de **Sistemas Operacionais**, com ênfase no ambiente Linux, gerenciamento de recursos e automação de tarefas.

Durante o desenvolvimento, os grupos deverão aplicar conceitos de:

- Sistemas Operacionais e ambiente Linux;
- Uso do terminal e de comandos do sistema;
- Gerenciamento de processos e recursos;
- Manipulação de arquivos, diretórios e permissões;
- Shell Script e automação de tarefas;
- Versionamento de código com Git e GitHub;
- Testes básicos e documentação de software.

O objetivo principal não é construir uma infraestrutura complexa, mas desenvolver uma solução simples, funcional e bem documentada que permita demonstrar os conceitos de Sistemas Operacionais na prática.

---

## 2. Tema do Projeto

Cada grupo deverá escolher um problema que possa ser resolvido por meio de uma aplicação simples relacionada à utilização, administração ou automação de recursos de um sistema operacional.

A aplicação poderá ser desenvolvida em uma linguagem de programação de escolha do grupo e poderá funcionar por meio de:

- Terminal (CLI);
- Aplicação web simples;
- API;
- Interface gráfica simples.

Independentemente da interface escolhida, o projeto deverá demonstrar claramente a aplicação de conceitos de Sistemas Operacionais. A interface, por si só, não será o foco principal da avaliação.

---

## 3. Requisitos Obrigatórios

### 3.1. Aplicação funcional

O grupo deverá desenvolver uma aplicação que resolva um problema específico e apresente funcionalidades que possam ser demonstradas durante a apresentação.

A solução deverá:

- Possuir um objetivo claramente definido;
- Implementar as principais funcionalidades propostas;
- Executar corretamente em um ambiente documentado;
- Demonstrar, na prática, conceitos de Sistemas Operacionais;
- Apresentar resultados que possam ser verificados durante a demonstração.

O grupo deverá priorizar uma versão funcional e simples do projeto (MVP), evitando funcionalidades desnecessárias que aumentem excessivamente a complexidade.

### 3.2. Sistemas Operacionais e Linux

Esta é a parte principal do projeto. A aplicação deverá demonstrar **pelo menos três conceitos de Sistemas Operacionais**, sendo pelo menos um deles relacionado diretamente ao gerenciamento de processos, memória, arquivos, armazenamento ou recursos do sistema.

Os conceitos poderão incluir:

- Utilização do terminal Linux;
- Consulta e gerenciamento de processos;
- Consulta de uso de CPU e memória;
- Verificação de espaço em disco;
- Criação, leitura, cópia, organização ou exclusão de arquivos;
- Gerenciamento de diretórios e permissões;
- Utilização de variáveis de ambiente;
- Execução de comandos do sistema operacional;
- Inicialização ou encerramento controlado de processos;
- Registro e consulta de informações operacionais;
- Agendamento de tarefas, quando pertinente.

O grupo deverá explicar quais conceitos foram utilizados, por que foram escolhidos e como aparecem no funcionamento da aplicação.

### 3.3. Shell Script ou automação

O projeto deverá incluir pelo menos um script ou procedimento automatizado relacionado à solução desenvolvida.

Exemplos:

- Script para executar a aplicação;
- Rotina de backup e organização de arquivos;
- Script para verificar recursos do sistema;
- Rotina para gerar relatórios;
- Script para preparar o ambiente de execução;
- Automação de uma tarefa administrativa.

O script deverá ser funcional, estar incluído no repositório e ter sua utilização explicada na documentação.

### 3.4. Versionamento com Git e GitHub

O grupo deverá utilizar Git e GitHub para armazenar e desenvolver o projeto colaborativamente.

Requisitos mínimos:

- Repositório com código-fonte e arquivos necessários;
- Commits que representem a evolução do trabalho;
- Identificação das contribuições dos integrantes;
- Organização básica dos arquivos e do histórico;
- Utilização de `.gitignore` quando necessário.

Não será obrigatório utilizar Git Flow, múltiplas branches, Pull Requests ou pipelines automatizadas. O grupo poderá utilizar um fluxo simples de versionamento, desde que o histórico e as contribuições estejam organizados.

### 3.5. Testes e documentação

O projeto deverá incluir verificações básicas que demonstrem o funcionamento das principais funcionalidades. Os testes poderão ser automatizados ou documentados por meio de procedimentos reproduzíveis, conforme a natureza da aplicação.

O repositório deverá conter um arquivo `README.md` com:

- Nome e objetivo do projeto;
- Problema que a aplicação pretende resolver;
- Integrantes do grupo;
- Tecnologias utilizadas;
- Conceitos de Sistemas Operacionais aplicados;
- Funcionalidades implementadas;
- Instruções de instalação e execução;
- Instruções para utilizar o script ou a automação;
- Como testar e verificar o funcionamento;
- Limitações conhecidas, se houver.

---

## 4. Sugestões de Projetos

Os exemplos abaixo servem como ponto de partida. Os grupos poderão propor outras soluções, desde que estejam alinhadas aos objetivos e aos requisitos da disciplina.

### 4.1. Monitor de Recursos do Sistema

Aplicação que consulta e apresenta informações básicas sobre o computador ou ambiente Linux.

Possíveis funcionalidades:

- Exibir uso de CPU e memória;
- Consultar espaço disponível em disco;
- Listar processos ativos;
- Gerar um relatório com os dados coletados;
- Registrar as consultas realizadas em um arquivo.

### 4.2. Sistema de Backup e Restauração

Aplicação para realizar cópias de segurança de arquivos e permitir sua recuperação.

Possíveis funcionalidades:

- Selecionar diretórios para backup;
- Copiar arquivos para um diretório de destino;
- Organizar backups por data;
- Registrar o resultado das operações;
- Restaurar arquivos a partir de um backup;
- Automatizar a execução por meio de um script.

### 4.3. Gerenciador de Processos

Aplicação para consultar informações sobre os processos em execução.

Possíveis funcionalidades:

- Listar processos ativos;
- Exibir PID e informações disponíveis sobre cada processo;
- Pesquisar processos pelo nome;
- Consultar o estado ou o consumo de recursos, quando disponível;
- Registrar consultas em um relatório.

Qualquer funcionalidade que encerre processos deverá operar de forma controlada e exigir autorização explícita do usuário quando necessário.

### 4.4. Analisador de Armazenamento

Aplicação para analisar arquivos e diretórios de determinado local.

Possíveis funcionalidades:

- Listar arquivos e diretórios;
- Identificar os arquivos maiores;
- Calcular o espaço ocupado;
- Agrupar arquivos por extensão;
- Gerar relatórios;
- Identificar arquivos duplicados, caso o grupo consiga implementar essa funcionalidade.

### 4.5. Automatizador de Tarefas com Arquivos

Aplicação para automatizar tarefas recorrentes de organização de arquivos.

Possíveis funcionalidades:

- Organizar arquivos por extensão;
- Criar diretórios automaticamente;
- Renomear arquivos conforme regras definidas;
- Identificar arquivos antigos;
- Gerar um relatório das operações;
- Disponibilizar uma opção de simulação antes de realizar alterações.

### 4.6. Verificador de Integridade de Arquivos

Aplicação que verifica alterações em arquivos por meio de informações como tamanho, data de modificação ou hash.

Possíveis funcionalidades:

- Selecionar arquivos ou diretórios para verificação;
- Gerar um registro inicial;
- Comparar os arquivos em verificações posteriores;
- Identificar arquivos modificados ou removidos;
- Gerar um relatório das diferenças.

---

## 5. Estrutura Esperada do Repositório

O grupo deverá organizar o repositório de acordo com as características da solução. Como referência, poderá utilizar a seguinte estrutura:

```text
projeto/
├── src/                 # Código-fonte da aplicação
├── scripts/             # Scripts de automação
├── tests/               # Testes ou verificações
├── docs/                # Imagens e documentação complementar
├── .gitignore
└── README.md
```

A estrutura poderá ser adaptada conforme a linguagem e o tipo de aplicação. Nem todas as pastas precisam existir caso não sejam pertinentes ao projeto.

---

## 6. Entregáveis

### 6.1. Repositório GitHub

O grupo deverá entregar o link do repositório contendo:

- Código-fonte da aplicação;
- Script ou procedimento automatizado;
- Arquivos necessários para executar e testar a solução;
- Histórico de commits;
- Documentação atualizada.

### 6.2. Documentação

O `README.md` deverá permitir que outra pessoa compreenda o objetivo do projeto e consiga executar a aplicação seguindo as instruções fornecidas.

### 6.3. Apresentação e demonstração

Cada grupo deverá realizar uma apresentação de **10 a 15 minutos**, incluindo:

1. Apresentação do problema e do objetivo da solução;
2. Explicação das funcionalidades desenvolvidas;
3. Identificação dos conceitos de Sistemas Operacionais aplicados;
4. Demonstração prática da aplicação em funcionamento;
5. Demonstração do script ou da automação;
6. Explicação dos testes realizados;
7. Apresentação do repositório e da documentação;
8. Considerações finais, limitações e possíveis melhorias.

Todos os integrantes deverão participar da apresentação e demonstrar conhecimento sobre o projeto.

---

## 7. Critérios de Avaliação

A avaliação será realizada com base no total de **10,0 pontos**.

| Critério | Descrição | Pontos |
|---|---|---:|
| Aplicação funcional | Atendimento ao objetivo proposto, funcionamento das principais funcionalidades e escopo adequado | 2,5 |
| Conceitos de Sistemas Operacionais | Aplicação prática e explicação correta de pelo menos três conceitos, incluindo um relacionado a processos, memória, arquivos, armazenamento ou recursos do sistema | 3,0 |
| Script e automação | Funcionamento, utilidade e integração do script ou procedimento automatizado à solução | 1,5 |
| Testes, organização e documentação | Verificações de funcionamento, organização do repositório e clareza do README | 1,0 |
| Apresentação e domínio técnico | Clareza da explicação, demonstração prática e conhecimento dos integrantes sobre a implementação | 2,0 |
| **Total** | | **10,0** |

A avaliação considerará a qualidade e a adequação da solução ao escopo proposto, e não a quantidade de tecnologias utilizadas. Um projeto simples, funcional e bem explicado poderá obter uma avaliação melhor do que uma solução mais complexa que não demonstre adequadamente os conceitos da disciplina.

---

## 8. Orientações para o Desenvolvimento

- Definam um problema específico e viável para o tempo disponível;
- Planejem primeiro as funcionalidades essenciais (MVP);
- Distribuam as tarefas entre os integrantes;
- Desenvolvam e testem a aplicação incrementalmente;
- Utilizem GitHub para registrar a evolução do projeto;
- Validem a execução no ambiente que será utilizado na apresentação;
- Documentem os comandos e procedimentos necessários;
- Evitem funcionalidades que não contribuam diretamente para o objetivo do projeto;
- Garantam que todos os integrantes consigam explicar a solução.

O uso de ferramentas ou tecnologias adicionais será permitido quando fizer sentido para o projeto, mas não substituirá a necessidade de demonstrar os conceitos de Sistemas Operacionais.

---

## 9. Referências e Materiais de Apoio

Os exemplos, links, repositórios e materiais apresentados durante as aulas poderão ser utilizados como apoio para o desenvolvimento do trabalho.

Repositórios de referência:

- [Aula DevOps](https://github.com/deivisontakatu/aula-devops)
- [Projeto Docker](https://github.com/deivisontakatu/projeto-docker)
- [Projeto Kubernetes](https://github.com/deivisontakatu/projeto-kubernetes)
- [Projeto DevOps com GitHub Actions e testes](https://github.com/deivisontakatu/projeto-devops-testes)
- [Projeto DevOps com pipeline GitHub Actions](https://github.com/deivisontakatu/projeto-devops)
- [Projeto Variáveis de Ambiente](https://github.com/deivisontakatu/projeto-variavel-ambiente)

Esses materiais são referências complementares. O projeto **não exige Docker, Kubernetes, pipelines CI/CD ou ferramentas de observabilidade avançada**.

---

## 10. Resultado Esperado

Ao final do projeto, cada grupo deverá apresentar uma aplicação funcional, de baixa complexidade e relacionada a um problema concreto. A solução deverá demonstrar a utilização prática de conceitos de Sistemas Operacionais, incluir uma automação simples, estar versionada no GitHub e possuir documentação suficiente para permitir sua execução e avaliação.

O foco principal será a compreensão dos conceitos, sua aplicação prática e a capacidade dos estudantes de explicar as decisões tomadas durante o desenvolvimento.
