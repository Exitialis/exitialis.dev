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

  # Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Python & PyTorch
        description: ''
        percent: 95
        icon: code-bracket
      - name: Machine Learning
        description: ''
        percent: 100
        icon: chart-bar
      - name: Cloud Computing (AWS/GCP)
        description: ''
        percent: 85
        icon: cloud
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Компьютерные игры
        description: ''
        percent: 80
        icon: bolt
      - name: Building Custom PCs
        description: ''
        percent: 90
        icon: cpu-chip
      - name: Sci-Fi Reading
        description: ''
        percent: 70
        icon: book-open

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
  - title: Best Paper Award
    url: https://neurips.cc/
    date: '2022-12-01'
    awarder: NeurIPS
    icon: hero/trophy
    summary: |
      Awarded for groundbreaking work on efficient training of large models.
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
