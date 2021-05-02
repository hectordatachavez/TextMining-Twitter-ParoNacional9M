# `Hello, World!`

This is part of a series of posts/repositories in which I explore the use of different tools relevant for my work as social-environmental impact research, ranging from visualizations to predictive modeling using \#TidyTuesday or other open datasets.

:rainbow_flag:

## What is this about?

This is a social media, text-mining project around the *"Paro Nacional"* (National Strike), an initiative of women in Mexico back in 2020 as protest against feminicides.

I wanted to practice accessing and mining social media text data using [`tidyverse`](https://www.tidyverse.org/), [`tidytext`](https://www.tidytextmining.com/), [`rtweet`](https://github.com/ropensci/rtweet) and [`sentimentr`](https://github.com/trinker/sentimentr) R packages. The purpose was not only technical. My interest was also to uncover more of the story, how women in Mexico use social media to organize themselves, to demand justice, and how they support each other through social media.

Outputs are both an `*Rmd` file and a formatted `HTML` file. At the time I was really into css-ing HTML output from R-markdown.

:star: If you would like to have a look at the data, please reach out. :handshake:

## What are my references?

I consulted the "[*Text Mining with R*](https://www.tidytextmining.com/)" book by [Julia Silge](https://github.com/juliasilge) & [David Robinson](http://varianceexplained.org/). There were a lot of blog-posts on sentiment analysis of tweets I consulted to structure this mining project, especially a few for sentiment analysis of text in Spanish. This one from [*Juan Bosco Mendoza Vega*](https://rpubs.com/jboscomendoza/analisis_sentimientos_lexico_afinn) was useful.

The winner for the "Best Design" award in the First Shiny Context (in 2019) was inspirational to make an interactive visualization of word networks. The winner was the "[69 Love Songs: A Lyrical Analysis](https://committedtotape.shinyapps.io/sixtyninelovesongs/)" app made by [David Smale](https://community.rstudio.com/u/committedtotape/). (I didn't succeed in making the word network visualization as cool as David's, but it was good learning.)

## If you want to know more about this movement, check out:

Paulina Villegas [article](https://www.nytimes.com/es/2020/03/10/espanol/mexico-paro-mujeres-protestas.html) in the NYT, in Spanish.

The [text](https://www.cndh.org.mx/noticia/paro-nacional-de-mujeres-contra-la-violencia-la-mujer-y-los-feminicidios#:~:text=El%2006%20de%20marzo%20de,poblaci%C3%B3n%20femenina%20en%20las%20esferas) from María de la Luz Estrada, Coordinator of the National Citizen Observatory of Feminicides, and references therein.

**Let's get started** :unicorn: **!**

PD: you can preview the HTML output [here](https://rawcdn.githack.com/hectordatachavez/TextMining-Twitter-ParoNacional9M/32d46307a3ecffe8af2108eb636fd97ee4fd5a2c/Text-Mining---Paro-Nacional.html). (A link possible thanks to [raw.githack](https://raw.githack.com/).)
