---
title: Как мы в Авито анализируем 5 миллионов трейсов и проводим арихтектурный надзор

event: Highload 2024
event_url: https://highload.ru/moscow/2024/abstracts/13640

location: Школа управления Сколково
address:
  street: Новая ул. 100 д. Сколково 
  city: Moscow
  region: Russia

summary: Рассказ про то, как в Авито анализируют существующую архитектуру и находят места для улучшения.
abstract: ''

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-12-03T13:00:00Z'
date_end: '2024-12-03T14:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-12-03T00:00:00Z'

authors:
  - admin

tags: []

featured: false

links:
  - type: slides
    url: https://docs.google.com/presentation/d/1LzookfjkIJsBVUjCIMeOx8YSzIvlBiLThUDsuXlE70M/edit?usp=sharing
  - type: video
    url: https://www.youtube.com/watch?v=02HLJES7_lA

slides: ""

projects: []
---

> [!NOTE]
> Слайды и видео выступления можно посмотреть по ссылкам в шапке страницы.

В Авито у нас несколько тысяч микросервисов, десятки команд разработки и единая платформа, на основе которой делаются все наши микросервисы. Из доклада вы узнаете, как наша команда ArchGovernance помогает разобраться во всём этом архитектурном хаосе и позволяет найти ошибки в архитектуре при помощи инструмента arch-rater.

Я расскажу:
* как мы обрабатываем 5 миллионов трейсов;
* как строим карту взаимодействия между нашими микросервисами и какие инструменты для этого используем;
* какие способы анализа этой карты мы используем, чтобы находить проблемы в архитектуре и повышать надёжность.
