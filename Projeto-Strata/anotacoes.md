





<input type="reset" class="button-default button-default-stroke" value="Limpar">
Retirar formatação padrão do html: 
-Procurar no google arquivo "css normalize";
- Salvar ele na pasta;
- Colocar link dele no html: 
```
    <link rel="stylesheet" href="css/css-normalize.css">
```



Fontes: https://fonts.google.com/

- Procurar a fonte, ir em "selecionar";
- Clicar em "embed", copiar o link�para o html. Ex: <link href="https://fonts.googleapis.com/css?family=Open+Sans&display=swap" rel="stylesheet">
-No CSS colocar apenas: font-family: 'Open Sans', sans-serif;

CSS:

- Sempre usar class para identicar, incluindo t�tulos como h1, h2 e etc;
- Cor RGBA - cor que usa transpar�ncia;
- Color:inherit (heran�a de outro elemento(elemento pai) com a mesma cor, assim ao mudar num muda em outro);
- em (p.e:1m): espa�o relativo ao tamanho da fonte;
- Usar pseudo classe para um elemento, exemplo, na lista tenho que retirar a linhado ultimo item:
last-child � a pseudoclasse.
.ul-alternate li:last-child{
    border:0;
-Tabela: alterar a primeira linha da tabela: peguei dentro da classe table, a tbody, a primeira tr(linha) e as td (coluna) que estão dentro.
.table tbody tr: first-child td{
    border-top: 2px solid #ccc
}    

- Para formatar linhas pares da tabela:
.table tbody tr:nth-child(even) td{

}

- Para formatar linhas ímpares usar: nth-child(odd)

- Formatar coluna: 

.col-1-3:nth-child(1n) {->pega todo multiplo de 1, portanto será pego todas as divisões da coluna.

.col-1-3:nth-child(2n) {->pega multiplo de 2, portanto pegará 2,4,6,8 etc.

.col-1-3:nth-child(3n) ->foi pego multiplo de 3, isto é:3,6,9 etc.

.col-1-3:nth-child(3n-1) {->pega cada multiplo de 3 menos 1;foi pego o terceiro filho menos 1.




