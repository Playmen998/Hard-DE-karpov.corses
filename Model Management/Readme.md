## [DVC](https://github.com/Playmen998/DE-karpov.corses/tree/main/Model%20Management/DVC)
Data Version Control – это инструмент для управления версиями данных и моделей в проектах машинного обучения. Он дополняет Git, позволяя отслеживать изменения в больших файлах данных, обеспечивать воспроизводимость экспериментов и автоматизировать процессы обучения моделей.

**Зачем нужен DVC?**
1. Контроль версий данных – позволяет версионировать датасеты и модели, как код в Git.
2. Реплицируемые эксперименты – фиксирует параметры, данные и модели для воспроизводимости.
3. Совместная работа – легко делиться данными без необходимости хранить их в репозитории.
4. Оптимизация хранения – использует удаленные хранилища (S3, GDrive и др.), избегая дублирования данных.
5. Автоматизация пайплайнов – строит воспроизводимые ML-процессы с зависимостями.



## [MLFlow](https://github.com/Playmen998/DE-karpov.corses/tree/main/Model%20Management/MLFlow)
Был создан проект по автоматизации прогнозирования вероятности аварийности водителей в следующем году на основе собранных статистических данных. В рамках проекта разработана система, позволяющая анализировать данные и строить предсказательные модели для оценки риска.  

**Задание:**  
Добавьте разметку эксперимента для трекинга процесса обучения модели в MLFlow.  

**Метрики:**  
•    f1  
•    weightedPrecision  
•    weightedRecall  
•    accuracy  

**Параметры:**  
•    input_columns - список колонок исходного датасета (Пример: ['col1', 'col2'])  
•    maxDepth - параметр максимальной глубины обученной модели  
•    maxIter - параметр максимального числа итераций обучения модели  
•    maxBins - параметр максимального числа ветвлений  
•    target - целевая переменная для предсказаний  
•    features - список колонок, используемых для векторизации (Пример: ['col1', 'col2'])  
•    stage_0 - Тип трансформера первого стейджа пайплайна (obj.class.name)  
•    stage_1 - Тип трансформера второго стейджа пайплайна (obj.class.name)  
•    stage_2 - Тип трансформера третьего стейджа пайплайна (obj.class.name)  
•    stage_3 - Тип трансформера четвертого стейджа пайплайна (obj.class.name)  
