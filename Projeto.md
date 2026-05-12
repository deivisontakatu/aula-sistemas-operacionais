# Projeto Integrador DevOps e Sistemas Operacionais

# Objetivo do Projeto

Desenvolver um projeto completo aplicando os conceitos estudados durante as aulas de:

* DevOps
* Git e Git Flow
* Integração Contínua (CI)
* Entrega Contínua (CD)
* Automação de Pipelines
* Sistemas Operacionais Linux
* Shell Script
* Docker
* Kubernetes
* Testes Automatizados
* Monitoramento e Observabilidade

O principal objetivo deste trabalho é demonstrar como o desenvolvimento moderno de software depende diretamente da integração entre desenvolvimento, infraestrutura e sistemas operacionais.

---

# Tema do Projeto

Cada grupo deverá desenvolver uma aplicação simples com foco em automação operacional e infraestrutura Linux.

A aplicação pode ser:

* Web
* API REST
* Sistema desktop simples
* Sistema via terminal (CLI)

---

# Ênfase Obrigatória: Sistemas Operacionais

## IMPORTANTE

O foco principal do projeto será a utilização prática de conceitos relacionados a Sistemas Operacionais Linux.

O grupo deverá demonstrar domínio operacional do ambiente Linux e automação de tarefas administrativas.

O objetivo não é apenas desenvolver uma aplicação, mas demonstrar como ela pode ser executada, monitorada, automatizada e mantida utilizando recursos do sistema operacional.

---

# Sugestões de Projetos

## Exemplos de sistemas aceitos

### 1. Sistema de Monitoramento Linux

Aplicação responsável por:

* Monitorar uso de CPU
* Monitorar memória RAM
* Monitorar armazenamento em disco
* Exibir processos ativos
* Gerar logs automáticos
* Registrar falhas do sistema

### 2. Sistema de Backup Automatizado

Aplicação que:

* Realiza backups automáticos
* Organiza arquivos de backup
* Gera logs de execução
* Agenda tarefas automáticas
* Permite restauração de arquivos

### 3. API de Monitoramento DevOps

API responsável por:

* Exibir status do servidor
* Verificar uptime do sistema
* Mostrar status de containers
* Monitorar recursos da máquina
* Registrar métricas operacionais

### 4. Sistema de Deploy Automatizado

Sistema que:

* Automatiza atualização da aplicação
* Executa rotinas de deploy
* Reinicia serviços automaticamente
* Registra logs de implantação
* Realiza verificações pós-deploy

### 5. Dashboard de Infraestrutura

Painel contendo:

* Métricas do sistema
* Status da aplicação
* Monitoramento de serviços
* Consumo de recursos
* Visualização de logs

---

# Requisitos Obrigatórios

# 1. Versionamento com Git

O projeto deverá utilizar Git corretamente.

## Requisitos mínimos

### Estrutura esperada de branches

* main
* develop
* feature/nome-funcionalidade
* hotfix/correcao

### O grupo deverá utilizar:

* Commits organizados
* Pull Requests
* Revisão de código (Code Review)
* Integração entre branches
* Histórico organizado do projeto

## O que será avaliado

* Organização do fluxo de desenvolvimento
* Colaboração entre integrantes
* Clareza no histórico de alterações
* Uso adequado do Git Flow

---

# 2. Sistemas Operacionais Linux

## Parte principal do projeto

O grupo deverá demonstrar domínio de conceitos relacionados a sistemas operacionais.

## O projeto deverá apresentar:

* Automação de tarefas administrativas
* Utilização do terminal Linux
* Gerenciamento de processos
* Controle de permissões
* Uso de variáveis de ambiente
* Manipulação de logs
* Agendamento de tarefas automáticas
* Organização de arquivos e diretórios
* Execução de serviços da aplicação

## Exemplos do que pode ser apresentado

### Automação operacional

* Rotinas automáticas de backup
* Limpeza automática de arquivos
* Inicialização automática da aplicação
* Verificação periódica do sistema

### Monitoramento do sistema

* Uso de CPU
* Uso de memória
* Espaço em disco
* Status da aplicação
* Status dos containers

### Logs

* Logs da aplicação
* Logs de erros
* Logs de execução
* Histórico de operações realizadas

### Gerenciamento operacional

* Controle de processos
* Reinício automático de serviços
* Configuração de permissões
* Organização de diretórios do sistema

## O que será avaliado

* Uso correto do Linux
* Capacidade de automação
* Organização operacional do ambiente
* Aplicação prática dos conceitos de sistemas operacionais

---

# 3. Pipeline CI/CD

O projeto deverá possuir pipeline automatizado utilizando:

* GitHub Actions
  OU
* Jenkins

## O pipeline deverá realizar:

* Build automatizado
* Execução de testes
* Validação do projeto
* Execução de verificações automáticas
* Preparação da aplicação para deploy
* Automatização do fluxo de integração contínua

## O que será avaliado

* Funcionamento da pipeline
* Organização do fluxo automatizado
* Integração com o repositório Git
* Qualidade da automação implementada

---

# 4. Testes Automatizados

O projeto deverá implementar:

* Testes unitários
* Testes de integração
* Validações automatizadas

## Objetivos esperados

* Garantir estabilidade da aplicação
* Detectar falhas automaticamente
* Validar funcionamento do sistema
* Integrar testes ao pipeline

