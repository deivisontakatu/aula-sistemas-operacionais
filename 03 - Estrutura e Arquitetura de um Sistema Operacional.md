# 📘 Estrutura e Arquitetura de um Sistema Operacional

## 📌 Descrição Geral

Esta unidade aborda **a estrutura e a arquitetura interna dos Sistemas
Operacionais (SO)**, explorando como esses sistemas são organizados
internamente e como seus componentes cooperam para gerenciar os recursos
de um computador.

O estudo da arquitetura de sistemas operacionais é fundamental para
compreender:

-   Como os programas são executados\
-   Como o hardware é controlado\
-   Como os recursos são compartilhados entre aplicações\
-   Como o sistema mantém estabilidade e segurança

Além disso, entender a organização interna de um sistema operacional
permite analisar **diferentes modelos arquiteturais**, suas vantagens,
limitações e aplicações em ambientes reais.

------------------------------------------------------------------------

# 🎯 Objetivo da Unidade

Ao final desta unidade, o estudante deverá ser capaz de:

-   Compreender **como um sistema operacional é estruturado
    internamente**
-   Identificar o papel do **kernel**
-   Diferenciar **modo usuário e modo kernel**
-   Entender o funcionamento de **processos e memória**
-   Compreender o papel dos **drivers de dispositivos**
-   Identificar diferentes **arquiteturas de sistemas operacionais**
-   Entender como aplicações interagem com o sistema operacional

------------------------------------------------------------------------

# 🧱 1. Visão Geral da Arquitetura de um Sistema Operacional

A **arquitetura de um sistema operacional** define a forma como seus
componentes são organizados e como ocorre a comunicação entre:

-   Hardware\
-   Kernel\
-   Programas de sistema\
-   Aplicações do usuário

Essa estrutura influencia diretamente diversos aspectos do sistema.

### Impactos da arquitetura

Uma boa arquitetura afeta diretamente:

-   Desempenho do sistema\
-   Segurança e proteção de memória\
-   Estabilidade do ambiente computacional\
-   Facilidade de manutenção e atualização\
-   Escalabilidade do sistema

Por isso, o projeto de um sistema operacional envolve decisões
importantes sobre **organização modular e separação de
responsabilidades**.

------------------------------------------------------------------------

# 🧠 2. Kernel: o Núcleo do Sistema Operacional

O **kernel** é o componente central de um sistema operacional.

Ele funciona como o **intermediário entre hardware e software**, sendo
responsável por controlar todos os recursos do computador.

Sem o kernel, os programas não teriam acesso organizado ao hardware.

------------------------------------------------------------------------

## Principais responsabilidades do kernel

Entre as principais funções do kernel estão:

-   Gerenciamento de processos
-   Gerenciamento de memória
-   Controle de dispositivos de entrada e saída
-   Gerenciamento do sistema de arquivos
-   Comunicação entre hardware e software
-   Implementação de mecanismos de segurança

O kernel possui acesso completo ao sistema, pois opera em **modo
privilegiado**.

------------------------------------------------------------------------

# 🔁 3. Processos

Um **processo** é um programa em execução.

Cada processo possui seu próprio conjunto de recursos e informações.

## Componentes de um processo

-   Código do programa
-   Dados
-   Pilha de execução
-   Registradores da CPU
-   Arquivos abertos
-   Estado do processo

## Multiprogramação

Sistemas modernos executam **múltiplos processos simultaneamente**,
alternando rapidamente o uso da CPU entre eles.

------------------------------------------------------------------------

# 📋 Tabela de Processos

O sistema operacional mantém uma estrutura chamada **Tabela de
Processos**, contendo:

-   PID (identificador do processo)
-   estado do processo
-   registradores
-   ponteiros de memória
-   arquivos abertos

Essa estrutura permite suspender e retomar processos corretamente.

------------------------------------------------------------------------

# 🧠 4. Espaço de Endereçamento

Cada processo possui um **espaço de memória próprio** contendo:

-   código executável
-   variáveis
-   pilha
-   heap

Representação simplificada:

0 ------------------------------ MAX

## Proteção de memória

A proteção garante que processos não interfiram entre si e que não
possam modificar o kernel.

------------------------------------------------------------------------

# 💾 5. Memória Virtual

A memória virtual permite executar programas maiores que a RAM
disponível.

Parte dos dados fica:

-   na RAM
-   no disco

O sistema operacional move dados entre esses dois locais conforme
necessário.

------------------------------------------------------------------------

# 📂 6. Sistema de Arquivos

O sistema de arquivos organiza dados em dispositivos de armazenamento.

## Operações comuns

-   criar arquivos
-   abrir arquivos
-   ler dados
-   escrever dados
-   remover arquivos

## Estrutura de diretórios

/ ├── usuarios │ └── aluno │ └── documentos │ └── trabalho.txt

------------------------------------------------------------------------

# 🔌 7. Entrada e Saída

Dispositivos de E/S incluem:

-   teclado
-   monitor
-   mouse
-   disco
-   impressora
-   rede

O sistema operacional controla esses dispositivos por meio de
**drivers**.

------------------------------------------------------------------------

# 🧩 8. Drivers de Dispositivo

Drivers são programas que permitem comunicação entre o sistema
operacional e hardware específico.

Eles abstraem as diferenças entre dispositivos.

------------------------------------------------------------------------

# 🏗️ 9. Arquiteturas de Sistemas Operacionais

## Arquitetura Monolítica

Todos os serviços executam dentro do kernel.

Vantagens:

-   alto desempenho

Desvantagens:

-   menor isolamento de falhas

------------------------------------------------------------------------

## Microkernel

Apenas funções essenciais permanecem no kernel.

Serviços adicionais executam em modo usuário.

Vantagens:

-   maior segurança
-   modularidade

Desvantagens:

-   maior custo de comunicação

------------------------------------------------------------------------

## Arquitetura Híbrida

Combina características de monolítico e microkernel.

Exemplos:

-   Windows
-   macOS

------------------------------------------------------------------------

# 📚 Considerações Finais

A arquitetura de um sistema operacional determina como os recursos do
computador são organizados e controlados.

Compreender conceitos como:

-   kernel
-   processos
-   memória
-   sistema de arquivos
-   drivers
-   arquiteturas de kernel

permite entender profundamente o funcionamento de sistemas modernos.
