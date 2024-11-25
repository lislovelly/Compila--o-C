# O Processo de Compilação em C

O Compilador converte o programa em C em um executável. 

![program.c.png](program.c.png)

As fases da compilação:

![alt text](fases.png)

1º Pré-Processamento: Remove comentários, incluios arquivos necessários (.i).

![program.i.png](program.i.png)

2º Compilação: O .i é compilado e gerado o .s que contém instruções em Assembly.

![program.i.png](program.s.png)

3º Assembly: O .s é usado para gerar um .o contendo apenas o código em linguagem de máquina.

![program.i.png](program.o.png)

4° Linking: É feito a ligação do objeto com as bibliotecas para gerar o executável final.

![program.i.png](program.png)

Gerar as fases da compilação:

-> gcc --save--temps program.c -o program

