---
Название: <% tp.file.title.replace('@', '').split(" - ")[0] %>
Категория:
  - "[[Работа]]"
Ссылка: 
tags:
  - проект
aliases:
  - <% tp.file.title.replace('@', '').split(" - ")[0] %>
---

<% await tp.file.move("/03-Projects/" + tp.file.title) %>