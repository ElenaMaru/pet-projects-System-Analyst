# Проект «Мини-приложение по продаже подарочных спа-боксов»

## 1. BRD (Business Requirements Document)

Файл: [`BRD (Business Requirements Document).docx`]([BRD (Business Requirements Document).docx](https://github.com/ElenaMaru/pet-projects-System-Analyst/blob/main/spa_box/file/BRD%20(Business%20Requirements%20Document).docx))

*Описывает цели проекта, целевую аудиторию и бизнес-ценность*

## 2. User story и use case

Файл: [`User Story & Use Cases.docx`]([User Story & Use Cases.docx](https://github.com/ElenaMaru/pet-projects-System-Analyst/blob/main/spa_box/file/User%20Story%20%26%20Use%20Cases.docx))


## 3. ER-модель базы данных

![ER-модель](https://github.com/ElenaMaru/pet-projects-System-Analyst/blob/main/spa_box/file/er-d.png)

*Отображает основные сущности: `Tariff`, `Rule`, `History` и связи между ними («один ко многим»). Сгенерировано в PlantUML.*

## 4. UML-диаграммы

![UML-диаграмма классов](uml_classes.png)

*Показывает структуру сервисного слоя приложения: классы `TariffService`, `RuleValidator`, `RateCalculator` и их методы.*

## 4. User story и use case

**User story:**

> «Как пользователь, я хочу получить актуальный тариф по своей подписке, чтобы узнать стоимость услуги заранее.»

**Use case:**

1. Пользователь отправляет запрос `GET /tariffs/{userId}`

2. Система проверяет права доступа

3. Система рассчитывает тариф и возвращает JSON с деталями

## 5. Техническое задание (SRS)

Файл: [`srs_dynamic_tariff.docx`](srs_dynamic_tariff.docx)

*Кратко описаны цель проекта, входные/выходные параметры API и критерии приёмки.*

> **Инструменты:** Jira, Confluence, PlantUML, Swagger/OpenAPI, PostgreSQL, Power BI
