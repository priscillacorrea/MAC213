# Formulas

Agora que ja temos nossos dados importados, vamos comecar a extrair informacoes deles.

Lembre-se que na [pagina](http://dados.prefeitura.sp.gov.br/dataset/perfil-dos-educandos-cor-raca-idade-sexo-necessidades-educacionais-especiais) que fizemos o download do CSV, temos o arquivo "Dicionario" que sera importante para "traduzirmos" as siglas presentes no nosso CSV.

## Introducao a funcoes

As funcoes no excel sao uma das maneiras mais simples de automatizarmos processos, o que e muito util, desde quando estamos trantando pequenos conjuntos de valores ate tabelas bastante grandes.

## Introduzindo valores
Para introduzir um valor no excel, basta clicar na celula em questao e digitar o valor que quisermos. Aqui, usamos o termo valor de forma generica: Pode ser uma quantia em dinheiro, uma data, um nome. O excel e capaz de tratar todos estes tipos de dados. Vamos ver como informar o questa nao celula ao excel mais a frente.

![Valores](Valores.gif)


## Introduzindo funcoes
Para introduzir funcoes, fazemos de maneira similar aos valores: clicamos na celula que queremos alterar e digitamos o que desejamos inserir. Entretanto, para avisarmos ao excel que queremos que aquilo seja avaliado como uma funcao ao inves de um valor, basta colocarmos um simbolo de **=** no comeco do que estamos digitando.

Uma vantagem de escrever assim, o excel imediatamente reconhece que estamos escrevendo uma formula e mostra uma serie de opcoes assim que comecamos a escrever o nome da funcao.

![Funcao](Funcao.gif)

## 

## Algumas funcoes uteis

Vamos agora comecar algumas analises simples dos dados que importamos, utilizando algumas funcoes do excel

### Funcao CONT.SE
A funcao CONT.SE e bastante util e pode nos informar o numero de celulas que atendem a algum criterio. Vamos supor como exemplo que desejamos contar quantos alunos sao do sexo masculino e quantos sao do sexo feminino. Temos um numero enorme de dados, mas essa analise fica muito simples com a funcao CONT.SE

Primeiramente, vamos criar uma nova planilha, para organizarmos nossas analises. Vamos clicar no botao +, localizado na parte inferior da nossa tela.

Uma nova aba vai se abrir. Podemos clicar duas vezes sobre ela para renomea-la. Vamos chama-la de analises.

![NewSheet](NewSheet.gif)

Agora nessa nova planilha, vamos usar a funcao CONT.SE para verificar a distribuicao de alunos do sexo masculino e feminino.

* Selecionamos uma celula e digitamos o simbolo de =
* Digitamos CONT.SE. Perceba que o excel comeca a mostrar opcoes conforme voce digita, nao sendo necessario digitar o comando inteiro.
* Clique sobre o nome CONT.SE para inserir a formula na celula.

![InsertForm](insertForm.gif)

Conforme aparece na tela, o comando CONT.SE leva dois argumentos:

    =CONT.SE(Onde você quer procurar?; O que você quer procurar?)
    
Queremos prcurar quantos alunos do sexo feminino estao presentes na coluna P da planilha "idadeserieneeracadez17". Entao vamos entrar esses dois argumentos na nossa formula.

Depois de inserir o esqueleto da CONT.SE na celula, vamos agora selecionar os argumentos.



