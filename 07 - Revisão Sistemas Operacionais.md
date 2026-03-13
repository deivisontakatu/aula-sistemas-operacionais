# 📘 Aula: Estrutura e Funcionamento de Sistemas Operacionais

## 🎯 Objetivos da Aula

Ao final desta aula, o estudante deverá ser capaz de:

-   Compreender o papel do **kernel** em um sistema operacional
-   Diferenciar **modo usuário** e **modo kernel**
-   Entender o conceito de **processos, threads e ciclo de vida**
-   Identificar **políticas e algoritmos de escalonamento**
-   Compreender **gerenciamento de memória e memória virtual**
-   Entender **comunicação entre processos**
-   Compreender **gerenciamento de dispositivos e sistemas de arquivos**

------------------------------------------------------------------------

# 1. Estrutura do Sistema Operacional

## 1.1 O que é um Sistema Operacional

Um **Sistema Operacional (SO)** é o software responsável por **gerenciar
os recursos do computador e fornecer serviços para os programas de
aplicação**.

Ele atua como intermediário entre:

-   Hardware
-   Aplicações
-   Usuários

Principais funções do sistema operacional:

-   gerenciamento de processos
-   gerenciamento de memória
-   gerenciamento de dispositivos de entrada e saída
-   gerenciamento de arquivos
-   segurança e proteção do sistema

------------------------------------------------------------------------

# 2. Kernel e Modos de Operação

## 2.1 O que é o Kernel

O **kernel** é o **núcleo do sistema operacional**.

Ele controla o hardware e gerencia os recursos utilizados pelos
programas.

Responsabilidades do kernel:

-   criação e gerenciamento de processos
-   alocação de memória
-   controle de dispositivos
-   gerenciamento de arquivos
-   proteção do sistema

Sem o kernel, os programas não teriam acesso organizado ao hardware.

------------------------------------------------------------------------

## 2.2 Modos de Operação do Processador

Os sistemas operacionais modernos utilizam **dois modos de execução**.

### Modo Usuário (User Mode)

Características:

-   utilizado por aplicações
-   acesso restrito ao hardware
-   maior segurança

Exemplos de programas executando nesse modo:

-   navegadores
-   editores de texto
-   jogos
-   softwares corporativos

### Modo Kernel (Kernel Mode)

Características:

-   acesso total ao hardware
-   utilizado pelo sistema operacional
-   executa operações críticas

Exemplos de operações:

-   manipulação da memória
-   controle de dispositivos
-   escalonamento de processos

------------------------------------------------------------------------

# 3. Processos

## 3.1 Conceito de Processo

Um **processo** é um **programa em execução juntamente com seu contexto
de execução**.

Enquanto um programa é apenas um arquivo armazenado no disco, o processo
contém:

-   código executável
-   dados
-   registradores da CPU
-   pilha de execução
-   arquivos abertos

------------------------------------------------------------------------

## 3.2 Estados de um Processo

  Estado       Descrição
  ------------ --------------------
  Novo         processo criado
  Pronto       aguardando CPU
  Executando   em execução
  Bloqueado    aguardando evento
  Finalizado   execução concluída

------------------------------------------------------------------------

## 3.3 PCB -- Process Control Block

O sistema operacional mantém uma estrutura chamada **PCB** para cada
processo.

Informações armazenadas:

-   PID
-   estado do processo
-   registradores
-   ponteiros de memória
-   prioridade
-   arquivos abertos

------------------------------------------------------------------------

# 4. Threads

Threads são unidades menores de execução dentro de um processo.

Vantagens:

-   melhor desempenho
-   compartilhamento de memória
-   paralelismo

------------------------------------------------------------------------

# 5. Escalonamento de Processos

## 5.1 Conceito

O **escalonamento** decide qual processo utilizará a CPU.

Objetivos:

-   maximizar uso da CPU
-   garantir justiça entre processos
-   reduzir tempo de resposta

------------------------------------------------------------------------

## 5.2 Algoritmos de Escalonamento

### FCFS

    Fila:
    P1 → P2 → P3

### Round Robin

    P1 → P2 → P3 → P1 → P2 → P3

### Prioridade

  Processo   Prioridade
  ---------- ------------
  P1         Alta
  P2         Média
  P3         Baixa

------------------------------------------------------------------------

# 6. Comunicação entre Processos

Processos podem compartilhar informações por:

-   memória compartilhada
-   pipes
-   mensagens
-   sinais

------------------------------------------------------------------------

# 7. Gerenciamento de Memória

Cada processo possui seu próprio espaço de memória.

    0 ---------------------- MAX
    | código |
    | dados |
    | heap |
    | pilha |

------------------------------------------------------------------------

# 8. Memória Virtual

Permite executar programas maiores que a RAM.

    Endereço lógico → tabela de páginas → frame físico

------------------------------------------------------------------------

# 9. Gerenciamento de Dispositivos

Dispositivos comuns:

-   teclado
-   mouse
-   monitor
-   impressora
-   disco
-   rede

Drivers permitem comunicação:

    Sistema Operacional ↔ Hardware

------------------------------------------------------------------------

# 10. Sistemas de Arquivos

Estrutura de diretórios:

    /
    ├── home
    │   └── aluno
    │       └── trabalho.txt

Operações comuns:

    open()
    read()
    write()
    close()

------------------------------------------------------------------------

# 📚 Conclusão

Os sistemas operacionais gerenciam todos os recursos do computador:

-   processos
-   memória
-   dispositivos
-   arquivos

Esses mecanismos permitem que múltiplos programas executem de forma
eficiente e segura.

------------------------------------------------------------------------

# 🧠 Exercícios

1.  Explique a diferença entre **modo usuário e modo kernel**.
2.  O que é um **processo**?
3.  Qual a diferença entre **processo e thread**?
4.  Explique o funcionamento do **Round Robin**.
5.  O que é **memória virtual**?
6.  Qual a função de um **driver de dispositivo**?
