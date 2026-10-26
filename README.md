# Дмитрий Вязовский — Go Backend Developer

Разрабатываю backend на Go. Есть опыт доработки Go-микросервисов и создания собственных backend-проектов. Работал с REST API, gRPC, Protocol Buffers, PostgreSQL и SQLite; реализовывал межсервисное взаимодействие, обработку ошибок, логирование, метрики и тесты бизнес-логики.

Ищу возможность развиваться в backend-команде, участвовать в разработке сервисов и последовательно повышать качество кода.

## 🛠 Технологии и инструменты

- **Язык:** Go
- **Backend и API:** REST API, gRPC, Protocol Buffers, WebSocket, микросервисы
- **Базы данных:** PostgreSQL, SQLite, SQL
- **Конкурентность:** goroutines, channels
- **Тестирование и наблюдаемость:** тесты бизнес-логики, Prometheus, Zap
- **Инструменты:** Git, GitHub, Docker, Linux, Bash, YAML
- **Дополнительно:** основы GitHub Actions, Groovy, JavaScript

## 🚀 Проекты

### [Market2 — биржевая система на Go и gRPC](https://github.com/dim-pep/Market2)

Backend-проект с отдельными сервисами для работы с заказами и торговыми рынками.

- Реализовал взаимодействие `OrderService` и `SpotInstrumentService`.
- Добавил проверку доступности торгового рынка через gRPC перед созданием заказа.
- Описал контракты взаимодействия с помощью Protocol Buffers.
- Реализовал преобразование доменных моделей и обработку ошибок через gRPC status codes.
- Настроил логирование с помощью Zap.
- Реализовал серверные interceptors для восстановления после паник и сбора метрик Prometheus.
- Написал тесты основной бизнес-логики и консольный gRPC-клиент.

**Стек:** Go, gRPC, Protocol Buffers, PostgreSQL, Prometheus, Zap, Docker.

### [Планировщик задач](https://github.com/dim-pep/go-final-project)

Backend-приложение для управления задачами с гибкими правилами повторения.

- Поддерживает повторение каждый год, каждые N дней, в выбранные дни недели и месяца.
- Предоставляет REST API для работы с задачами.
- Использует SQLite для хранения данных.
- Поддерживает запуск в Docker.

**Стек:** Go, REST API, SQLite, SQL, Docker.

### [Go WebSocket Chat](https://github.com/dim-pep/WebSocket-Chat)

Чат в реальном времени на Go с использованием WebSocket.

- Реализовал обмен сообщениями между подключёнными клиентами.
- Использовал goroutines и channels для обработки подключений.
- Разделил серверную логику на `Hub`, `Client` и `Handler`.
- Добавил уведомления о подключении и отключении участников.

**Стек:** Go, `net/http`, Gorilla WebSocket, goroutines, channels.

### [Фитнес-трекер](https://github.com/dim-pep/two_project)

Приложение на Go для учёта тренировок и расчёта показателей физической активности.

- Реализовал модели для бега, ходьбы и плавания.
- Использовал встраивание структур, методы и интерфейс `CaloriesCalculator`.
- Реализовал расчёт скорости и калорий для разных типов активности.
- Использовал `time.Duration` для работы с длительностью тренировок.

**Стек:** Go, структуры, интерфейсы, методы, `time.Duration`.

## 📫 Контакты

- **Telegram:** [@dim_pep](https://t.me/dim_pep) — предпочтительный способ связи
- **Email:** [pepidastr@yandex.ru](mailto:pepidastr@yandex.ru)
- **GitHub:** [dim-pep](https://github.com/dim-pep)

## 🎮 Хобби

В свободное время разрабатываю небольшие игры на Godot и Ren'Py.
