---
aliases:
  - obsidian formating
---
***Mas info:*** [WEB](https://help.obsidian.md/How+to/Format+your+notes)
___
# Links avanzados
[Obsidian URI](https://help.obsidian.md/Advanced+topics/Using+Obsidian+URI) links can be used to open notes in Obsidian either from another Obsidian vault or another program.
For example, you can link to a file in a vault like so (please note the [required encoding](https://help.obsidian.md/Advanced+topics/Using+Obsidian+URI#Encoding)):
```md
[Link to note](obsidian://open?path=D:%2Fpath%2Fto%2Ffile.md)
```
[Web](https://help.obsidian.md/How+to/Format+your+notes)
==Hermano = Akh==

```query
tag:#PC
```
# Callouts

> [!abstract] [[resumen - summary - abstract (cua)]] [[ejemplo - example - lista (cua)]]

> [!todo]  [[bien - hecho - todo (cua)]]

> [!tip] [[consejo - tip (cua)]]

> [!success] [[exito-success (cua)]]

> [!question] [[pregunta - question (cua)]]

> [!warning] [[peligro - warning (cua)]]

> [!failure] [[problema - failure (cua)]]

> [!danger] [[peligro - warning (cua)]]

> [!bug] [[bug (cua)]]

> [!example] [[ejemplo - example - lista (cua)]]

> [!Quote]  [[biblio (cua)]] [[cita - quote (cua)]]
>Donde está el baño?
\-  *Nelson Mandela*

> [!question] Can callouts be nested? 
> > [!todo] Yes!, they can. 
> > > [!example] You can even use multiple layers of nesting.
# This is a heading 1 
## This is a heading 2 
### This is a heading 3 
#### This is a heading 4 
##### This is a heading 5 
###### This is a heading 6

```query
file:("Obsidian")
```

Link Interno: [[Kepler]]
Link a una [pagina web](https://help.obsidian.md/) (Ayuda)
Link Externo: [Kepler](File:///home/alejandro/akrai/Dropbox/Azahara/Hoplitas/Interior/Kepler.md) [^2]

|First Header | Second Header|
|------------ | ------------|
|Content from cell 1 | Content from cell 2|
|Content in the first column | Content in the second column|
|||
|||
|||
|||


- [x] #PC, [links](), **formatting** supported 
- [x] list syntax required (any unordered or ordered list supported) 
- [x] this is a complete item 
- [?] this is also a complete item (works with every character) 
- [ ] this is an incomplete item 
- [ ] tasks can be clicked in Preview to be checked off

~~Tachado~~

==highlight text==

Here's a simple footnote,[^1] and here's a longer one.[^bignote]
Here is an inline footnote ^[Aprendí a hacer estas solito y aún no he descuierto una fuente que hable de ellas]

Indent:![[Atajos#Aprender]]Indent without title([link to blocks](https://help.obsidian.md/How+to/Link+to+blocks)):![[Atajos#^59532c]]
Comments: \%\% escribir aquí y no se verá en lectura \%\%
%% eso es... %%

`{ my code with Alt + x}` 

```eMail
with alt + c
To target an HTML link to a specific page in a PDF file, add #page=[page number] to the end of the link's URL
```

# Templates:
date:{{date.DD/MM/YYY}}
day of the week {{date:dddd}}
day of the year {{date:DDD}}
Last two numbers of the gregorian year: {{date:YY}}
Number of the week on the year {{date:w}}
Hour in 12h format with minutes: {{time:hh:mm}}
Hour in 24h format avec des 0s avant les chiffres seules: {{time:HH:mm}}
~~Hour without 0s: {{time:H:m}}~~




[^1]: meaningful!
[^bignote]: Here's one with multiple paragraphs and code.
[^2]: Antes lo hacia mal ([Internal pdf](<D:\Users\Alejandro\Videos\Finger_2010 electric_fish.pdf>)) y no se ni como funcionaba. Creo que los abría el navegador o algo.