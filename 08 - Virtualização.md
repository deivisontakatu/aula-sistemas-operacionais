# 📘 Introdução à Virtualização

## 📌 Descrição Geral

Este material apresenta os **conceitos fundamentais de virtualização**,
uma tecnologia amplamente utilizada em ambientes de computação modernos.

A virtualização permite executar **múltiplos sistemas operacionais em um
único computador físico**, criando ambientes isolados chamados
**máquinas virtuais (Virtual Machines -- VM)**.

Essa tecnologia é amplamente utilizada em: - Laboratórios de ensino -
Testes de software - Ambientes de desenvolvimento - Infraestruturas de
servidores

------------------------------------------------------------------------

# 🎯 Objetivo da Unidade

Compreender **o conceito de virtualização** e aprender a utilizar
ferramentas para criação de máquinas virtuais.

Ao final do estudo, o aluno deverá ser capaz de:

-   Definir o conceito de virtualização
-   Compreender o funcionamento de uma máquina virtual
-   Identificar vantagens da virtualização
-   Criar e configurar uma máquina virtual
-   Instalar um sistema operacional em ambiente virtualizado

------------------------------------------------------------------------

# 🧱 Estrutura do Conteúdo

## 1. Conceito de Virtualização

### Definição

A **virtualização** é uma tecnologia que permite executar **vários
sistemas operacionais simultaneamente em um único computador físico**.

### Princípio

Cria ambientes **isolados** que simulam hardware real.

### Aplicações

-   Laboratórios de testes
-   Desenvolvimento de software
-   Ambientes de produção

------------------------------------------------------------------------

## 2. Vantagens da Virtualização

### Economia de Hardware

Permite consolidar vários sistemas em uma única máquina.

### Ambientes Isolados

Problemas em uma VM não afetam o sistema principal.

### Facilidade para Testes

Permite snapshots e restauração rápida de ambientes.

### Múltiplos Sistemas

Execução simultânea de Windows, Linux, macOS e outros.

------------------------------------------------------------------------

## 3. Conceito de Máquina Virtual

Uma **máquina virtual (VM)** é um computador simulado dentro de outro
computador.

### Sistema Hospedeiro (Host)

Sistema operacional principal do computador físico.

### Camada de Virtualização

Software que simula o hardware para a VM.

### Sistema Convidado (Guest)

Sistema operacional executado dentro da máquina virtual.

------------------------------------------------------------------------

## 4. Oracle VirtualBox

O **Oracle VirtualBox** é uma ferramenta de virtualização:

-   Desenvolvida pela Oracle
-   Gratuita para uso pessoal e educacional
-   Multiplataforma (Windows, Linux, macOS, Solaris)
-   Muito utilizada em ambientes educacionais

------------------------------------------------------------------------

## 5. Criando uma Máquina Virtual

### Passo 1 --- Criar nova VM

Clique em **Nova** no VirtualBox.

### Passo 2 --- Escolher o sistema operacional

Selecione tipo e versão.

### Passo 3 --- Definir memória RAM

Recomendado: **2048 MB ou mais**.

### Passo 4 --- Criar disco virtual

Espaço recomendado: **20--40 GB**.

------------------------------------------------------------------------

## 6. Instalando um Sistema Operacional

1.  **Obter ISO** Baixar o sistema desejado.

2.  **Montar ISO** Adicionar no armazenamento da VM.

3.  **Iniciar VM** Boot pela ISO.

4.  **Instalar sistema** Seguir instalação normal.

------------------------------------------------------------------------

## 7. Exemplo de Sistema Operacional

### Tiny Core Linux

Características:

-   ISO entre **17 MB e 248 MB**
-   Muito leve
-   Modular
-   Ideal para testes e virtualização

Site: https://tinycorelinux.net/downloads.html

------------------------------------------------------------------------

# 🧪 Atividade Prática

1.  Instalar o **Oracle VirtualBox**
2.  Criar uma **máquina virtual**
3.  Instalar um Linux leve (Tiny Core, Lubuntu ou Xubuntu)
4.  Explorar o sistema virtualizado
5.  Documentar o processo em formato de **manual**
6.  Publicar no repositório da disciplina

------------------------------------------------------------------------

# 📚 Referências

TANENBAUM, Andrew S.; BOS, Herbert. *Sistemas Operacionais Modernos*.
Pearson.

SILBERSCHATZ, Abraham; GALVIN, Peter B.; GAGNE, Greg. *Fundamentos de
Sistemas Operacionais*. LTC.

STALLINGS, William. *Sistemas Operacionais: Conceitos e Projetos*.
Pearson.
