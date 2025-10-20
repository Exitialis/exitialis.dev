---
# Display name
title: Иван Нещадин

# Name pronunciation (optional)
name_pronunciation: ''

# Full name (for SEO)
first_name: Иван
last_name: Нещадин

# Pronouns (optional)
pronouns: 

# Status emoji
status:
  icon: 👨‍💻

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: TechLead @ Bridge/Arch

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Avito
    url: https://avito.ru/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:lpexitialis@gmail.com'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/exitialis
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/alexjohnsonai/
  - icon: brands/telegram
    url: https://t.me/exitialis


interests:
  - Backend
  - Team Management
  - Large Language Models
  - Reinforcement Learning

education:
  - area: BS Information Systems and Technology
    institution: Stankin University
    date_start: 2014-09-01
    date_end: 2018-06-30
  
work:
  - position: TechLead 
    company_name: Avito
    company_url: 'https://avito.ru/'
    company_logo: ''
    date_start: 2024-06-01
    summary: |
      TechLead команды Bridge. Команда отвечает за надёжность всех сервисов в Авито, улучшает надёжность, помогает решать критичный архитектурный долг и критичные проблемы с техническим долгом.
      С сентября 2025 также возглавляю команду Arch, которая отвечает за архитектуру всех сервисов в Авито в целом.
  - position: Senior Backend Developer
    company_name: Avito
    company_url: 'https://avito.ru/'
    company_logo: ''
    date_start: 2020-03-20
    date_end: 2024-06-01
    summary: |
      Senior backend developer. Работал в команде, которая распиливала большой PHP монолит на Symfony на микросервисы.
      Лично распилил несколько крупных кусков суммарно с 500k rpm на несколько сервисов. Овнил функционал сохранённых поисков.
      Разработал систему для оценки качества архитектуры и поиска архитектурных проблем arch-rater.
  - position: Senior Backend Developer
    company_name: Carprice
    company_url: 'https://carprice.ru/'
    company_logo: ''
    date_start: 2019-03-10
    date_end: 2020-03-01
    summary: |
      Senior backend developer. Помогал распиливать большой Bitrix24 монолит на микросервисы с использованием Laravel и Go.
      Реализовал backend сервиса, который общается с BPM и позволяет работать с внутренним документооборотом, предоставляя простой интерфейс для пользоваталей.
      Интегрировал быструю оплату по номеру телефона для клиентов Тинькофф банка. На тот момент это было что-то вроде СБП, при помощи которого дилеры могли проводить платежи с компанией Carprice. Это сократило время получения платежа на несколько дней и ускорило сделки с автомобилями.
  - position: Middle Fullstack Developer
    company_name: Onlinesim
    company_url: 'https://onlinesim.ru/'
    company_logo: ''
    date_start: 2017-11-01
    date_end: 2019-03-10
    summary: |
      Middle developer. Разработал отдельный портал whitenum для определения использования одноразовых телефонов при регистрации на популярных ресурсов, с целью предоставления API для крупных компаний, при помощи которого они смогли бы проверять номер пользователя при регистрации. Использовал Laravel + Vue.js
      Разработал приложение на Electron, которое взаимодействует с внешним оборудованием (Sim-модемами) и общается по последовательному Com порту.
      Перевёл архитектуру сайта на несколько микросервисов, чтобы можно было отдельить бизнес логику и обеспечить отдельный деплой.
      Настроил автоматизированный пайплайн CI/CD. Ранее для деплоя использовался php скрипт на deployer, который просто скачивал код из репозитория и обновлял его на сервере.
  - position: Junior Fullstack Developer
    company_name: Simex Inc.
    company_url: 'https://simex.global/'
    company_logo: ''
    date_start: 2016-12-01
    date_end: 2015-01-20
    summary: |
      Junior Fullstack Developer. Работал над улучшением сайта, работающего под фреймворком Laravel.
      В качестве фронтенда использовался Vue.js. Работал над сайтом краудинвестинговой платформы.
      **Одно из ключевых достижений**: Разработал админ панель для переводчиков, при помощи которой они смогли перевести весь сайт на другие языки. При помощи регулярных выражений и консольных команд достал из всего кода захардкоженный текст, заменил его на получение значения по ключу из i18n и сохранил все языковые настройки в БД.

skills:
  - name: Технические скиллы
    items:
      - name: PHP
        description: 'Начинал с PHP 5.0, знаю все актуальные изменения. Работал с Birtix24, Wordpress, Laravel, Symfony и многим другим.'
        percent: 100
        icon: code-bracket
      - name: Go
        description: 'Мой основной стек на текущий момент. Знаю все тонкости, умею тюнить GC, профилировать приложения и разбираться в сложных проблемах.'
        percent: 100
        icon: code-bracket
      - name: Javascript / Vue.js
        description: 'До 2021 года имел очень актуальный опыт работы с Vue.js, знал все тонкости. Сейчас уже чуть подзабылось, из-за того, что неиспользую.'
        percent: 80
        icon: code-bracket
      - name: Python / ML
        description: 'Работа с базовыми ML моделями + сетап RAG LLM системы с векторной БД.'
        percent: 80
        icon: code-bracket
      - name: Docker/Kubernetes
        description: 'Умение полностью с нуля написать нужный Dockerfile, управлять kubernetes из kubectl и чинить кластеры в проде.'
        percent: 100
        icon: cloud
      - name: Linux / Terminal / Bash
        description: 'Умение использовать terminal и знание стандартных и не только команд. Умение настраивать сервера.'
        percent: 90
        icon: command-line

  - name: Хобби
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Компьютерные игры
        description: ''
        icon: bolt
      - name: Работа с железом
        description: ''
        icon: computer-desktop
      - name: Путешествия
        description: ''
        icon: paper-airplane
      - name: Электроника
        description: ''
        icon: cpu-chip
      - name: 3D печать
        description: ''
        icon: printer
      - name: Строительство / работа с деревом
        description: ''
        icon: wrench-screwdriver
      - name: Умный дом
        description: ''
        icon: home-modern



languages:
  - name: Russian
    percent: 100
  - name: English
    percent: 90

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Топ-10 доклад на Highload 2024
    url: https://highload.ru/
    date: '2024-12-01'
    awarder: Highload
    icon: hero/trophy
    summary: |
      Награда за доклад, вошедший в топ-10 лучших докладов на highload по контенту и подаче.
  - title: AI Innovation Grant
    url: https://www.nsf.gov/
    date: '2021-06-15'
    awarder: National Science Foundation
    icon: hero/currency-dollar
    summary: |
      $500,000 grant for research in ethical AI development.
  - title: Outstanding PhD Thesis
    url: https://www.stanford.edu/
    date: '2019-06-30'
    awarder: Stanford University
    icon: hero/academic-cap
    summary: |
      Recognized for contributions to scaling laws in deep learning.
---

Иван Нещадин - TechLead нескольких ключевых команд в Авито, которые отвечают за работу платформы, на которой строится сайт Авито, в частности за надёжность и архитектурные решения всего Авито. Более чем 10-ти летний опыт работы в разных IT компаниях, от небольших до больших. IT-энтузиаст, увлекаюсь инженерией, 3Д-печатью, электроникой. Веду блог про IT и инженерию, рассказываю про управление командами разработчиков.
