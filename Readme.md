<h1 align="center">
  Привет, я Михаил
  <img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/>
</h1>

<h3 align="center">Java Backend Developer</h3>

<p align="center">
  Строю микросервисы на Spring Boot, деплою в Kubernetes, интегрирую через Kafka.<br/>
  Иногда пишу на Go — там где важна скорость.
</p>

<p align="center">
  <a href="https://bolohonovma.online" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-bolohonovma.online-667eea?style=for-the-badge&logo=google-chrome&logoColor=white"/>
  </a>
  <a href="https://t.me/Bolohonov" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-@Bolohonov-0088cc?style=for-the-badge&logo=telegram&logoColor=white"/>
  </a>
</p>

---

## 🛠 Стек

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

---

## 🚀 Проекты

### 🏪 [Cloud CRM](https://github.com/Bolohonov/crm-app) + [E-commerce Platform](https://github.com/Bolohonov/shop-project)
> Два связанных сервиса с интеграцией через Apache Kafka

**CRM** — микросервисная архитектура, мультитенантная изоляция данных (PostgreSQL), real-time уведомления через SSE, Kafka producer с Transactional Outbox Pattern, drag-and-drop канбан, экспорт Excel/CSV.

**E-commerce** — Интернет-магазин ИТ-услуг с Kafka-интеграцией, корзиной, балансом и SSE уведомлениями о статусе заказов из CRM.

`Java 21` `Spring Boot 3` `Vue 3` `Kafka` `PostgreSQL` `Docker` `k3s`

---

### 💬 [Real-time Chat](https://github.com/Bolohonov/chat-app)

WebSocket приложение для обмена сообщениями в реальном времени. Go-сервис в роли WebSocket-шлюза, Spring Boot для бизнес-логики и авторизации, Vue 3 фронтенд, деплой в k3s через Traefik Ingress.

`Java` `Spring Boot` `Go` `Vue.js` `PostgreSQL` `Redis` `Kubernetes` `Docker`

---

### 🏦 [Bank Microservices](https://github.com/Bolohonov/bank)

8 микросервисов: переводы, конвертация валют, история операций, мониторинг. Полный observability-стек: Prometheus + Grafana + ELK. CI/CD через Jenkins, деплой через Helm.

`Java 21` `Spring Boot` `Kafka` `PostgreSQL` `Kubernetes` `Helm` `Jenkins` `Grafana` `Prometheus` `ELK`

---

### 📅 [EventHub](https://github.com/Bolohonov/ewm)

Сервис публикации событий и поиска участников. Два микросервиса с раздельными БД, Vue.js фронтенд, JPA Criteria API для гибкой фильтрации, Docker Compose для развёртывания.

`Java` `Spring Boot` `Vue.js` `PostgreSQL` `Docker`

---

### 🔔 [Notification Service](https://github.com/Bolohonov/NotificationService)

API Gateway + Authorization Server с JWT, Spring Eureka для service discovery, защита от DDoS через Redis rate limiting.

`Java` `Spring Cloud` `Spring Eureka` `Redis` `Docker`

---

### ✅ [Task Manager Service](https://github.com/Bolohonov/tms)

Микросервис с JWT-аутентификацией и Swagger API документацией.

`Java` `Spring Boot` `PostgreSQL` `Docker`

---

### 🏪 [Product Storefront](https://github.com/Bolohonov/shop)

Реактивный интернет-магазин на Spring WebFlux: витрина товаров с поиском и пагинацией, корзина, история заказов и эмуляция оформления покупки

`Java` `Spring WebFlux` `PostgreSQL R2DBC`

---

## 📊 Статистика

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bolohonov&layout=compact&theme=tokyonight&hide_border=true"/>
</p>
