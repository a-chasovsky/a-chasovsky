**Привет** &nbsp; &#x1F44B;

Я специалист по анализу данных и машинному обучению.

* 🎓 &nbsp; Сфера деятельности:  
&ensp;&ensp;&ensp;&ensp;&nbsp; - анализ социально-экономических показателей;  
&ensp;&ensp;&ensp;&ensp;&nbsp; - сравнительный анализ региональных данных;  
&ensp;&ensp;&ensp;&ensp;&nbsp; - исследования в сотрудничестве с региональными и областными администрациями субъектов РФ;  
&ensp;&ensp;&ensp;&ensp;&nbsp; - научно-исследовательские работы (экономика, гос. управление).
   
* 👷‍♂️ &nbsp; Навыки и инструментарий:  
&ensp;&ensp;&ensp;&ensp;&nbsp; - статистический анализ данных;  
&ensp;&ensp;&ensp;&ensp;&nbsp; - описательная и предиктивная аналитика;  
&ensp;&ensp;&ensp;&ensp;&nbsp; - машиное обучение (классификация, регрессия, кластеризация);  
&ensp;&ensp;&ensp;&ensp;&nbsp; - дата-инженерные задачи, ETL-пайплайны (SQL, Clickhouse, Airflow);  
&ensp;&ensp;&ensp;&ensp;&nbsp; - визуализация и BI (Superset, Redash, Tableau);  
&ensp;&ensp;&ensp;&ensp;&nbsp; - программирование и статистические пакеты: Python, R, Stata, SPSS, Statistica;  
&ensp;&ensp;&ensp;&ensp;&nbsp; - ML-алгоритмы и библиотеки Python: sklearn, scipy, statsmodels, xgboost, etc.


Ознакомьтесь с кратким описанием моих проектов:

<img src='img/logo-house.png' valign='-0.2em' width='20'> &nbsp; Комбинирование регрессионного анализа и машинного обучения - <a href='https://achasovsky.github.io/house-prices/' target='_blank'>перейти к проекту</a>

<img src='img/logo-credit-card.png' valign='-0.35em' width='20'> &nbsp; Обнаружение мошеннических операций с кредитными картами - <a href='https://achasovsky.github.io/credit-card-fraud-detection/'>перейти к проекту</a>

<img src='img/logo-economics.png' valign='-0.35em' width='20'> &nbsp; Данные Росстата о состоянии экономики РФ - <a href='https://achasovsky.github.io/economics-rus/'>перейти к проекту</a>

<img src='img/logo-motogp.png' valign='-0.18em' width='25'> &nbsp; Методика оценки чемпионата MotoGP - <a href='https://achasovsky.github.io/motogp-analytics/'>перейти к проекту</a>







&ensp; &ensp; &nbsp;&nbsp; *Регрессионный анализ, машинное обучение, описательная аналитика, предиктивная аналитика*

<img src='img/logo-house.png' valign='-0.2em' width='20'> &ensp; 
<a href='https://achasovsky.github.io/house-prices/' target='_blank'>Перейти к проекту</a> &ensp; <a href='https://github.com/achasovsky/house-prices' target='_blank'>Перейти к репозиторию</a>

В проекте оценивается эффект от включения в регрессионную модель оценщика остатков (ошибок) регрессии. Отдельно для каждого этапа оценивается влияние исправления ошибок в данных, очистки и добавления новых предикторов.

Работа объединяет классический регрессионный анализ и проект по созданию модели машинного обучения. В результате получаеются три переходные модели на этапе исследования и подготовки данных, регрессионная модель, две модели машинного обучения (линейная и ансамбль Stacking), а также финальный регрессор.

#

- **Обнаружение мошеннических операций с кредитными картами**

&ensp; &ensp; &nbsp;&nbsp; *Машинное обучение, классификация*

<img src='img/logo-credit-card.png' valign='-0.35em' width='20'> &ensp; <a href='https://achasovsky.github.io/credit-card-fraud-detection/'>Перейти к проекту</a> &ensp; <a href='https://github.com/achasovsky/credit-card-fraud-detection' target='_blank'>Перейти к репозиторию</a>

В работе исследуется эффективность популярных алгоритмов машинного обучения, применяемых для выявления мошеннических операций с кредитными картами.

Для повышения эффективности создаются новые переменные, учитывающие поведение клиентов (согласно RFM). При обучении и валидации моделей учитываются особенности работы с банковскими транзакциями и временными рядами. Для оценки ML-алгоритмов применяются метрики AUC ROC, Average Precision, Card Precision, строятся кривые ROC и PR, исследуется влияние величины порогового коэффициента.

Дополнительно рассматриваются техники работы с несбалансированными датасетами: oversampling, undersampling, комбинирование undersampling и oversampling, присвоение весов классам.

#

- **Данные Росстата о состоянии экономики РФ**

&ensp; &ensp; &nbsp;&nbsp; *Преобразование и визуализация данных Росстата*

<img src='img/logo-economics.png' valign='-0.35em' width='20'> &ensp; <a href='https://achasovsky.github.io/economics-rus/'>Перейти к проекту</a> &ensp; <a href='https://github.com/achasovsky/economics-rus' target='_blank'>Перейти к репозиторию</a>

Федеральная служба государственной статистики (Росстат) регулярно публикует статистические данные о ключевых экономических показателях на своем сайте. Чтобы иметь возможность анализировать и визуализировать данные с помощью бибилотек Python, их необохдимо преобразовать.

В этом проекте представлены графики изменения цен на продукты питания (начиная с января 2021 года), а также динамика некоторых экономичеких показателей за 90-е и 2000-е годы.

#

- **Методика оценки чемпионата MotoGP**

&ensp; &ensp; &nbsp;&nbsp; *Аналитика данных*

<img src='img/logo-motogp.png' valign='-0.18em' width='25'> &ensp; <a href='https://achasovsky.github.io/motogp-analytics/'>Перейти к проекту</a> &ensp; <a href='https://github.com/achasovsky/motogp-analytics'>Перейти к репозиторию</a>

Одно из направлений в аналитике данных сегодня - это спортивная аналитика. Обычно исследуются данные наиболее популярных видов спорта: футбол, баскетбол, хоккей, бейсбол, американский футбол. Предложенная в этом проекте методика позволяет лучше понять мотоспорт.

В качестве примера анализируются данные мирового чемпионата по мотогонкам MotoGP. По запросу пользователя скрипт автоматически скачивает протокол гонки в формате pdf (используя навигацию сайта), извлекает из него данные, преобразовывает, считает метрики и строит итоговые графики.

#

- **Другие проекты по работе с данными**

&ensp;&ensp; <img src='img/logo-alert.png' valign='-0.2em' width='15'> &nbsp; [Anomaly Detection System](https://github.com/achasovsky/anomaly-detection-system)  &ensp;&ensp; | &ensp;&ensp; <img src='img/logo-etl.png'  valign='-0.2em' width='17'> &nbsp; [ETL-Pipeline](https://github.com/achasovsky/etl-pipeline)  &ensp;&ensp; | &ensp;&ensp; <img src='img/logo-ab.png'  valign='-0.3em' width='17'> &nbsp; [A/B Test](https://github.com/achasovsky/ab-testing)