## O que será avaliado

* Organização dos testes
* Integração dos testes com CI/CD
* Capacidade de validação automatizada

---

# 5. Docker

O projeto deverá utilizar Docker.

## O grupo deverá demonstrar:

* Criação de ambiente padronizado
* Execução da aplicação em container
* Portabilidade da aplicação
* Organização do ambiente de execução

## O que será avaliado

* Estrutura do container
* Organização do ambiente Docker
* Funcionamento da aplicação no container
* Padronização do ambiente

---

# 6. Kubernetes

O projeto deverá apresentar estrutura básica de orquestração.

## O grupo deverá demonstrar:

* Organização da aplicação em ambiente orquestrado
* Estrutura de deploy
* Comunicação entre serviços
* Escalabilidade básica

## O que será avaliado

* Estrutura organizacional do Kubernetes
* Clareza da configuração
* Aplicação correta dos conceitos

---

# 7. Logs e Monitoramento

A aplicação deverá gerar informações operacionais.

## O projeto deverá possuir:

* Logs da aplicação
* Monitoramento básico
* Métricas operacionais
* Identificação de falhas

## Exemplos aceitos

* Logs de inicialização
* Logs de erro
* Logs de deploy
* Monitoramento de uso de recursos
* Tempo de resposta
* Status dos serviços

## O que será avaliado

* Clareza das informações geradas
* Organização dos logs
* Capacidade de monitoramento do ambiente

---

# 8. Gerenciamento de Configuração

O projeto deverá separar corretamente:

* Código-fonte
* Configurações da aplicação
* Variáveis sensíveis
* Arquivos de ambiente

## O que será avaliado

* Organização do projeto
* Separação entre configuração e código
* Estrutura do ambiente
* Facilidade de manutenção

---

# Estrutura Esperada do Projeto

O projeto deverá possuir organização mínima contendo:

* Código-fonte
* Scripts operacionais
* Estrutura Docker
* Estrutura Kubernetes
* Testes automatizados
* Documentação
* Arquivos de configuração

---

# Entregáveis

# 1. Repositório GitHub

O grupo deverá entregar:

* Código completo
* Histórico de commits
* Branches utilizadas
* Pull Requests
* Organização do fluxo Git

---

# 2. Documentação

O README deverá conter:

* Objetivo do projeto
* Tecnologias utilizadas
* Estrutura da aplicação
* Organização do ambiente
* Explicação do pipeline
* Explicação da automação
* Explicação dos containers
* Explicação da infraestrutura utilizada

---

# 3. Apresentação

Cada grupo deverá demonstrar:

* Aplicação funcionando
* Pipeline executando
* Automação operacional
* Containers em execução
* Estrutura Kubernetes
* Logs e monitoramento
* Organização da infraestrutura

---

# Critérios de Avaliação

| Critério                    | Pontos |
| --------------------------- | ------ |
| Uso correto do Git/Git Flow | 1,0    |
| Sistemas Operacionais Linux | 3,0    |
| Pipeline CI/CD              | 2,0    |
| Docker                      | 1,0    |
| Kubernetes                  | 1,0    |
| Testes Automatizados        | 1,0    |
| Organização e documentação  | 1,0    |

---

# Desafios Extras (Bônus)

O grupo poderá implementar:

* Rollback automatizado
* Canary Release
* Blue-Green Deployment
* Deploy em nuvem
* Health Check
* Monitoramento avançado
* Balanceamento de carga
* Banco de dados com migrations

---

# Referências e Materiais de Apoio

Todos os hyperlinks, exemplos e projetos apresentados nos slides das aulas podem e devem ser utilizados como referência para o desenvolvimento do trabalho.

Os projetos demonstrados durante as aulas servem como apoio técnico para estruturação da solução.

## Repositórios e exemplos apresentados nos slides

### Projeto DevOps

[https://github.com/deivisontakatu/aula-devops](https://github.com/deivisontakatu/projeto-devops)

### Projeto Docker

[https://github.com/deivisontakatu/projeto-docker](https://github.com/deivisontakatu/projeto-docker)

### Projeto Kubernetes

[https://github.com/deivisontakatu/projeto-kubernetes](https://github.com/deivisontakatu/projeto-kubernetes)

### Projeto DevOps com GitHub Actions e testes

[https://github.com/deivisontakatu/projeto-devops-testes](https://github.com/deivisontakatu/projeto-devops-testes)

### Projeto DevOps com pipeline GitHub Actions

[https://github.com/deivisontakatu/projeto-devops/](https://github.com/deivisontakatu/projeto-devops/)

### Projeto Variáveis de Ambiente

[https://github.com/deivisontakatu/projeto-variavel-ambiente](https://github.com/deivisontakatu/projeto-variavel-ambiente)

---

# Resultado Esperado

Ao final do projeto, o grupo deverá demonstrar capacidade de:

* Trabalhar colaborativamente utilizando Git
* Automatizar tarefas em Linux
* Organizar ambientes operacionais
* Construir pipelines DevOps
* Utilizar containers Docker
* Aplicar conceitos de Kubernetes
* Implementar integração contínua
* Automatizar deploys
* Monitorar aplicações
* Aplicar boas práticas DevOps
* Integrar desenvolvimento e operações
* Utilizar conceitos de sistemas operacionais na prática
