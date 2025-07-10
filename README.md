# DIO - TRILHA JAVA BÁSICO									
									
## PROGRAMAÇÃO ORIENTADA A OBJETOS E ESTRUTURAS DE DADOS COM JAVA  									
									
### DESAFIO - JOGO SUDOKU									
									
Projeto criado utilizando Programação Orientada a Objetos (POO) e Estrutura de dados.									
									
Realizado inicialmente um fork no diretório [Sudoku para terminal](https://github.com/digitalinnovationone/sudoku).  									
									
Posteriormente, foi incluido no diretório do fork, o diretório do [Sudoku para interface gráfica](https://github.com/digitalinnovationone/sudoku/tree/ui). 									
									
Este diretório possui dois arquivos para execução do jogo:  									
1. Main - para executar no terminal  									
									
2. UIMain - para executar na interface gráfica do Java  									
									
Foi utilizado como argumentos, os seguintes dados:  
1º caracter -> corresponde a linha.  
2º Caracter -> corresponde a coluna.  
3º caracter -> corresponde ao número a ser incluído.  
4º caracter -> recebe dois valores: true (para o número fixo no tabuleiro) e false (para o número a ser incluído pelo usuário).

|     L/C     |   Coluna 0  |  Coluna 1   |  Coluna 2   |  Coluna 3   |  Coluna 4   |   Coluna 5  |  Coluna 6   |  Coluna 7   |  Coluna 8   |
|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|:-----------:|  
|   Linha 0   | 0,0;4,false | 0,1;1,false | 0,2;2,false | 0,3;5,true  | 0,4;8,false | 0,5;6,false | 0,6;7,true  | 0,7;9,true  | 0,8;3,false |
|   Linha 1   | 1,0;7,false | 1,1;3,true  | 1,2;6,true  | 1,3;1,false | 1,4;9,true  | 1,5;4,true  | 1,6;5,false | 1,7;8,true  | 1,8;2,false | 
|   Linha 2   | 2,0;9,true  |	2,1;5,false |	2,2;8,false | 2,3;3,true  | 2,4;7,false | 2,5;2,false | 2,6;4,false | 2,7;1,false | 2,8;6,true  |
|   Linha 3   | 3,0;5,false | 3,1;4,false | 3,2;9,false | 3,3;7,false | 3,4;1,true  | 3,5;3,false | 3,6;2,false | 3,7;6,false | 3,8;8,true  |
|   Linha 4   | 4,0;8,true  | 4,1;7,true  | 4,2;1,true  | 4,3;6,false | 4,4;2,true  | 4,5;9,false |	4,6;3,true  | 4,7;4,true  | 4,8;5,true  |
|   Linha 5  	|	5,0;6,true  | 5,1;2,false | 5,2;3,false | 5,3;4,false | 5,4;5,true  | 5,5;8,false | 5,6;9,false | 5,7;7,false | 5,8;1,false |
|   Linha 6   | 6,0;2,true  | 6,1;8,false | 6,2;7,false | 6,3;9,false | 6,4;3,false | 6,5;1,true  | 6,6;6,false | 6,7;5,false | 6,8;4,true  |
|   Linha 7   | 7,0;3,false | 7,1;9,true  | 7,2;4,false | 7,3;8,true  | 7,4;6,true  | 7,5;5,false | 7,6;1,true  | 7,7;2,true  | 7,8;7,false |
|   Linha 8  	| 8,0;1,false | 8,1;6,true  | 8,2;5,true  | 8,3;2,false | 8,4;4,false | 8,5;7,true  | 8,6;8,false | 8,7;3,false | 8,8;9,false |

