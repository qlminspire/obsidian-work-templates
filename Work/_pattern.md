---
Название: <% tp.file.title.replace('@', '').split(" - ")[1] %>
Категория:
  - "[[Паттерны проектирования]]"
Ссылка: 
tags:
  - инструмент/паттерн
aliases:
  - <% tp.file.title.replace('@', '').split(" - ")[1] %>
---

<% await tp.file.move("/02-Permanent/Patterns/" + tp.file.title) %>