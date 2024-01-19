<h1 align="center">Привет, я Михаил.<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Программирую на <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-bage&logo=java&logoColor=white" height="24"/>. </h3>

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=bolohonov&layout=compact)

<h3 align="center"> Некоторые из моих проектов: </h3>  

##### Сервис по публикации событий и поиска компании для участия в этих событиях
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=bolohonov&repo=java-explore-with-me)](https://github.com/Bolohonov/java-explore-with-me)  
Реализовано два микросервиса, каждый из которых работает со своей БД - PostgreSQL. Предусмотрена возможность развертывания 4-х контейнеров Docker: 2 для микросервисов и 2 для БД. Также использовал `CriteriaApi`.

##### UI для сервиса публикации событий (в разработке).
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=bolohonov&repo=ewm)](https://github.com/Bolohonov/ewm)  
UI для сервиса публикации событий. На данный момент доступны функции: Авторизация, просмотр списка событий, информации о событии, создание нового события.
Технологии:
Frontend: Vue.js, WaveUI (UI framework)
Backend: Spring Boot, PostgreSQL, JPA + Hibernate, JPA Criteria API

##### Простой task-менеджер с JWT-аутентификацией
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=bolohonov&repo=tms)](https://github.com/Bolohonov/tms)

Микросервис на SpringBoot с БД - PostgreSQL, Swagger API документация. Настроена контейнеризация docker.   

##### Сервис для отправки уведомлений
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=bolohonov&repo=NotificationService)](https://github.com/Bolohonov/NotificationService)   
Микросервисная архитектура. Запросы поступают на API Gateway и переадресуются на Authorization server, который выдает  
и проверяет токены JWT. На сервере ресурсов также настроена проверка авторизации. Все микросервисы регистрируются  
в Spring Eureka. Реализована простая защита от DDoS-атак на основе установленных лимитов подключений для Redis.  
Реализована возможность развертывания микросервисов в контейнерах docker.

##### Сервис для добавления, оценки и рекомендации фильмов на основе общих предпочтений.
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=bolohonov&repo=filmorate)](https://github.com/Bolohonov/filmorate)

Основа проекта на `Spring Boot и JdbcTemplate`. Реализована система поиска, лайков, отзывов, добавления в друзья, алгоритм рекомендаций на основе предпочтений, лента событий.

##### Сервис для заказа еды.
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=bolohonov&repo=FoodOrderingApp)](https://github.com/Bolohonov/FoodOrderingApp)  
Сервис использует брокер сообщений Kafka, настроено развертывание docker-контейнеров.