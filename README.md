# Automatizador_Hydrus

## Descrição
Este freeware gera N cópias alterando as propriedades do Material 1. O dados serão substituidos conforme dados de entrada fornecidos.

## Citação
Please cite the following thesis in any publication in which you find Automatizador_Hydrus was useful.
DOI:  https://doi.org/10.17771/PUCRio.acad.33363

__Citation styles:__

__ABNT:__

ROSA, F. A. Um estudo de procedimentos numéricos e experimentais para uso no ensaio de infiltração monitorada. 2017. 131 f. Dissertação de Mestrdo (Mestrado) - Departamento de Engenharia Civil e Ambiental - DEC, Pontifícia Universidade Católica do Rio De Janeiro - PUC-RIO, Rio de Janeiro. Disponível em: https://doi.org/10.17771/PUCRio.acad.33363.


__APA:__

Rosa, F. A. (2017). Um estudo de procedimentos numéricos e experimentais para uso no ensaio de infiltração monitorada. [Dissertação de Mestrdo, Pontifícia Universidade Católica do Rio De Janeiro - PUC-RIO]. https://doi.org/10.17771/PUCRio.acad.33363. 


__Chicago:__

Rosa, Felipe Alves 2017. « Um estudo de procedimentos numéricos e experimentais para uso no ensaio de infiltração monitorada. » Mestrado Dissertação de Mestrdo, Departamento de Engenharia Civil e Ambiental - DEC, Pontifícia Universidade Católica do Rio De Janeiro - PUC-RIO. https://doi.org/10.17771/PUCRio.acad.33363.

##Instalação
Ao rodar o arquivo .exe pode ser exibida uma tela que diz que o software pode ser de origem desconhecida ou não confiável. Ignorar a mensagem e escolher a opção para "executar mesmo assim".

##Uso

__1-__ Descompactar pasta no diretório C:

__2-__ Colocar arquivo a ser copiado na pasta Pattern

__3-__ Renomear arquivo e pasta do Hydrus a ser copiado para "Eq_Empirica"

__4-__ Abrir o arquivo "Selector.IN" e substituir os parâmetros a serem alterados para

thr_INPUT    ths_INPUT   alfa_INPUT     n_INPUT         ks_INPUT      l_INPUT

__5-__ Colocar os parâmetros a serem gerados na pasta "DadosEntrada" em um arquivo chamado "DADOS_ENTRADA.txt" com o seguinte cabeçalho:

ID	thr	ths	Alfa	n	Ks

__6-__ Executar o programa 


## Para rodar arquivos em Batch no HYDRUS

__1-__ É necessário atualizar o arquivo run.bat, pois o comando para rodar o Hydrus está em letras minúsculas. Alterar h2d_calc para H2D_Calc
__2-__ Colocar os arquivos gerados pelo GeradorAutomáticoHydrus (level_01.dir + run.bat + paths...) na pasta do Hydrus (C:\Program Files (x86)\PC-Progress\HYDRUS 1.xx)
__3-__ Executar o arquivo run.bat. Não é necessário rodar como administrador
