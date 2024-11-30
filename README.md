![image](https://publish.purewow.net/wp-content/uploads/sites/2/2018/05/nyc-yellow-taxi-in-times-square-hero.jpg)

# PROJECT-5. Прогнозирование продолжительности поездки на такси в Нью-Йорке
##  Практика в выполнении задач машинного обучения, направленную на автоматизацию бизнес-процессов.

### Описание проекта

Представим, что мы заказываем такси из одной точки Нью-Йорка в другую, причём необязательно, что конечная точка должна находиться в пределах города. Сколько мы должны будем заплатить за поездку?

Известно, что стоимость такси в США рассчитывается на основе фиксированной ставки и тарифной стоимости, величина которой зависит от времени и расстояния. Тарифы варьируются в зависимости от города.

В свою очередь, время поездки зависит от множества факторов, таких как направление поездки, время суток, погодные условия и так далее.

Таким образом, если мы разработаем алгоритм, способный определять длительность поездки, мы сможем прогнозировать её стоимость самым тривиальным образом, например, просто умножая стоимость на заданный тариф.

Сервисы такси хранят огромные объёмы информации о поездках, включая такие данные, как конечная и начальная точки маршрута, дата поездки и её продолжительность. Эти данные можно использовать для того, чтобы прогнозировать длительность поездки в автоматическом режиме с привлечением искусственного интеллекта.

---

### Бизнес-задача:

Определить характеристики и с их помощью спрогнозировать длительность поездки на такси.

### Техническая задача для специалиста в Data Science:

Построить модель машинного обучения, которая на основе предложенных характеристик клиента будет предсказывать числовой признак — время поездки такси, то есть решить задачу регрессии.

---

### Организационная информация

Проект будет состоять из пяти частей:

1. **Первичная обработка данных**

   В рамках этой части нам предстоит сформировать набор данных на основе предложенных нам источников информации, а также обработать пропуски и выбросы в данных.

2. **Разведывательный анализ данных (EDA)**

   Нам необходимо будет исследовать данные, 'нащупать' первые закономерности и выдвинуть гипотезы.

3. **Отбор и преобразование признаков**

   На этом этапе мы перекодируем и преобразуем данные таким образом, чтобы их можно было использовать при решении задачи регрессии — для построения модели.

4.  **Решение задачи регрессии: линейная регрессия и деревья решений**

    На данном этапе мы построим свои первые прогностические модели и оценим их качество. Тем самым мы создадим так называемый *baseline*, который поможет нам ответить на вопрос: «Решаема ли вообще представленная задача?»

5.  **Решение задачи регрессии: ансамбли моделей и построение прогноза**

     На заключительном этапе мы сможем доработать своё предсказание с использованием более сложных алгоритмов и оценить, с помощью какой модели возможно сделать более качественные прогнозы.

---
