# Проект «Мини-приложение по продаже подарочных спа-боксов»

## 1. BRD (Business Requirements Document)

Файл: [`BRD (Business Requirements Document).docx`](BRD (Business Requirements Document).docx)

*Описывает цели проекта, целевую аудиторию и бизнес-ценность*

## 2. ER-модель базы данных

![ER-модель таблиц тарификатора](er_model.png)

*Отображает основные сущности: `Tariff`, `Rule`, `History` и связи между ними («один ко многим»). Сгенерировано в PlantUML.*

## 3. UML-диаграмма классов

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
