Проект: Обучение с учителем: качество модели

Описание исследования: интернет-магазин «В один клик» продает широкий ассортимент товаров. Анализ данных показал снижение активности постоянных клиентов, несмотря на привлечение новых. Руководство поручило отделу цифровых технологий разработать решение для повышения покупательской активности постоянных клиентов.

Цель исследования: разработать решение и дать рекомендации для персонализации предложений, направленное на увеличение покупательской активности постоянных клиентов интернет-магазина

Главные задачи исследования:

1. Разработать модель, которая предскажет вероятность снижения покупательской активности
2. Выделите сегменты покупателей, проанализировать и дать необходимые рекомендации

Для поиска лучшей модели и решения задачи была проведена преобработка данных; проведен исследовательский анализ и устранены аномалии; объединены датасеты в один; проведен коррелляционный численных показателей, мультиколлинеарность не обнаружена; с помощью пайплайна найдена лучшая модель для предсказания - LogisticRegression(C=2, penalty='l1', random_state=42,solver='liblinear'). Показатели нашей модели хорошие, метрика ROC-AUC = 0.92