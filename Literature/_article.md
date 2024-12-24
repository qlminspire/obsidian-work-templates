---
Название: <% tp.file.title.split(" - ")[0] %>
Автор:
  - '[[@<% tp.file.title.split(" - ")[1] %>]]'
Начало: <% tp.date.now("YYYY-MM-DD") %>
Завершение: <% tp.date.now("YYYY-MM-DD") %>
Рейтинг: 
Категория:
  - "[[Работа]]"
Ссылка: 
tags:
  - источник/статья
  - статус/в_планах
---

<% await tp.file.move("/01-Literature/Articles/" + tp.file.title) %>
