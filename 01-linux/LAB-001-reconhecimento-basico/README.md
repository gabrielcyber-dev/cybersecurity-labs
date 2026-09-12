# LAB-001 — Reconhecimento básico do sistema Linux

## Objetivo

O objetivo desse laboratório é analisar os resultados de alguns comandos no Linux, entender o que eles fazem, qual informação eles retornam e como aquela informação pode ser útil.

## Ambiente

- Sistema operacional: GNU/Linux
- Usuário: gabriel.esperidiao
- Hostname: pop-os

## Comandos utilizados

Para consultar a finalidade de algum comando, podemos consultar a biblioteca do próprio Linux digitando `man [COMANDO]` 

### `whoami`

O que faz: Exibe o nome de usuário do sistema

Resultado/observação: gabriel.esperidiao

### `hostname`

O que faz: Exibe o nome de host do sistema

Resultado/observação: pop-os

### `pwd`

O que faz: Exibe o diretório atual

Resultado/observação: /home/gabriel.esperidiao/cybersecurity-labs/01-linux/LAB-001-reconhecimento-basico

### `uname -a`

O que faz: exibe todas as informações do sitema

Podemos especificar

`-a`, --all              print all information, in the following order, 
                         except omit -p and -i if unknown:

-s, --kernel-name        print the kernel name
-n, --nodename           print the network node hostname
-r, --kernel-release     print the kernel release
-v, --kernel-version     print the kernel version
-m, --machine            print the machine hardware name
-p, --processor          print the processor type (non-portable)
-i, --hardware-platform  print the hardware platform (non-portable)
-o, --operating-system   print the operating system

## O que aprendi
    Aprendi a identidicar informações básicas sobre sistema operacional local.

## Conclusão
    Aqui aprendi a identificar o usuário atual, nome de host do sistema, pasta atual e exibir informações do sistema através do uname. 