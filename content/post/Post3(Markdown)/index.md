---
title: Язык разметки Markdown
subtitle: Этот пост о том, как начать работу с Git.
# Summary for listings and search engines
summary: Этот пост о том, как начать работу с Git. Вначале изучим основы систем контроля версий. 
# Link this post with a project
projects: []

# Date published
date: '2024-04-04'

# Date updated
lastmod: '2024-04-04'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  
tags:
  - Academic

categories:
  - Education
 
---


Markdown — это простой язык разметки, используемый для создания форматированного текста (например, HTML) с помощью текстового редактора. Он позволяет добавлять к тексту базовое форматирование, используя символы, известные и доступные на всех клавиатурах. Размер шрифта, цвет и другие расширенные параметры недоступны в Markdown.

Вы можете встретить Markdown в .md или .markdown файлах.

```

Такие файлы содержат базовые элементы, которые можно найти почти в любом README.md:

    заголовок первого уровня для названия;
    выделение жирным шрифтом важных частей в описании;
    ссылка с понятным текстом;
    
Несмотря на то, что Markdown достаточно удобно читать в исходном виде, его часто переводят в HTML. 


#Синтаксис

Параграф — это одна или несколько подряд идущих строчек текста, отделённых одной или несколькими пустыми строчками. Если строка содержит только пробелы или табы, то она всё равно считается пустой.

Подряд идущие строчки будут склеены в одну, если не добавить жёсткий перенос. Существует несколько способов, как это можно сделать:

    добавить два (или больше) пробелов в конце строки <пробел><пробел>;
    добавить обратную косую черту в конце строки \;
    добавить HTML-тег переноса строки <br>.
    
Markdown предлагает два стиля написания заголовков: через решётки и через подчёркивания (====). Можно использовать до шести уровней заголовков, но подчёркивания позволяют создавать только первые два.
    
Для того чтобы выделить заголовок, необходимо поставить от 1 до 6 решёток и пробел в самом начале строки. Уровень заголовка зависит только от количества решёток.

«Подчёркивание» параграфа знаками равно или дефисами делает его заголовком первого или второго уровня соответственно. Уровень заголовка зависит только от типа «чёрточек», их количество значения не имеет.

Между текстом и «подчёркиванием» не должно быть пустых строк.

Для создания маркированных (ненумерованных) списков перед каждым пунктом нужно поставить минус, плюс или звёздочку. Маркер и текст пункта необходимо разделять пробелом.



```
- Помидор
- Огурец

+ Бублик
+ Ватрушка

* Молоко
* Кефир
```

- Помидор
- Огурец

+ Бублик
+ Ватрушка

* Молоко
* Кефир

