---
Название: <% tp.file.title.split(" - ")[0] %>
Автор:
  - '[[@<% tp.file.title.split(" - ")[1] %>]]'
Начало: <% tp.date.now("YYYY-MM-DD") %>
Завершение: <% tp.date.now("YYYY-MM-DD") %>
Рейтинг: 5
Категория:
  - "[[Работа]]"
Ссылка: 
tags:
  - источник/видео
  - статус/в_процессе
---

<% await tp.file.move("/01-Literature/Video/" + tp.file.title) %>
