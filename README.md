## Постановка задачи 
Необходимо построить модель, которая предсказывает к какому из трех сегментов (0,1,2) относится каждый абонент.
Обучающая выборка contest_train.csv состоит из следующих столбцов:
ID - идентификатор абонента. TARGET - соответствующий абоненту сегмент. FEATURE_0…FEATURE_259 — характеристики абонента. Тестовая выборка contest_test.csv состоит из столбца ID и следующими за ним столбцами FEATURE_0 … FEATURE_259
Точность предсказания оценивается по метрике macro-f1_score. Распределение Public/Private - 50%/50%