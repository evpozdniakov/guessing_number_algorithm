# Сегментирование клиентов онлайн-магазина подарков

*Проект по курсу [«Профессия Data Science»](https://lms.skillfactory.ru/courses/course-v1:Skillfactory+DST-PRO+15APR2020/about)\
от школы [SkillFactory](https://skillfactory.ru)*

В данном проекте вы решите настоящую бизнес-задачу в области маркетинга. Вам предстоит произвести сегментацию клиентов на основе их покупательской способности, частоты совершения заказов и срока давности последнего заказа, а также определить оптимальную стратегию взаимодействия с ними.

## Бизнес-задача

Произвести сегментацию существующих клиентов, проинтерпретировать эти сегменты и определить стратегию взаимодействия с ними.

## Техническая задача

Построить модель кластеризации клиентов на основе их покупательской способности, частоты заказов и срока давности последней покупки, определить профиль каждого из кластеров.

## Цели проекта

1. Произвести предобработку набора данных.
1. Провести разведывательный анализ данных и выявить основные закономерности.
1. Сформировать категории товаров и клиентов.
1. Построить несколько моделей машинного обучения, решающих задачу кластеризации клиентов, определить количество кластеров и проинтерпретировать их.
1. Спроектировать процесс предсказания категории интересов клиента и протестировать вашу модель на новых клиентах.

## План работы

Проект будет состоять из шести частей:

### 1. Базовый анализ и знакомство с данными

Первая часть проекта будет посвящена знакомству с исходными данными и их структурой.

### 2. Предобработка и очистка данных

Далее вам необходимо будет подготовить датасет для кластеризации, очистив его от пропусков, дублей, выбросов и другого «мусора».

### 3. Разведывательный анализ данных (EDA)

Вам предстоит произвести небольшое исследование данных, нащупать первые закономерности и выдвинуть гипотезы.

### 4. RFM-сегментация клиентов. Часть I

Вы познакомитесь с очень популярным в маркетинге методом сегментации клиентов под названием RFM (Recency, Frequency, Monetary). На основе этого метода вы сформируете из исходного датасета о транзакциях таблицу с RFM-характеристиками клиентов и произведёте их первичную сегментацию.

### 5. RFM-сегментация клиентов. Часть II

Мы попробуем расширить наши клиентские сегменты и создать промежуточные категории с помощью нелинейных преобразований размерности. Это позволит произвести более качественную кластеризацию и улучшить стратегии взаимодействия с клиентами.

### 6. RFM-сегментация клиентов. Часть III

Наконец, вам будет необходимо построить модель классификации, которая позволит автоматически определять сегмент клиента на основе нескольких транзакций.