## Репозиторий команды *AirWorker-Improvis* на [Авиахакатоне 2021](https://aviahackathon.mai.ru/)

## Кейс - Энергоаудит зданий с применением БПЛА

### Краткое описание

Развитие сервисов по поиску и обнаружению утечек тепловых потерь на основе тепловизионной съёмки с БПЛА

### Текущая ситуация

Ежегодно МАИ выделяют средства избюджета для оплаты отопления обслуживающим организациям. Эта сумма фиксированная. За счет мероприятий по энергосбережению, возможно сэкономить потребление, а следовательно и расходы на отопление. Сумма выделяемых средств при этом не уменьшится и возникнет положительный остаток  

### Проблема
Обычно решения по тепловизионной съемке дают представление о местах утечек, но не дают понимания об объёме теплопотерь, не предоставляют рекомендаций по мероприятиям в области энергосбережения. 
Не существует решения, которое позволило бы с помощью БПЛА произвести исследования теплопотерь на высокоэтажных зданиях с высокой точность. 

### Задача
Разработать решение, которое будет строить карту полета БПЛА вокруг здания и строить 3d-карту теплопотерь здания на основе сделанных фотографий (фотограмметрия). Решение, также должно делать расчет мест для наиболее эффективного утепления и оценивать экономический эффект от подобных мер.
Создать приложение, позволяющее по материалам тепловизионной съёмки с БПЛА оценить объёмы теплопотерь через различные поверхности здания (окна, стены и т.д.) для каждого типа поверхности оценить эффект (технический и экономический) от мероприятий по энергосбережению. Результаты представить в виде отчета.

### Данные

Источник 1: [Тарифы на тепловую энергию](https://www.mos.ru/depr/function/tarifnaya-politika/tarify-na-zku-na-2020-god/)

Источник 2: [Методика расчета теплопотерь стен здания](https://www.calc.ru/Teplopoteri-Doma-Raschet-Teplopoter.html)

Источник 3: [Пример отчета о тепловизионном обследования дома](https://energo-audit.com/otchet-po-teplovizionnomu-obsledovaniu-zhylogo-doma)

Источник 4: [Тепловизионная съёмка с БПЛА](https://disk.yandex.ru/d/56S7eTHSLGFkhA/20210324_202838?w=1)

Источник 5: [Методические рекомендации по оценке энергосберегающий мероприятий](http://sro61.ru/docs/metodiki/Met.rek-cii-po-ocenke_effektivnosti_e-sb.mer..pdf)

Источник 6: [Презентация кейса](https://github.com/Roman200110/CalculationOfHeatLoss/raw/master/Resources/%D0%9A%D0%B5%D0%B9%D1%81.pptx)

### Дополнительные источники данных для сегментации элементов фасада

Источник 1. [eTRIMS Image Database](http://www.ipb.uni-bonn.de/projects/etrims_db/)

Источник 2. [LabelMeFacade Database](https://www.inf-cv.uni-jena.de/Research/Datasets/LabelMeFacade.html)

Источник 3. [Ecole Centrale Paris Facades Database](http://vision.mas.ecp.fr/Personnel/teboul/data.php)

Источник 4. [CMP Facade Database](https://cmp.felk.cvut.cz/~tylecr1/facade/)

Источник 5. [ICG Graz50 Facade Dataset](http://www.vision.ee.ethz.ch/~rhayko/paper/cvpr2012_riemenschneider_lattice/graz50_facade_dataset.zip)

Источник 6. [Zurich Buildings Database](https://icu.ee.ethz.ch/research/datsets.html)

Источник 7. [VarCity Dataset](http://www.varcity.ethz.ch/3dchallenge/index.html)

### Постановщик

![Provider Logo](http://aviahack.mai.ru/media/ck_uav.png)