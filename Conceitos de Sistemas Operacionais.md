# Conceitos de Sistemas Operacionais

---

## 1. Introdução

Os sistemas operacionais fornecem conceitos e abstrações fundamentais que permitem compreender como o computador funciona e como os recursos são gerenciados.

Entre os principais conceitos estão:

- Processos  
- Espaços de endereçamento  
- Arquivos  
- Entrada/Saída  
- Proteção  
- Shell (interpretador de comandos)  

Este documento apresenta uma visão estruturada e organizada desses conceitos.

---

# 1.5.1 Processos

## O que é um Processo?

Um processo é um programa em execução.

Ele é composto por:

- Espaço de endereçamento  
- Registradores da CPU  
- Contador de programa  
- Ponteiro de pilha  
- Lista de arquivos abertos  
- Recursos associados  
- Informações armazenadas na tabela de processos  

---

## Espaço de Endereçamento

Cada processo possui um espaço de memória que vai de:

0 até um valor máximo.

Esse espaço contém:

- Código executável  
- Dados do programa  
- Pilha  

---

## Tabela de Processos

O sistema operacional mantém uma estrutura chamada Tabela de Processos.

Ela armazena:

- Estado do processo  
- Conteúdo dos registradores  
- Informações de controle  
- Recursos associados  

---

## Multiprogramação

Em um sistema multiprogramado:

- Vários processos ficam ativos simultaneamente  
- O sistema operacional alterna a CPU entre eles  
- Cada processo é suspenso e retomado preservando seu estado  

---

## Suspensão e Retomada

Quando um processo é interrompido:

- Seu estado precisa ser salvo  
- Ponteiros de arquivos precisam ser armazenados  
- Registradores precisam ser preservados  
- O estado deve ser restaurado exatamente como estava  

---

## Criação e Término de Processos

Chamadas de sistema principais:

- Criar processo  
- Finalizar processo  
- Esperar processo filho  
- Solicitar memória  
- Liberar memória  

---

## Estrutura em Árvore

Processos podem gerar outros processos:

- Processo Pai  
- Processo Filho  

Isso cria uma árvore de processos.

---

## Comunicação entre Processos (IPC)

Processos podem precisar:

- Compartilhar dados  
- Sincronizar atividades  
- Enviar mensagens  

Essa comunicação é chamada de Comunicação entre Processos (IPC).

---

## Sinais

Sinais são notificações enviadas pelo sistema operacional ao processo.

Exemplos:

- Temporizador expirado  
- Instrução ilegal  
- Endereço inválido  

Funcionam como interrupções em software.

---

## UID e GID

Cada processo possui:

- UID (User Identification)  
- GID (Group Identification)  

O superusuário possui privilégios especiais.

---

# 1.5.2 Espaços de Endereçamento

## Memória Principal

Computadores possuem memória para armazenar programas.

Tipos de sistemas:

- Monoprogramação (um programa por vez)  
- Multiprogramação (vários programas simultaneamente)  

---

## Proteção de Memória

É necessário impedir que:

- Um processo interfira no outro  
- Um processo altere o sistema operacional  

O hardware oferece mecanismos de proteção controlados pelo sistema operacional.

---

## Endereços de 32 e 64 bits

- 32 bits → 2³² endereços  
- 64 bits → 2⁶⁴ endereços  

Isso pode representar um espaço maior que a memória física real.

---

## Memória Virtual

Técnica que:

- Mantém parte da memória no disco  
- Transfere dados conforme necessário  
- Cria a ilusão de memória maior  

O espaço de endereçamento é desacoplado da memória física.

---

# 1.5.3 Arquivos

## Sistema de Arquivos

O sistema operacional fornece:

- Abstração de arquivos  
- Independência do dispositivo físico  
- Estrutura hierárquica  

---

## Operações com Arquivos

Chamadas de sistema:

- Criar  
- Remover  
- Abrir  
- Fechar  
- Ler  
- Escrever  

