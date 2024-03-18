### Привет &#x1F44B;

Я специалист по анализу данных и машинному обучению.  
* 🎓 &nbsp; Более 3 лет работаю аналитиком в Высшей школе экономики (НИУ ВШЭ).  
&ensp;&ensp;&ensp;&nbsp;Сфера деятельности:  
&ensp;&ensp;&ensp;&ensp;&ensp; - анализ социально-экономических показателей;  
&ensp;&ensp;&ensp;&ensp;&ensp; - сравнительный анализ региональных данных;  
&ensp;&ensp;&ensp;&ensp;&ensp; - обработка и анализ данных исследований по заказу региональных и областных администраций.
   
* 👷‍♂️ &nbsp; Область знаний:  
    &ensp;&ensp;&ensp;&ensp;\- статистический анализ данных, регрессионный анализ;  
    &ensp;&ensp;&ensp;&ensp;\- описательная и предиктивная аналитика;  
    &ensp;&ensp;&ensp;&ensp;\- машиное обучение (классификация, регрессия, кластеризация);  
    &ensp;&ensp;&ensp;&ensp;\- дата-инженерные задачи, построение ETL-пайплайнов (SQL, Clickhouse, Airflow);  
    &ensp;&ensp;&ensp;&ensp;\- программирование и статистические пакеты: Python, R, Stata, SPSS, Statistica;  
    &ensp;&ensp;&ensp;&ensp;\- ML-алгоритмы и библиотеки Python: sklearn, scipy, statsmodels, xgboost, etc.;  
    &ensp;&ensp;&ensp;&ensp;\- визуализация и BI (Superset, Redash, Tableau).

<hr style='color:red'>

### Список проектов

### <img src='img/logo-house.png' width='20' style='margin-left:-0.2em;vertical-align:0em;'> &ensp; [Сочетание регрессионного анализа и машинного обучения для увеличения точности и интерпретируемости модели](https://a-chasovsky.github.io/house-prices/)

<font size='2'> &ensp; &ensp; &ensp; *Регрессионный анализ, машинное обучение, описательная аналитика, предиктивная аналитика* </font>



### <img src='img/logo-credit-card.png' width='20' style='vertical-align:-0.28em;'> &ensp; [Обнаружение мошеннических операций с кредитными картами](https://a-chasovsky.github.io/credit-card-fraud-detection/)

<font size='2'> &ensp; &ensp; &ensp; *Машинное обучение, классификация* </font>

В работе исследуется эффективность популярных алгоритмов машинного обучения, применяемых для выявления мошеннических операций с кредитными картами. 

Для повышения эффективности создаются новые переменные, учитывающие поведение клиентов (согласно RFM). При обучении и валидации моделей учитываются особенности работы с банковскими транзакциями и временными рядами. Для оценки ML-алгоритмов применяются метрики AUC ROC, Average Precision, Card Precision, строятся кривые ROC и PR, исследуется влияние величины порогового коэффициента. 

Дополнительно рассматриваются техники работы с несбалансированными датасетами: undersampling, комбинирование undersampling и oversampling, присваение весов классам. 

### <img src='img/logo-economics.png' width='20' style='vertical-align:-0.28em;'> &ensp; [Данные Росстата о состоянии экономики РФ](https://a-chasovsky.github.io/economics-rus/)

<font size='2'> &ensp; &ensp; &ensp; *Преобразование и визуализация данных Росстата* </font>





### <img src='img/logo-motogp.png' width='25' style='vertical-align:-0.12em;'> &ensp; [MotoGP Analytics](https://a-chasovsky.github.io/motogp-analytics/)

<font size='2'> &ensp; &ensp; &ensp; *Аналитика данных* </font>

Одно из направлений data science - спортивная аналитика. Обычно исследуются данные наиболее популярных видов спорта: футбол, баскетбол, бейсбол, американский футбол. В свою очередь, я придумал методику, с помощью которой можно лучше понять такой вид спорта, как чемпионат мира по мотогонкам MotoGP. По запросу пользователя скрипт автоматически скачивает протокол гонки в формате pdf (используя навигацию сайта), извлекает из него данные, преобразовывает, считает метрики и строит итоговые графики.  

#### <img src='img/logo-alert.png' width='15' style='vertical-align:-0.15em;'> &ensp; [Anomaly Detection System](https://github.com/a-chasovsky/kc_anomaly_detection_system)

<font size='2'> &ensp; &ensp; &ensp; *Аналитика данных* </font>

Система осуществляет поиск аномалий в данных в режиме, близком к реальному времени (временной интервал - 15 минут). В качестве базового периода берутся средние значения аналогичного интервала за предыдущие 3 дня, считаются верхние и нижние пороги, и в случае обнаружения аномальных значений ответственному лицу отправляется сообщение в мессенджере Telegram.

#### <img src='img/logo-etl.png' width='17' style='vertical-align:-0.25em;'> &ensp; [ETL-Pipeline](https://github.com/a-chasovsky/kc_etl_pipeline)

<font size='2'> &ensp; &ensp; &ensp; *Дата-инжиниринг* </font>

Данные выгружаются из нескольких таблиц БД, рассчитываются агрегированные характеристики. Результаты записываются в датафрейм, который загружается обратно в базу. Процедура повторяется один раз в сутки.

#### <img src='img/logo-ab.png' width='17' style='vertical-align:-0.33em;'> &ensp; [A/B Test](https://github.com/a-chasovsky/kc_ab_testing)

<font size='2'> &ensp; &ensp; &ensp; *Статистические тесты* </font>

A/B тест с выводами и рекомендациями.