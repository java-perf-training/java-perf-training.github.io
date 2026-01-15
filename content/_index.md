---
title: 'Тренинги'
date: 2026-01-10
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Оптимизация производительности приложений на JVM
      text: Тренинги для тех, кто в ответе за свой код на production🧑🏼‍💻
      primary_action:
        text: Записаться
        url: https://forms.yandex.ru/u/66b620c5f47e7313456e26e4/templates/
        icon: rocket-launch
      secondary_action:
        text: Посмотреть описание
        url: '#plan'
      announcement:
        text: "Открыта запись на занятия в марте"
        link:
          text: "Подробнее"
          url: "https://java-rock-stars.timepad.ru/event/3654125/"
    design:
    #   spacing:
    #     padding: [0, 0, 0, 0]
    #     margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: grafana-cropped-b-01.png
          filters:
            brightness: 0.1
          size: cover
          position: center
          parallax: true

  # - block: stats
  #   content:
  #     items:
  #       - statistic: "≈90М ₽"
  #         description: |
  #           Потеряли ИТ-компании в РФ
  #           за 2024 г. на&nbsp;программных сбоях и ошибках
  #       - statistic: "40%"
  #         description: |
  #           Простоев онлайн-сервисов
  #           случаются из-за проблем производительности
  #       - statistic: "10 часов"
  #         description: |
  #           Среднее время исправления performance-проблемы в&nbsp;JVM
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]

  # - block: markdown
  #   content:
  #     title: "Эти риски можно снизить📉"
  #     subtitle: "Даем разработчикам необходимые знания и навыки"
  #     text: |
  #       Если **заранее** получить необходимые знания и навыки,
  #       чтобы при появлении проблемы **сразу** приступать к анализу и исправлению,
  #       а не перебирать варианты во&nbsp;время пожара.
  #   design:
  #     columns: "1"
  #     background:
  #       color: "white"

  - block: team-showcase
    id: tutors
    content:
      title: Кто мы
      subtitle: Разработчики с большим боевым опытом
      text: Мы строили успешные высоконагруженные системы и готовы помочь в этом вам
      user_groups:
        - Tutors
      sort_by: 'Params.last_name'
      sort_ascending: false
      # cta:
      #   text: Join Our Team
      #   url: /opportunities
      #   icon: user-plus
    design:
      show_role: true
      show_organizations: false
      show_interests: true
      show_social: true
      # Section background color (CSS class)
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: features
    id: features
    content:
      title: Что дают тренинги?
      text: Только самые необходимые навыки (и немножко больше)
      items:
        - name: Определение первопричин
          icon: magnifying-glass
          description: Научитесь точно находить первопричину проблемы, даже если у нее множество симптомов.
        - name: Повышение отзывчивости
          icon: bolt
          description: Освоите приемы ускорения приложений без&nbsp;существенных доработок в прикладном коде.
        - name: Превентивная диагностика
          icon: sparkles
          description: Узнаете, по каким признакам можно выявить потенциальные проблемы до их проявления.
        - name: Лучшие практики
          icon: code-bracket
          description: Получите множество советов по оптимизации производительности приложений на JVM.
        - name: Признание коллег
          icon: star
          description: Станете настоящим экспертом в области производительности своего проекта. 
        - name: Грамотная архитектура
          icon: rectangle-group
          description: Сможете без труда проектировать и&nbsp;развивать высоконагруженные системы.

  - block: cta-image-paragraph
    id: plan
    content:
      items:
        - title: Базовые техники профилирования
          text: Основополагающий тренинг для начинающих
          feature_icon: check
          features:
            - "Методы профилирования"
            - "Профайлеры их особенности"
            - "Условия и советы по применению"
          # Upload image to `assets/media/` and reference the filename here
          image: base-profiling-techniques.png
          button:
            text: Записаться
            url: https://hugoblox.com/templates/
        - title: Анализ памяти в куче
          text: Тренинг по разбору и предотвращению OutOfMemory
          feature_icon: bolt
          features:
            - "Основы устройства кучи и работы GC"
            - "Методы получения и анализа дампов памяти"
            - "Способы обнаружения и устранения утечек"
          # Upload image to `assets/media/` and reference the filename here
          image: eclipse-mat.png
          button:
            text: Записаться
            url: https://discord.gg/z8wNYzb
        - title: Мониторинг JVM
          text: Тренинг по сбору и анализу метрик ==уже 17.03.26==
          feature_icon: check
          features:
            - "Источники полезных метрик: от JMX до ОС"
            - "Инструменты мониторинга: от консоли до Grafana"
            - "Лучшие практики по работе с метриками"
          image: jvm-monitoring.png
          button:
            text: Записаться
            url: https://discord.gg/z8wNYzb

    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"

  - block: testimonials
    id: feedback
    content:
      title: "Отзывы участников"
      text: ""
      items:
        - name: "Анна С."
          role: "Backend-разработчик, Java/Kotlin"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: | 
            Побывала на всех трёх занятиях в прошлом году. 
            Курс оказался очень полезным, особенно с точки зрения практики: 
            что, где смотреть? что вообще может дать тот или иной инструмент
        - name: "Рустам К."
          role: "Java-разработчик"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: | 
            Проходил осенью тренинг по потокам и памяти. Очень доступная подача материала, порадовало большое количество живых примеров в рантайме. Для меня это был первый структурированный опыт погружения в тему, позже помогло при решении боевой задачи. Рекомендую!
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]

  - block: cta-card
    content:
      title: Сделайте свой production быстрым! 🚀
      text: Пройдите тренинги сегодня, чтобы завтра быть готовыми ко всему.
      button:
        text: Записаться
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
---
