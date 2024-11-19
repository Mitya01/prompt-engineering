# prompt-engineering

## Задание

Известно, что LLM могут выдавать различные по качеству и релевантности ответы на один и тот же вопрос в зависимости от его формулировки и дополнительных инструкций. Необходимо оптимизировать промпт для получения технических скрининговых вопросов по описанию вакансии, используя Gigachat.

Результатом решения задачи должен быть выбранный оптимальный промпт, а также отчёт с описанием подборки оптимального промпта.

## Промпт

"Представь, что ты рекрутер, который ищет кандидата на позицию [вставить название позиции]. Сформулируй 5 технических скрининговых вопросов, основываясь на описании вакансии и примерах 5 скрининговых вопросов для разработчика на языке программирования Python. Вопросы должны быть краткими, понятными и соответствовать уровню знаний, необходимому для выполнения работы. Убедись, что скрининговые вопросы затрагивают несколько обязанностей и требований, предъявляемых кандидату. 

Описание вакансии: 

[Вставить описание вакансии] 

Пример 5 скрининговых вопросов для разработчика на языке программирования Python. 

1. Что такое Python и перечислите некоторые из его ключевых функций. 

2. Что такое cписки и кортежи в Python? 

3. В чём разница между изменяемым типом данных и неизменяемым типом данных? 

4. Можете ли вы объяснить распространённые обхода графов в Python? 

5. Что такое ошибка KeyError в Python и как с этим справиться?]

## Отчет с описанием подборки оптимального промпта.

### 1. Критерии оценки качества ответов 

Для оценки качества полученных ответов на основе промпта можно использовать следующие критерии: 

- Соответствие описанию вакансии: вопросы должны быть релевантны требованиям и обязанностям, указанным в описании вакансии. 

- Краткость и понятность: на вопросы можно устно ответить в течение короткого времени. 

- Техническая сложность: вопросы должны соответствовать уровню знаний, необходимому для выполнения работы, указанной в вакансии. 

- Разнообразие вопросов: наличие различных типов вопросов для более полного скрининга кандидата. 

### 2. Проверяемые гипотезы 

- Гипотеза 1: Использование контекста о роли рекрутера может повысить качество вопросов. Например, "Представь, что ты рекрутер, который ищет кандидата на позицию разработчика Python". 

- Гипотеза 2: Уточнение уровня сложности вопросов может привести к более релевантным ответам. Например, " Вопросы должны быть краткими, понятными и соответствовать уровню знаний, необходимому для выполнения работы".

- Гипотеза 3: Убрать примеры скрининговых вопросов для разработчика на языке программирования Python, чтобы не “засорять” промпт.

- Гипотеза 4: Добавление в промпт информации о том, что вопросы должны быть разнообразными. Например, "Убедись, что скрининговые вопросы затрагивают несколько обязанностей и требований, предъявляемых кандидату"

### 3. Оценка применения гипотез по выделенным критериям 

- Гипотеза 1: Применение контекста рекрутера привело к более целенаправленным вопросам, которые соответствуют описанию вакансии. Вопросы стали более практическими и ориентированными на реальный опыт кандидата. 

- Гипотеза 2: Уточнение уровня сложности вопросов позволило получить более адекватные и соответствующие уровню кандидата вопросы. Это также способствовало более быстрому и эффективному скринингу. 

- Гипотеза 3: Пример нужен для более точных скрининговых вопросов. Кроме того, использование примеров - в best-practices для промпт-инжиниринга. 

- Гипотеза 4: Добавление в промпт информации о том, что вопросы должны быть разнообразными помогло расширить спектр проверяемых знаний кандидата.