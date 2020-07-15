# Spoken_Corpora_with_Kaldi
Проект по распознаванию корпуса звучащей речи SpokenCorpora на русском языке с помощью Kaldi: оценка качества распознавания, создание алгоритма автоматического поиска и исправления ошибок в транскрибациях.

## План задач

|Задача | Кто делает | Статус |
| ---- | ---- | ---- |
| Создать репозиторий проекта |Катя | Done |
| Скачать [корпус звучащей речи SpokenCorpora](https://github.com/smekur/Spoken_Corpora_with_Kaldi/tree/master/%D0%9A%D0%BE%D1%80%D0%BF%D1%83%D1%81%20%D0%B7%D0%B2%D1%83%D1%87%D0%B0%D1%89%D0%B5%D0%B9%20%D1%80%D0%B5%D1%87%D0%B8%20SpokenCorpora), загрузка в репозиторий, создание описания | Настя | Done |
| Собрать ["золотой стандарт"](https://github.com/smekur/Spoken_Corpora_with_Kaldi/tree/master/Golden%20standard)| Катя, Настя| Done |
| Формирование корпуса текстов "Рассказы о сновидениях", предобработка текста, загрузка в репозиторий .xlsx файла | Катя | Done |
| Формирование корпусов текстов "Рассказы сибиряков", "Истории о подарках и катании на лыжах", предобработка текста, загрузка в репозиторий .xlsx файла| Настя | Done |
| Подсчёт метрик "золотого стандарта" | Катя, Настя | Done |
| Распознание [корпуса звучащей речи с помощью Kaldi](https://github.com/smekur/Spoken_Corpora_with_Kaldi/tree/master/%D0%A2%D1%80%D0%B0%D0%BD%D1%81%D0%BA%D1%80%D0%B8%D0%B1%D0%B0%D1%86%D0%B8%D0%B8) | Катя, Настя | Done |
| Формирование корпуса распознанной речи "Рассказы о сновидениях", загрузка в репозиторий .xlsx файла | Катя | Done |
| Формирование корпусов распознанной речи "Рассказы сибиряков", "Истории о подарках и катании на лыжах", загрузка в репозиторий .xlsx файла| Настя | Done |
| Подсчёт метрик для распознанного корпуса | Катя, Настя | Done |
| Сравнительный анализ полученных данных по двум корпусам ("золотой стандарт" и распознанной речи) | Катя, Настя | Done |
| Подсчет и сравнение метрик для оценки качества распознавания речи для двух корпусов | Катя | In Progress |
| Краткая наивная классификация ошибок в полученных транскрибациях | Настя | Done |
| Сбор корпуса 1 и корпуса 2 для обучения языковой модели на основе марковских цепей для разработки алгоритма автоматического поиска ошибок в транскрибациях | Настя, Катя | Done |
| Предобработка корпуса 1 для обучения языковой модели на основе марковских цепей (токенизация, лемматизация, чистка корпуса) | Настя | Done |
| Предобработка корпуса 2 для обучения языковой модели на основе марковских цепей (токенизация, лемматизация, чистка корпуса) | Катя | Done |
| Сбор статистики по тренировочному корпусу 1 | Настя | Done |
| Сбор статистики по тренировочному корпусу 2 | Катя | Done |
| Создание вспомогательных словарей (список вводных слов и частотных дискурсивных маркеров, список частотных слов с дефисом) | Настя | Done |
| Обучение языковой модели на основе марковских цепей на корпусе 1, корпусе 2 | Настя, Катя | Done |
| Объявление функций для предобработки тестового корпуса | Катя, Настя | Done |
| Объявление функций для нахождения и исправления ошибок в транскрибациях | Катя | Done |
| Запуск алгоритма на тестовом корпусе | Катя, Настя | Done |
| Оценка качества работы алгоритма на тестовом копусе (подсчет метрик: precision, recall, f1, accuracy) | Катя, Настя | Done |
| Подбор предобученной векторной модели для минимизации ложно найденнных ошибок (false positives) | Настя | Done |
| Создание словаря для конвертации частеречных тэгов (из формата от Pymorphy2 в формат Universal Dependencies) | Настя | Done |
| Объявление функций для нахождения ошибок в транскрибациях с использованием векторой модели | Настя | Done |
| Оценка качества работы алгоритма с использованием векторной модели | Настя | Done |
| Объявление функции для автоматического исправления ошибок с использованием расстояния Левенштейна по фонетическим представлениям | Катя | Done |
| Оценка качества работы алгоритма автоматического исправления ошибок с использованием расстояния Левенштейна по фонетическим представлениям | Катя | Done |
| Составление презентации финального проекта | Катя, Настя | Done |



