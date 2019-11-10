---
layout: page
title: Sobre
permalink: /about/
weight: 3
---

<style>
img {
  float: right;
}
</style>

# **Sobre Mim**

Eu sou o **{{ site.author.name }}**,<br>

<p><img src="{{ site.author.image }}" alt="Rafael Ribeiro" style="width:180px;height:180px;margin-left:10px;">
Eu sou um curioso que adora programar e ultimamente meus interesses são Data Science e Inteligência Artificial.<p></p>
<p></p>
Tenho trabalhado com desenvolvimento em Android durante 10 anos
</p>
Finalizei meu mestrado na Universidade de Campinas (UNICAMP) em 2019. Onde meu trabalho feito foi a detecção de atenção do motorista utilizando uma câmera de profundidade estilo Kinect. Utilizei de métodos de aprendizado de máquina modernos como Deep Learning.
<p></p>


<div class="row">
{% include about/skills.html title="Programação" source=site.data.programming-skills %}
{% include about/skills.html title="Data Science" source=site.data.data-science %}
</div>

<div class="row">
{% include about/skills.html title="Certificações" source=site.data.certificacoes %}
{% include about/skills.html title="Outras Habilidades" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html title="Qualificações" %}
</div>

<div class="row">
{% include  about/work.html title="Experiência Profissional" %}
</div>