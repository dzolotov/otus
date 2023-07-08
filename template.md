---
marp: true
style: |
  section {
      background-image: url("https://raw.githubusercontent.com/dzolotov/otus/main/theme/background_third.jpg");
      background-size: cover;
  }

  p {
      font-weight: normal;
      font-family: Roboto;
  }

  ul, ol {
      padding-left: 32px;
  }

  ul li {
      padding-left: 8px;
      font-weight: normal;
      font-family: Roboto;
      font-size: 90%;
      list-style-type: "\25B6";
  }

  ul li::marker {
      font-weight: normal;
      font-family: Roboto;
      font-size: 90%;
      color: orange;
  }

  ol li {
      padding-left: 8px;
      font-weight: normal;
      font-family: Roboto;
      font-size: 90%;
      padding-left: 16px;
  }

  ol li::marker {
      font-weight: normal;
      font-family: Roboto;
      font-size: 90%;
      padding-left: 16px;
      color: orange;
  }

  h1 {
      position: absolute;
      left: 5%;
      top: 10%;
      color: black;
      font-weight: bold;
      font-size: 32pt;
      font-family: Roboto;
  }

  h2 {
      position: absolute;
      left: 5%;
      top: 15%;
      color: orange;
      font-size: 15pt;
      font-weight: bold;
      font-family: Roboto;
  }

  ol li::marker {
      color: orange;
      font-size: 24pt;
      font-weight: bold;
      font-family: Roboto;
  }

  ol li {
      color: black;
      font-size: 24pt;
      font-weight: normal;
      font-family: Roboto;
  }

  section.first_page {
      background-image: url("https://raw.githubusercontent.com/dzolotov/otus/main/theme/background.jpg");
      background-size: cover;
  }

  section.first_page h1 {
      position: absolute;
      top: 35%;
      width: 50%;
      padding-left: 5%;
      color: white;
      font-size: 56pt;
      font-weight: bold;
      font-family: Roboto;
  }
  section.first_page h3 {
      color: white;
      font-size: 18pt;
      font-family: Roboto;
      position: absolute;
      bottom: 7%;
      left: 11%;
  }

  section.second_page h1 {
      position: absolute;
      top: 40%;
      width: 40%;
      left: 11%;
      color: black;
      font-size: 40pt;
      font-weight: bold;
      font-family: Roboto;
  }
  section.second_page img[alt="REC"] {
      position: absolute;
      top: 25%;
      left: 11%;
      width: 5%;
      height: 5%;
  }
  section.second_page h2 {
      position: absolute;
      top: 22%;
      left: 18%;
      color: black;
      font-size: 21pt;
      font-weight: bold;
      font-family: Roboto;
  }

  section.second_page h3 {
      position: absolute;
      top: 67%;
      left: 18%;
      width: 27%;
      color: black;
      font-size: 18pt;
      font-weight: normal;
      font-family: Roboto;
  }

  section.second_page img[alt="PLUS"] {
      position: absolute;
      top: 70%;
      left: 11%;
      width: 5%;
      height: 9%;
  }

  section.second_page {
      background-image: url("https://raw.githubusercontent.com/dzolotov/otus/main/theme/background_third.jpg");
      background-size: cover;
  }

  section.third_page h6, section.last_page h6 {
      position: absolute;
      left: 5%;
      top: 10%;
      color: orange;
      font-weight: normal;
      font-family: Roboto;
      font-size: 15pt;
  }
  section.third_page h1, section.last_page h1 {
      position: absolute;
      left: 5%;
      top: 15%;
      color: black;
      font-weight: bold;
      font-size: 32pt;
      font-family: Roboto;
  }
  section.third_page img, section.last_page img {
      position: absolute;
      left: 5%;
      width: 160px;
      height: 160px;
      top: 60%;
      padding-left: 32px;
      padding-top: 32px;
      padding-bottom: 32px;
      background: linear-gradient(90deg, #ffab40 0%, #ffab40 60%, white 60.1%, white 100%);
  }

  section.third_page h2, section.last_page h2 {
      font-size: 15pt;
      font-weight: bold;
      font-family: Roboto;
      position: absolute;
      left: 25%;
      top: 60%;
  }

  section.third_page marp-pre, section.last_page marp-pre {
      position: absolute;
      left: 25%;
      top: 70%;
      background-color: white;
      border: none;
      padding: 0;
  }

  section.third_page marp-pre code, section.last_page marp-pre code {
      font-weight: normal !important;
      font-family: Roboto !important;
  }

  section.third_page, section.last_page {
      background-image: url("https://raw.githubusercontent.com/dzolotov/otus/main/theme/background_third.jpg");
      background-size: cover;
  }

  section.page_about img {
      position: absolute;
      left: 5%;
      width: 288px;
      height: 288px;
      top: 30%;
      padding-left: 32px;
      padding-top: 32px;
      padding-bottom: 32px;
      background: linear-gradient(90deg, #ffab40 0%, #ffab40 60%, white 60.1%, white 100%);
  }

  section.page_about h2 {
      font-size: 16pt;
      font-weight: bold;
      font-family: Roboto;
      position: absolute;
      left: 35%;
      top: 32%;
  }

  section.page_about ul {
      position: absolute;
      left: 33%;
      top: 40%;
  }

  section.page_about li {
      font-size: 14pt;
      font-family: Roboto;
      font-weight: normal;
      line-height: 1.8;
  }

  section.page_rules {
      background-image: url(https://raw.githubusercontent.com/dzolotov/otus/main/theme/rules.png);
      background-size: cover;
  }

  section.page_route ul {
      padding-top: 64px;
      padding-left: 8px;
  }
  section.page_route li {
      background-color: #ffd966;
      list-style-type: none;
      padding-top: 8px;
      padding-bottom: 8px;
      padding-left: 16px;
      margin-top: 32px;
      margin-bottom: 32px;
      font-size: 18pt;
      font-family: Roboto;
      font-weight: normal;
      width: 50%;
  }

  section.page_section {
      background-image: url("https://raw.githubusercontent.com/dzolotov/otus/main/theme/section.jpg");
      background-size: cover;
  }

  section.page_section h1 {
      color: white;
      font-size: 49pt;
      font-family: Roboto;
      font-weight: 900;
      position: absolute;
      top: 45%;
      left: 7%;
      right: 7%
  }

  section.page_withimage {
      padding-right: 50%;
  }

  section.page_withimage img {
      position: absolute;
      right: 0;
      top: 0;
      bottom: 0;
      left: 50%;
      width: 50%;
      margin-top: auto;
      margin-bottom: auto;
  }

  section.page_image img {
      position: absolute;
      height: 480px;
      position: absolute;
      top: 128px;
      left: 0px;
      right: 0px;
      margin-left: auto;
      margin-right: auto;        
  }

  section.page_reflexion {
      background-image: url(theme/reflexion.png);
      background-size: cover;
  }

  section.next_webinar_page img[alt="academy"] {
      position: absolute;
      left: 8%;
      top: 35%;
      width: 96px;
      height: 96px;
  }
  section.next_webinar_page img[alt="check1"] {
      position: absolute;
      left: 8%;
      top: 75%;
      width: 48px;
      height: 48px;
  }
  section.next_webinar_page img[alt="check2"] {
      position: absolute;
      left: 35%;
      top: 75%;
      width: 48px;
      height: 48px;
  }
  section.next_webinar_page img[alt="redflag"] {
      position: absolute;
      left: 65%;
      top: 75%;
      width: 48px;
      height: 48px;
  }
  section.next_webinar_page h3 {
      position: absolute;
      left: 20%;
      top: 32%;
      color: orange;
      font-family: Roboto;
      font-weight: normal;
      font-size: 20pt;
  }
  section.next_webinar_page h2 {
      position: absolute;
      left: 20%;
      top: 38%;
      color: black;
      font-family: Roboto;
      font-weight: bold;
      font-size: 32pt;
  }
  section.next_webinar_page h4 {
      font-family: Roboto;
      font-weight: normal;
      font-size: 19pt;
      position: absolute;
      left: 13%;
      top: 72.5%;
      width: 20%;
      color: black;
  }
  section.next_webinar_page h5 {
      font-family: Roboto;
      font-weight: normal;
      font-size: 19pt;
      position: absolute;
      left: 40%;
      top: 72.5%;
      width: 20%;
      color: black;
  }
  section.next_webinar_page h6 {
      font-family: Roboto;
      font-weight: normal;
      font-size: 19pt;
      position: absolute;
      left: 70%;
      top: 72.5%;
      width: 23%;
      color: black;
  }
---
<!-- _class: first_page -->
# Онлайн образование
### otus.ru
---

# Меня хорошо видно && слышно?
<!-- _class: second_page -->
![REC](https://raw.githubusercontent.com/dzolotov/otus/main/theme/rec.png)
## Проверить, идет ли запись?
### Ставим “+”, если все хорошо “-”, если есть проблемы
![PLUS](https://raw.githubusercontent.com/dzolotov/otus/main/theme/plusminus.png)
 
---
<!-- _class: third_page -->
###### Тема вебинара
# {{topic}}
![photo]({{ lector.photo }})
## {{ lector.name }}

```
{{ lector.info }}
```
---
# Преподаватель

<!-- _class: page_about -->

![photo]({{ lector.photo }})
## {{ lector.name }}

{% for a in lector.about %}- {{ a }}
{% endfor %}

---
<!-- _class: page_rules -->
---
<!-- _class: page_route -->
# Маршрут вебинара

{% for a in toc %}- {{ a}}
{% endfor %}
---
# Цели вебинара
## После занятия вы сможете

{% for a in goals %}1. {{ a}}
{% endfor %}

---
# Смысл
## Зачем вам это уметь

{% for a in reasons %}1. {{ a}}
{% endfor %}
---
{% for a in content %}
    {% if a["section"] %}
<!-- _class: page_section -->
# {{ a["section"] }}
    {% elif a["page"] %}
# {{ a["page"] }}
{{ a["content"] }}
    {% elif a["withimage" ] %}
<!-- _class: page_withimage -->
# {{ a["withimage"] }}
{{ a["content" ]}}
![{{ a["alt"] }}]({{ a["src"] }})
    {% elif a["image"] %}
<!-- _class: page_image -->
# {{ a["image"] }}
![{{a["alt"]}}]({{a["src"]}})
    {% endif %}
---
{% endfor %}
<!-- _class: page_section -->
# Рефлексия

---
# Полезные материалы

{% for a in additional %}{% if a["link"] %}- [{{ a["text"] }}]({{ a["link"] }}){% elif a["text"] %}- {{ a["text"] }}{% else %}- {{ a }}{% endif %}
{% endfor %}
---
# Цели вебинара
## Проверка достижения целей
{% for a in goals %}1. {{ a}}
{% endfor %}

---
<!-- _class: page_reflexion -->

---
<!-- _class: next_webinar_page -->
# Следующий вебинар
![academy](https://raw.githubusercontent.com/dzolotov/otus/main/theme/academic.png)
### {{ next.date }}
## {{ next.topic }}
![check1](https://raw.githubusercontent.com/dzolotov/otus/main/theme/check.png)
![check2](https://raw.githubusercontent.com/dzolotov/otus/main/theme/check.png)
![redflag](https://raw.githubusercontent.com/dzolotov/otus/main/theme/redflag.png)
#### Ссылка на вебинар будет в ЛК за 15 минут
##### Материалы к занятию в ЛК - можно изучать
###### Обязательный материал обозначен красной лентой

---
<!-- _class: page_section -->
# Заполните, пожалуйста, опрос о занятии по ссылке в чате {{ feedback }}

---
<!-- _class: last_page -->
###### Спасибо за внимание!
# Приходите на следующие вебинары
![photo]({{ lector.photo }})
## {{ lector.name }}

```
{{ lector.info }}
```
