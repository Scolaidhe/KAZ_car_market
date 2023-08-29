# Исследование автомобильного рынка Казахстана за 2019 год

## Задача

На основании датасета, необходимо проанализировать как отдельно ситуацию на автомобильном рынке Казахстана, так ситуацию для конкретного автоцентра Mercur Auto. Исследование поможет определиться с основными показателями и конкурентами.

## Данные

Файл, содержащий информацию о продажах автомобилей в Казахстане за 2019 год с января по сентябрь включительно:   

- Год продажи (2019),
- Месяц продажи (январь - сентябрь),
- Название автоцентра,
- Название продаваемой марки автомобиля,
- Название модели автомобиля,
- Модификация модели автомобиля (удаляем),
- Год производства автомобиля,
- Страна, где произведен автомобиль,
- Вид топлива,
- Объем двигателя автомобиля в литрах,
- Тип коробки переключения передач (оставляем два варианта: автоматическая, механическая),
- Тип привода – в итоге оставляем RWD – задний привод, FWD – передний привод, 4WD – полный привод, 2WD – все остальное (подключаемый полный привод и где нет четкого указания передний или задний это привод),
- Сегмент – сегмент, к которому относится авто (удаляем),
- Регион продажи,
- Наименование дилерского центра – совпадает с компанией (удаляем),
- Тип клиента – юридическое или физическое лицо,
- Форма расчета – наличный и безналичный расчет (много пропусков – можно удалять),
- Количество – количество автомобилей в заказе,
- Цена USD – цена автомобиля,
- Продажа USD – цена заказа (цена авто умноженная на количество и за вычетом скидок если есть),
- Область – область продажи,
- Сегментация 2013 – сегмент автомобиля актуальный,
- Класс 2013 – класс автомобиля актуальный,
- Сегментация Eng – английская сегментация (удаляем),
- Локализация производства – удаляем (совпадает со страной производителем).

## Выводы

**Общие выводы по рынку и конкурентам Mercur Auto:**

1. Топ-5 дилеров по объему продаж:
    - топ-5 автоцентров по объему продаж: Toyota Motor Kazakhstan, БИПЭК АВТО, Astana Motors, Вираж, ТК КАМАЗ;
    - топ-5 автоцентров по количеству продаж: БИПЭК АВТО, Toyota Motor Kazakhstan, Astana Motors, Вираж, Nissan Manufactiring RUS;
    - при этом по объему продаж Mercur Auto на 7-м месте, по количеству продаж Mercur Auto на 8-м месте.
2. Mercur Auto имеет 100% долю брендов Volkswagen, Porsche, Audi на рынке, что очень хорошо, поскольку среди данных брендов нет конкурентов.
3. Доля Mercur Auto на рынке в деньгах за весь период: 2.71%, в натуральном выражении: 2.35%
4. В основном ближайшие конкуренты по регионам для Mercur Auto это: ТК КАМАЗ, УзАвто-Казахстан, Nissan Manufacturing, Renault Россия, БИПЭК АВТО.
5. Ближайшие конкуренты по сегментам: УзАвто-Казахстан, Автоцентр Бавария, MMC, Вираж.
6. Mercur Auto имеет довольно большую долю рынка в следующих классах:
    - спортивные автомобили: 84.04%
    - F класс: 35.70%
    - полноразмерный минивэн: 16.99%

## Используемые библиотеки
*pandas, numpy, matplotlib, seaborn, plotly.express*
