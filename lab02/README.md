## Tarefa sobre catálogo de componentes

[Solução - Catálogo de Componentes](notebook/components-01-catalog-resolution.ipynb)

## Tarefa Web Components 1
> Escreva aqui o código da sua composição de componentes Web, como mostra o exemplo a seguir:
~~~html
<dcc-trigger label="Mundo" action="noticia/mundo/politica" value="Noticia Política mundo.">
</dcc-trigger>

<dcc-trigger label="Brasil P" action="noticia/brasil/politica" value="Noticia Política Brasil.">
</dcc-trigger>

<dcc-trigger label="Brasil E" action="noticia/brasil/esporte" value="Noticia Esporte Brasil.">
</dcc-trigger>

<dcc-trigger label="Brasil E" action="noticia/bahia/esporte" value="Noticia Esporte Bahia.">
</dcc-trigger>



<dcc-lively-talk id="doctor"
                 duration="0s"
                 character="doctor"
                 speech="">
  <subscribe-dcc topic="#/politica"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk id="nurse"
                 duration="0s"
                 character="nurse"
                 speech="">
  <subscribe-dcc topic="noticia/brasil/+"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk id="patient"
                 duration="0s"
                 character="patient"
                 speech="">
  <subscribe-dcc topic="noticia/#"></subscribe-dcc>
</dcc-lively-talk>
~~~

## Tarefa Web Components 2
~~~html
<dcc-trigger label="Next Item" action="next/rss">
</dcc-trigger>

<dcc-rss publish="rss/science" source="https://www.wired.com/category/science/feed">
  <subscribe-dcc topic="next/rss" role="step"></subscribe-dcc>
</dcc-rss>

<dcc-rss publish="rss/design" source="https://www.wired.com/category/design/feed">
  <subscribe-dcc topic="next/rss" role="step"></subscribe-dcc>
</dcc-rss>



<dcc-aggregator publish="aggregate/science" quantity="3">
  <subscribe-dcc topic="rss/science"></subscribe-dcc>
</dcc-aggregator>


<dcc-lively-talk id="doctor"
                 duration="0s"
                 character="doctor"
                 speech="">
  <subscribe-dcc topic="aggregate/science"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk id="nurse"
                 duration="0s"
                 character="nurse"
                 speech="">
  <subscribe-dcc topic="#/science"></subscribe-dcc>
</dcc-lively-talk>

<dcc-lively-talk id="patient"
                 duration="0s"
                 character="patient"
                 speech="">
  <subscribe-dcc topic="#/design"></subscribe-dcc>
</dcc-lively-talk>
~~~
