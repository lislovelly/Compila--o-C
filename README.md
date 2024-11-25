# O Processo de Compilação em C

O Compilador converte o programa em C em um executável. 

![alt text](Screenshot_4.png)

As fases da compilação:

![alt text](Screenshot_2.png)

1º Pré-Processamento: Remove comentários, inclui os arquivos necessários (.i).

![alt text](Screenshot_5.png)

2º Compilação: O .i é compilado e gerado o .s que contém instruções em Assembly.

![alt text](Screenshot_7.png)

3º Assembly: O .s é usado para gerar um .o contendo apenas o código em linguagem de máquina.

![alt text](Screenshot_6.png)

4° Linking: É feito a ligação do objeto com as bibliotecas para gerar o executável final.

![alt text](Screenshot_3.png)

Gerar as fases da compilação:

-> gcc --save--temps program.c -o program

