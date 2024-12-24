---
Название: <% tp.file.title.split(" - ")[0] %>
Автор:
  - '[[@<% tp.file.title.split(" - ")[1] %>]]'
Начало: <% tp.date.now("YYYY-MM-DD") %>
Завершение:
Рейтинг: 
Категория:
  - "[[Работа]]"
Платформа: 
Ссылка: 
tags:
  - источник/курс
  - статус/в_планах
---

<% await tp.file.move("/01-Literature/Courses/" + tp.file.title) %>
