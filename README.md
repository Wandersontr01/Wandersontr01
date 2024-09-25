

<h1> Hi, i'm Wanderson!</h1>
<img align='right' src="https://media.giphy.com/media/B6wdZEDP2TXRkA83o5/giphy.gif" width="200">
<p><em>🎓 Estudando Sistemas de Informação na <a href="https://www.faesa.br">Faesa</a></em></p>
<p><em>📊 Consultor SAP ABAP/CPI | MEGAWORK </em></p>
<p><em>🎯 Buscando oportunidades para ampliar meus conhecimentos e desenvolver minhas habilidades.</em></p>
<br>


---

<h3>Um pouco mais sobre mim...</h3>

```abap
REPORT zwanderson_franca NO STANDARD PAGE HEADING.

TYPES: BEGIN OF ty_stack,
         lv_language TYPE char20,
       END OF ty_stack.

TYPES: BEGIN OF ty_social,
         lv_link TYPE char100,
       END OF ty_social.

TYPES: BEGIN OF ty_wanderson,
         lv_name     TYPE char50,
         lv_location TYPE char30,
         lt_stack    TYPE STANDARD TABLE OF ty_stack WITH EMPTY KEY, 
         lt_social   TYPE STANDARD TABLE OF ty_social WITH EMPTY KEY,
       END OF ty_wanderson.

DATA: ls_wanderson TYPE ty_wanderson,
      lt_stack     TYPE STANDARD TABLE OF ty_stack WITH EMPTY KEY,
      lt_social    TYPE STANDARD TABLE OF ty_social WITH EMPTY KEY.

* Linguagens Favoritas
APPEND VALUE #( lv_language = 'Java'   ) TO lt_stack.
APPEND VALUE #( lv_language = 'ABAP'   ) TO lt_stack.

* Contatos
APPEND VALUE #( lv_link = 'GitHub: https://github.com/Wandersontr01'   ) TO lt_social.
APPEND VALUE #( lv_link = 'Email: wanderson.f.g@hotmail.com'           ) TO lt_social.
APPEND VALUE #( lv_link = 'LinkedIn: www.linkedin.com/in/wandersonfg/' ) TO lt_social.

* Informações
ls_wanderson = VALUE #( lv_name = 'Wanderson Franca Gonçalves'
                        lv_location = 'Vitória/ES'
                        lt_stack    = lt_stack
                        lt_social   = lt_social
                      ).
```
---

<h3>🌐 Vamos conectar e explorar juntos o mundo da programação e da inovação! 🚀</h3>

[![Linkedin: Wanderson](https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/wandersonfg/)
[![Instagram: Wanderson](https://img.shields.io/badge/-Instagram-%23E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/wanderson_gon)
[![Hotmail: Wanderson](https://img.shields.io/badge/-Email-blue?%23E4405F?style=flat-square&logo=microsoftoutlook&logoColor=white)](href=mailto:<nowiki>wanderson.f.g@hotmail.com)


<div>
    <a><img loading="lazy" src="https://github.com/user-attachments/assets/f70a795b-7e99-47d2-8734-881d86651124" width="54" height="54">Adoro me conectar com pessoas diferentes então se quiser dar um oi, ficarei feliz em te conhecer! :)</a>
</div>

---

<h3>Estatísticas 📊</h3>

| [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Wandersontr01&layout=donut)](https://github.com/anuraghazra/github-readme-stats) | ![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Wandersontr01&show_icons=true) |
| --- | --- |




