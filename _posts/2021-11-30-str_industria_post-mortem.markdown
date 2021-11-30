---
layout: post
title: "STR Industra Post Mortem"
date: 2021-11-30 19:15:30
categories: post-mortem
---

###### Artigo original : https://str-postmortem.videmogroup.org/
###### Demo na pouet : https://www.pouet.net/prod.php?which=10428

###### Contexto

Post mortem escrito após a inercia demoparty 2003. 


Abaixo segue uma tradução do artigo original. 


# VI Demogroup - STR Industria Post Mortem
###### Autor : Jae686

STR: Industria foi uma demo cujo o proósito era ser uma introdução do nosso demogroup para a *demoscene* portuguesa.
A demo é um *fly-by* por um cenário *flat-shaded*

Porque fazer uma demo com um simples *fly-by* ?

Quando contactei o filami para formarmos um demogroup, eu não fazia idea das competencias dele relativamente a computação gráfica, naquela altura, e nem de quanto tempo seria necessário para implementar uma dada funcionalidade no motor gráfico.

E além disso, nessa altura, eu não tinha conhecimentos sobre a criação de texturas e o respetivo processo para mapear essa textura em um modelo.
A unica competência que tinha na altura era de modelação 3D em [Wings3D](http://http://www.wings3d.com/) 


Portanto, a unica forma de ser possivel termos uma demo pronta para a inercia demoparty (em 2003), era de fazer a demo o tão simples como possível, do ponto de vista tecnológico. Portanto a unica coisa em que podiamos "carregar" era nos modelos 3d utilizados na demo.

Graças a implementação da linguagem de scriping LUA, o processo de construção da demo foi bastante flexível e fez encurtar o tempo de desenvolvimento da demo.

O conceito da demo em sí é bastrante simples : um *fly-by* sobre um cenário industrial com *flat shading*
A musica foi feita pelo priprio filami.

## O Bom

Mesmo sem experiência e trabalhando via internet (apenas nos encontrando cara a cara na própria demoparty), a equipa foi capaz de começar e acabar um projeto do zero, o que foi possível graças a dedicação do filami ao projeto.

Até foi possivel criar mais 2 cenarios adicionais no pary place (a primeira e segunda cena), e as colocar na demo. A coordenação entre os graficos e a musica (ja feita antes da party), também foi feita no party place.

Fizemos uma boa primeira introdução da demoscene portuguesa, e aperndemos que a tecnologia não é tudo. :)

# O Mau

*Bugs* inesperados, que podiam comprometer a conclusão da demo, ocorreram no party place. Também houve alguma pressão, devido a constrangimentos de tempo, para fazer as cenas extra a tempo para a submisão da demo para a competição.
A implementação de funcionalidades que não estavam planeadas também foram um problema. Se tivesem sido planeadas com antencedência, poderiamos ter feito um melhor uso das mesmas.

# Conclusão

Com esta demo, aprendendemos imenso sobre as dificuldades e problemas no nosso processo de dcesenvolvimento, assim como aprendemos como melhorar no futuro.
Também houve muito detalhe que foi modelado, mas que não foi devidamente explorado (o telespecador não podia ver os detalhas durante a demo = tempo de desenvolvimento desperdiçado)

