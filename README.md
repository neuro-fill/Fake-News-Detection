# Fake-News-Detection
Инструмент для обнаружения недостоверных новостей

### Задача:
Разработать инструмент для анализа текстов новостей с целью выявления их достоверности. Основная цель — помочь пользователям фильтровать информацию и избегать дезинформации.

#### Ссылка на код

### Что сделано:
* Сбор и предобработка данных из открытых источников, содержащих маркированные статьи.
* Анализ текста, включая токенизацию, удаление стоп-слов и приведение к нормальной форме.
* Обучение модели классификации с использованием наивного байесовского классификатора и метода опорных векторов.

#### Используемые технологии:
* Python и библиотеки scikit-learn и pandas для обработки данных.
* NLTK для работы с текстами, включая токенизацию и анализ.
* Выбор технологий обусловлен их высокой производительностью при работе с текстовыми данными и удобством интеграции в Jupyter Notebook.

### Результат:
Модель с точностью 85% на тестовых данных. Инструмент готов к использованию как часть информационного приложения или веб-сервиса.

#### Команды:
* Установка зависимостей: pip install -r requirements.txt
* Локальный запуск: python app.py
* Запуск тестов: pytest




