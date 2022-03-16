# Insper_Programa-Web_Trab3

Detalhes do exercício:
Esse exercício envolve criar um arquivo CSS do zero para estilizar uma página html.
Baixe o  arquivo aula-03-exercicio.zip em anexo, que contém um arquivo html e um arquivo de imagem (gráfico). O arquivo html representa, de forma resumida e simplificada, o conteúdo da página: https://pudding.cool/projects/vocabulary/index.html.
O objetivo é estilizar o conteúdo com CSS, para deixá-lo com uma aparência semelhante à página original do Pudding. Para isso é preciso inicialmente criar um arquivo .css no mesmo diretório e incluir um link para esse arquivo no <head> do arquivo html, usando a tag <link> (referência: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link).
Vá montando o CSS, criando as regras para estilizar cada parte do documento. Fique à vontade para alterar o arquivo html e incluir classes nos elementos existentes para facilitar sua identificação e formatação no CSS.
Utilize propriedades que vimos na aula, como color, font-size, font-style, font-width, text-align, margin, padding, width, max-width etc. (referência: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
Não se preocupe em reproduzir as fontes originais: utilize as fontes padrão, com as declarações  font-family: serif; e font-family: sans-serif; 
Não se preocupe com o logo do Pudding no alto, pode ignorá-lo. 
Um padrão bastante utilizado (e responsivo) para centralizar um bloco de texto em relação a um container exterior é usar margens laterais automáticas com uma definição de largura máxima para o bloco. Algo como: 
p.corpo-do-texto {

max-width: 36rem; /* ou um valor que vc julgue mais adequado */

margin: 1rem auto; /*lembrem que isso é uma abreviação: o primeiro valor, "1rem", vai ser usado para as margens verticais (margin-top e margin-bottom); o segundo, "auto", para as horizontais (margin-right e margin-left)*/

}
