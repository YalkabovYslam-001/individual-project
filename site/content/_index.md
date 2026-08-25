---
title: ""
summary: ""
date: 2025-01-01
type: landing

sections:
  # ==========================================
  # 3.2. ГЛАВНЫЙ ЭКРАН
  # ==========================================

  - block: hero
    content:
      title: "Ялкабов Ислам"
      text: |
        ## Студент • Разработчик • IT

        Фундаментальная информатика и информационные технологии

        Изучаю программирование, Linux, веб-разработку
        и современные технологии.

      primary_action:
        text: "Обо мне"
        url: "#about"

      secondary_action:
        text: "GitHub"
        url: "https://github.com/YalkabovYslam-001"

    design:
      spacing:
        padding: ["6rem", "0", "6rem", "0"]

      columns: "2"

      background:
        gradient_mesh:
          enable: true

  # ==========================================
  # 3.3. ПРОФИЛЬ
  # ==========================================

  - block: markdown
    id: profile

    content:
      title: ""

      text: |

        <div style="display:flex; flex-wrap:wrap; align-items:center; gap:3rem; padding:2rem 0;">

        <div style="flex:0 0 220px; text-align:center;">

        <img src="/individual-project/images/avatar.jpg"
             alt="Ялкабов Ислам"
             style="width:220px; height:220px; object-fit:cover; border-radius:50%; box-shadow:0 10px 30px rgba(0,0,0,0.15);">

        </div>

        <div style="flex:1; min-width:280px;">

        <h2>Привет! 👋</h2>

        <p style="font-size:1.1rem;">
        Меня зовут <strong>Ялкабов Ислам</strong>.
        Я студент Российского университета дружбы народов,
        изучающий информационные технологии и разработку
        программного обеспечения.
        </p>

        <p>
        Мне интересны программирование, веб-разработка,
        Linux и цифровой дизайн.
        </p>

        <p>
        Этот сайт является моим индивидуальным проектом,
        где я собираю свои работы, знания и результаты обучения.
        </p>

        </div>

        </div>

  # ==========================================
  # 3.4. ОБО МНЕ
  # ==========================================

  - block: markdown
    id: about

    content:
      title: "Обо мне"

      text: |

        ### Ялкабов Ислам

        Я студент **Российского университета дружбы народов (РУДН)**.

        Изучаю информационные технологии и разработку программного обеспечения.

        Интересуюсь веб-разработкой, Linux и современными технологиями программирования. Также занимаюсь цифровым дизайном.

        В рамках обучения изучаю программирование, операционные системы, веб-технологии, системы контроля версий и современные инструменты разработки.

  # ==========================================
  # 3.5. ОБРАЗОВАНИЕ
  # ==========================================

  - block: markdown
    id: education

    content:
      title: "Образование"

      text: |

        <div style="padding:2rem; border-radius:20px; border:1px solid rgba(128,128,128,.2);">

        <h2>🎓 Российский университет дружбы народов</h2>

        <p style="font-size:1.15rem;">
        <strong>Фундаментальная информатика и информационные технологии</strong>
        </p>

        <p>
        Группа: <strong>НКАБД-06-25</strong>
        </p>

        <p>
        Год обучения: <strong>2025</strong>
        </p>

        </div>

  # ==========================================
  # 3.6. МОИ ИНТЕРЕСЫ
  # ==========================================

  - block: markdown
    id: interests

    content:
      title: "Мои интересы"

      text: |

        <div style="display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:1.2rem;">

        <div style="padding:1.5rem; border-radius:18px; border:1px solid rgba(128,128,128,.2);">
        <h3>🐧 Linux</h3>
        <p>Операционные системы, терминал, Bash и системные инструменты.</p>
        </div>

        <div style="padding:1.5rem; border-radius:18px; border:1px solid rgba(128,128,128,.2);">
        <h3>💻 C++</h3>
        <p>Программирование, алгоритмы, структуры данных и объектно-ориентированный подход.</p>
        </div>

        <div style="padding:1.5rem; border-radius:18px; border:1px solid rgba(128,128,128,.2);">
        <h3>🐍 Python</h3>
        <p>Разработка программ, автоматизация и изучение современных технологий.</p>
        </div>

        <div style="padding:1.5rem; border-radius:18px; border:1px solid rgba(128,128,128,.2);">
        <h3>🌐 Web</h3>
        <p>HTML, CSS, JavaScript и создание современных веб-сайтов.</p>
        </div>

        <div style="padding:1.5rem; border-radius:18px; border:1px solid rgba(128,128,128,.2);">
        <h3>🎨 Дизайн</h3>
        <p>Цифровой дизайн, визуальное оформление и работа с интерфейсами.</p>
        </div>

        </div>

  # ==========================================
  # 3.7. ИНДИВИДУАЛЬНЫЙ ПРОЕКТ
  # ==========================================

  - block: markdown
    id: projects

    content:
      title: "Индивидуальный проект"

      text: |

        Этот сайт является частью моего индивидуального проекта.

        В процессе разработки я изучаю и применяю:

        - Hugo;
        - HugoBlox;
        - Git;
        - GitHub;
        - GitHub Actions;
        - GitHub Pages;
        - Markdown;
        - HTML и CSS;
        - инструменты веб-разработки.

        Цель проекта — создать собственный современный персональный сайт и разместить его в интернете с использованием GitHub Pages.

  # ==========================================
  # 3.8. ИТОГИ НЕДЕЛИ
  # ==========================================

  - block: markdown
    id: week

    content:
      title: "Итоги недели"

      text: |

        ### Что было сделано

        На этой неделе были выполнены следующие задачи:

        - установка Hugo;
        - установка необходимых инструментов;
        - настройка Hugo Academic;
        - создание GitHub-репозитория;
        - настройка Git;
        - настройка GitHub Actions;
        - публикация сайта через GitHub Pages;
        - первые результаты проекта.

        В результате был создан рабочий персональный сайт, который собирается с помощью Hugo и публикуется через GitHub Pages.

  # ==========================================
  # 3.9. GITHUB
  # ==========================================

  - block: cta-card
    id: github

    content:
      title: "Мой GitHub"

      text: |
        Исходный код проекта и другие учебные работы доступны на GitHub.

      button:
        text: "Перейти на GitHub"
        url: "https://github.com/YalkabovYslam-001"

    design:
      card:
        css_class: "bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl"
        css_style:
          ""

          # =========================
  # ЭТАПЫ ПРОЕКТА
  # =========================

  - block: markdown
    id: stages
    content:
      title: "🚀 Этапы индивидуального проекта"
      text: |
        <div style="display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:1.5rem;">

        <div style="padding:1.8rem; border-radius:20px; border:1px solid rgba(128,128,128,.2);">
        <h3>01. Подготовка</h3>
        <p>Установка Hugo, Git, Visual Studio Code и необходимых инструментов для разработки сайта.</p>
        </div>

        <div style="padding:1.8rem; border-radius:20px; border:1px solid rgba(128,128,128,.2);">
        <h3>02. Создание сайта</h3>
        <p>Создание проекта на основе HugoBlox и первоначальная настройка структуры сайта.</p>
        </div>

        <div style="padding:1.8rem; border-radius:20px; border:1px solid rgba(128,128,128,.2);">
        <h3>03. Персонализация</h3>
        <p>Добавление имени, фотографии, биографии, образования и интересов.</p>
        </div>

        <div style="padding:1.8rem; border-radius:20px; border:1px solid rgba(128,128,128,.2);">
        <h3>04. Git и GitHub</h3>
        <p>Настройка Git, создание репозитория и загрузка проекта на GitHub.</p>
        </div>

        <div style="padding:1.8rem; border-radius:20px; border:1px solid rgba(128,128,128,.2);">
        <h3>05. GitHub Actions</h3>
        <p>Настройка автоматической сборки и публикации проекта.</p>
        </div>

        <div style="padding:1.8rem; border-radius:20px; border:1px solid rgba(128,128,128,.2);">
        <h3>06. GitHub Pages</h3>
        <p>Публикация готового сайта в интернете.</p>
        </div>

        <div style="padding:1.8rem; border-radius:20px; border:1px solid rgba(128,128,128,.2);">
        <h3>07. Документация</h3>
        <p>Подготовка отчёта, презентации, скриншотов и видеодемонстрации проекта.</p>
        </div>

        </div>
---
