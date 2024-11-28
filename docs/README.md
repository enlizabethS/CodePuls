# CodePuls (At the development stage)

## Project Overview
CodePuls is a multifunctional news website designed for technical specialists, programmers, and web designers. The site should support various technical fields and offer users functionalities like registration, article submission, commenting, keyword search, and reactions to articles. The structure of the website should include the main page, "News," "Categories," "Create News," "Registration," "Login," "Top Articles," and "Leaderboard."

## Key Features
- Article reactions (thumbs up and thumbs down)
- Comments
- User registration
- User login
- Article submission
- Keyword and article search
- Article ranking

## Content Topics
The content should cover all technical fields related to programming, web design, and related areas. Categories should be flexible and configurable.

## Design
- **Website Name**: CodePuls
- **Color Scheme**: Deep blue, black, dark gray with bright accents (neon blue, turquoise, or green)
- **Fonts**: Modern and minimalist (Roboto, Open Sans)
- **Interface**: Clean and functional with news cards featuring images, titles, short descriptions, and a "Read More" button.
- **Sidebar**: Popular topics and filters
- **Animations**: Smooth element appearance on scroll, button highlighting, card enlargement on hover, parallax effect for background
- **Main Page**: News feed, tag cloud, and popular articles
- **Create News Page**: Text fields, image upload functionality, live preview

## Architecture
The project follows a microservices architecture:
- **News Service**: Manages articles (CRUD operations, image handling, category management)
- **User Service**: User registration, authentication, and authorization (OAuth)
- **Comment Service**: Creation, moderation, and display of comments
- **Analytics Service**: Collects data on article popularity and user activity
- **Media Service**: Image processing and storage

## Security
- Basic security measures: SSL certificates, OAuth authentication (Google, GitHub), protection against SQL injections and XSS attacks

## Additional Requirements
- Scroll animations, image carousels in articles, pop-ups for comments and authentication
- SEO-friendly: Meta tags, header tags (h1-h6), alt descriptions for images, keywords
- Fully responsive design for mobile and tablet devices
- Multilingual support: English (primary) and Russian
- **Frontend**: Bootstrap or Tailwind CSS, animation library (AOS)
- **Backend**: Lombok, Hibernate, Spring Framework
- **Unit Tests**
- **Documentation**: README.md, architecture description, API endpoints
- **Performance Optimization**: Fast page load, data caching, image compression
- **CI/CD**: GitHub Actions or Jenkins for automatic deployment
- **Error Logging**: Logback
- **Monitoring**: Spring Boot Actuator
- **Horizontal Scalability**: Load balancing between microservices, database scaling
- **Social Media API Integration**: For authentication and content sharing
- **GDPR Compliance**: Privacy policy, data usage consent

---

# CodePuls (на стадии разработки)

## Общее описание
CodePuls — это многофункциональный новостной сайт, предназначенный для технических специалистов, программистов и веб-дизайнеров. Сайт должен поддерживать различные технические области и предоставлять пользователям функции регистрации, добавления новостей, комментирования, поиска по ключевым словам и реакций на статьи. Структура сайта включает главную страницу, разделы «Новости», «Категории», «Создать новость», «Регистрация», «Вход», «ТОП лучших статей» и «Таблица рейтинга».

## Основные функции
- Реакции на статьи (палец вверх и вниз)
- Комментарии
- Регистрация пользователя
- Вход в личный кабинет пользователя
- Добавление новостей
- Поиск по ключевым словам и новостям
- Рейтинг статей

## Тематика контента
Контент должен охватывать все технические направления, связанные с программированием, веб-дизайном и смежными областями. Категории должны быть гибко настраиваемыми.

## Дизайн
- **Название сайта**: CodePuls
- **Цветовая схема**: глубокий синий, черный, темно-серый с яркими акцентами (неоновый синий, бирюзовый или зеленый)
- **Шрифты**: современные и минималистичные (Roboto, Open Sans)
- **Интерфейс**: чистый и функциональный с карточками новостей, изображениями, заголовками, кратким описанием и кнопкой «Читать далее».
- **Боковая панель**: популярные темы и фильтры
- **Анимации**: плавное появление элементов при прокрутке, подсветка кнопок, увеличение карточек при наведении, эффект параллакса для фона
- **Главная страница**: лента новостей, облако тегов и популярные статьи
- **Страница создания новости**: поля для текста, загрузки изображений, живой предпросмотр

## Архитектура
Проект построен по микросервисной архитектуре:
- **Сервис новостей**: управление статьями (CRUD, обработка изображений, управление категориями)
- **Сервис пользователей**: регистрация, аутентификация, авторизация (OAuth)
- **Сервис комментариев**: создание, модерация и отображение комментариев
- **Сервис аналитики**: сбор данных о популярности статей и активности пользователей
- **Сервис мультимедиа**: обработка и хранение изображений

## Безопасность
- Основные меры безопасности: SSL-сертификаты, аутентификация через OAuth (Google, GitHub), защита от SQL-инъекций и XSS-атак

## Дополнительные требования
- Анимации при прокрутке, карусели изображений в статьях, всплывающие окна для комментариев и аутентификации
- SEO-оптимизация: метатеги, заголовки (h1-h6), alt-описания для изображений, ключевые слова
- Полностью адаптивный дизайн для мобильных устройств и планшетов
- Мультиязычная поддержка: английский (основной) и русский
- **Фронтенд**: Bootstrap или Tailwind CSS, библиотека для анимаций (AOS)
- **Бэкенд**: Lombok, Hibernate, Spring Framework
- **Юнит-тесты**
- **Документация**: README.md, описание архитектуры, API-эндпоинты
- **Оптимизация**: быстрая загрузка страниц, кэширование данных, сжатие изображений
- **CI/CD**: GitHub Actions или Jenkins для автоматического развертывания
- **Логгирование ошибок**: Logback
- **Мониторинг**: Spring Boot Actuator
- **Горизонтальное масштабирование**: разделение нагрузки между микросервисами, масштабирование базы данных
- **Интеграция с API социальных сетей**: для авторизации и публикации контента
- **Соответствие требованиям GDPR**: политика конфиденциальности, согласие на использование данных

