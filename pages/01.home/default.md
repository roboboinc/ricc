---
title: Home
media_order: 'Cartaz Coronavirus Os Simtomas.jpg,Cartaz Coronavirus Homepage.jpg,Coronavirus Contactos emergencias.jpg'
hide_git_sync_repo_link: false
body_classes: 'title-center title-h1h2'
process:
    markdown: true
    twig: true
twig_first: true
---

# Olá!
## Seja Bem Vindo à RICC

Parabéns por conseguires aceder a nossa rede.

Veja o video do PSI ![Jeito_final%20-%20Wi-Fi.m4v](/blog/psi/Jeito_final%20-%20Wi-Fi.m4v?&resize=400,300&loop=1&controls=1&autoplay=0)

Veja o video sobre o POS Virtual ![POS%20VIRTUAL_F_HD_TV.mov](/videos/bci-covid19/POS%20VIRTUAL_F_HD_TV.mov?resize=400,300&loop=1&controls=1&autoplay=0)

[PSI](/blog/psi)

[Ver Videos](/videos?classes=button,big)
![Coronavirus Flyer MINED](Coronavirus%20Contactos%20emergencias.jpg?lightbox=600,400&resize=200,400)
![](Cartaz%20Coronavirus%20Os%20Simtomas.jpg?lightbox=600,400&resize=200,400)
![Como Previnir do Corona](Cartaz%20Coronavirus%20Homepage.jpg?lightbox=600,400&resize=200,400)

**Artigos mais recentes:**
<ul>
{% for post in page.find('/blog').children.order('date', 'desc').slice(0, 5) %}
    <li class="recent-posts">
        <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>
    </li>
{% endfor %}
</ul>