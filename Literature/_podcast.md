---
Название: <% tp.file.title.split(" - ")[0] %>
Автор:
  - '[[@<% tp.file.title.split(" - ")[1] %>]]'
Начало: <% tp.date.now("YYYY-MM-DD") %>
Завершение: 
Рейтинг: 
Категория:
  - "[[Работа]]"
Ссылка: 
tags:
  - источник/подкаст
  - статус/в_планах
---

<% await tp.file.move("/01-Literature/Podcasts/" + tp.file.title) %>