---

## Diretórios

Diretórios servem para:

- Organizar arquivos  
- Criar hierarquia  
- Permitir agrupamento lógico  

---

## Caminhos

### Caminho Absoluto

Começa no diretório raiz.

Exemplo em sistemas Unix:

/Professores/Prof.Brown/Cursos/CS101

### Caminho Relativo

Depende do diretório atual do processo.

---

## Diretório de Trabalho

Cada processo possui:

- Diretório atual  
- Base para resolução de caminhos relativos  

---

## Descritor de Arquivo

Quando um arquivo é aberto:

- O sistema retorna um número inteiro  
- Esse número é o descritor de arquivo  

---

## Montagem (Mount)

Permite:

- Integrar sistemas de arquivos externos  
- CDs  
- USB  
- Discos externos  

O sistema montado passa a fazer parte da árvore principal.

---

## Arquivos Especiais

Dois tipos principais:

- Arquivos de bloco  
- Arquivos de caractere  

São usados para representar dispositivos de entrada e saída.

---

## Pipes

Pipe é um pseudoarquivo usado para:

- Comunicação entre processos  
- Encadeamento de comandos  

Exemplo:

cat arquivo | sort

---

# 1.5.4 Entrada/Saída

## Dispositivos de E/S

Exemplos:

- Teclado  
- Monitor  
- Impressora  
- Disco  

---

## Subsistema de E/S

Composto por:

- Código independente de dispositivo  
- Drivers específicos para cada hardware  

O sistema operacional abstrai as diferenças físicas dos dispositivos.

---

# 1.5.5 Proteção

## Objetivo

Proteger:

- Arquivos  
- Informações confidenciais  
- Sistema contra intrusos  

---

## Permissões no Unix

Código de 9 bits:

rwxr-x--x

Dividido em:

- Proprietário  
- Grupo  
- Outros  

---

## Significado dos Bits

- r → leitura  
- w → escrita  
- x → execução  

---

# 1.5.6 Shell

## O que é o Shell?

Programa que:

- Interpreta comandos  
- Atua como interface entre usuário e sistema operacional  

---

## Funcionamento Básico

Exemplo:

date

O shell:

- Cria processo filho  
- Executa programa  
- Aguarda término  

---

## Redirecionamento

Saída:

date > arquivo

Entrada:

sort < entrada > saida

---

## Execução em Segundo Plano

Comando:

comando &

Permite continuar usando o terminal enquanto o processo executa.

---

# 1.5.7 Evolução Tecnológica

## Ontogenia Recapitula Filogenia

Na computação:

- Tecnologias evoluem  
- Conceitos retornam  
- Ideias tornam-se obsoletas e depois ressurgem  

---

## Linguagem de Montagem

Retornos históricos:

- Mainframes antigos  
- Minicomputadores  
- Microcomputadores iniciais  

---

## Microprogramação

- IBM 360 introduziu microprogramação  
- RISC trouxe execução direta  
- Java trouxe interpretação novamente  

---

## Memória ao Longo do Tempo

Exemplos históricos:

- IBM 7090 → cerca de 128 KB  
- PDP-1 → 4.096 palavras  
- Microcomputadores iniciais → 4 KB  
- PCs modernos → vários GB  

---

## Hardware de Proteção

Evolução:

- Sem proteção → monoprogramação  
- Com proteção → multiprogramação  

---

## Discos

Evolução histórica:

- Fitas magnéticas  
- Discos rígidos iniciais  
- Diretórios simples  
- Sistemas hierárquicos complexos  

---

# Conclusão

Os conceitos fundamentais de sistemas operacionais incluem:

- Processos  
- Memória  
- Arquivos  
- Comunicação entre processos  
- Proteção  
- Interface com o usuário  

Esses conceitos evoluem conforme a tecnologia avança, mas permanecem como base para compreensão de qualquer sistema computacional moderno.

---