##Marcação Básica 

A marcação permite que você escreva usando um plano de formato de texto fácil de ler e fácil de escrever, na qual converte para um HTML valido para ser visualizado no GitHub.

##Escrita básica

###Parágrafos 

Os parágrafos na marcação são apenas um ou mais consecutivas linhas de texto seguido de um ou mais espaços em branco.
```
On July 2, an alien mothership entered Earth's orbit and deployed several dozen saucer-shaped "destroyer" spacecraft, each 15 miles (24 km) wide.

On July 3, the Black Knights, a squadron of Marine Corps F/A-18 Hornets, participated in an assault on a destroyer near the city of Los Angeles.
```

###Cabeçalhos 

Você pode criar um cabeçalho adicionando um ou mais # símbolos antes do cabeçalho do texto. O numero de símbolos que você usa determinara o tamanho do cabeçalho.
```
# The largest heading (an <h1> tag)
## The second largest heading (an <h2> tag)
…
###### The 6th largest heading (an <h6> tag)
```

###Bloco de Notas

Você pode indicar o bloco de notas com um >.
```
In the words of Abraham Lincoln:

> Pardon my french
```

###Estilo de texto

Você pode fazer um texto em Negrito ou Itálico.
```
*This text will be italic*
**This text will be bold**
```
Ambos Negrito e Itálico podem usar tanto um * ou um _ estilizando um texto em volta. Isto permite que você combine Negrito e Itálico se for preciso.
```
**Everyone _must_ attend the meeting at 5 o'clock today.**
```

##Listas

###Listas desordenadas

Você pode fazer uma lista desordenada precedendo itens da lista com tanto um * ou um -.
```
* Item
* Item
* Item

- Item
- Item
- Item
```
###Listas ordenadas

Você pode fazer uma lista ordenada precedendo itens com um numero. 
```
1. Item 1
2. Item 2
3. Item 3
```

###Listas aninhada

Você pode criar listas aninhadas pelas listas de recuo por dois espaços.
```
1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3
```

##Formatação de código 

###Formatos nas entrelinhas

Use uma única crase para formatar um texto num formato de mono espaço especial. Tudo dentro das aspas aparecem como é, sem nenhum outro formato especial.
```
Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.
```

#Linhas múltiplas

Você pode usar aspas triplas para formatar o texto como seu próprio bloqueio distinto. 

Check out this neat program I wrote:

```
x = 0
x = 2 + 2
what is x
```

#Links

Você pode criar um link nas entrelinhas envolvendo os links nas chaves no texto, e então envolva o link nos parênteses.

Por exemplo, para criar um hiperlink no www.github.com , com um link textual que diz, visite GitHub!, você escreveria esta marcação: ``` [Visit GitHub!](www.github.com). ```





