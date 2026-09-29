# Avito Recommendation System

Решение задачи retrieval / ranking для поиска до 50 релевантных объявлений по пользовательскому запросу.

## Идея

Итоговый pipeline:

**Query → Candidate generation → Ranking → Top-50**

Для Candidate generation используются BM25, E5 и контекстные признаки.

Для Ranking используются CatBoost и BGE Cross-Encoder.

## Запуск

1. Откройте `solution.ipynb`.
2. Раскомментируйте ячейку загрузки данных в блоке 2.0.
3. Запустите notebook сверху вниз.
