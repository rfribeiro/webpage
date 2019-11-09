---
layout: page
title: About
permalink: /about/
weight: 3
---

# **sobre Mim**

Olá, 

Eu sou o **{{ site.author.name }}**,<br>

Eu sou um curioso que adora programar e ultimamente meus interesses são Data Science e Inteligência Artificial.

Finalizei meu mestrado na Universidade de Campinas (UNICAMP) em 2019. Onde meu trabalho feito foi a detecção de atenção do motorista utilizando uma câmera de profundidade estilo Kinect. Utilizei de métodos de aprendizado de máquina modernos como Deep Learning.

<div class="row">
{% include about/skills.html title="Programação" source=site.data.programming-skills %}
{% include about/skills.html title="Outros Habilidades" source=site.data.other-skills %}
</div>

<div class="row">
{% include title="Qualificações" about/timeline.html %}
</div>

<div class="row">
{% include title="Trabalho" about/work.html %}
</div>