# portfolio_python_analytics
Welcome to see my mini-projects using python. This repository based on Karpov-course ('data analytics') and few projects I made at university and for testing.
Short describtions of tasks and data are provided here, others inside of files.

Добро пожаловать! Тут собраны мои мини-проекты, которые я выполняла, учась на специализации "аналитик данных" от Карпова. Также будут добавляться учебные файлы из университета и других источников. Спасибо, что решили ознакомиться.

**FOR mini-project 2(3 lesson)**:
For Russian version scroll down.
Tasks:
1) upload 2 files  user_data and logs.
2) describe data, find shape, change type if neccessary, etc.
3) Which client made the most successful operations? 
Find the platform with the most successfull operations. 
Which platform is preferred by premium-segment clients? 
Visualize the distibution between the clients' age and operations type (premium or not).
Visualize the distibution of successfull operations
Visualize the distibution of successfull operations, which were made on the platform = computer, depending on the clients' age. Use sns.countplot

Задачи
Какой клиент совершил больше всего успешных операций? (success == True) С какой платформы осуществляется наибольшее количество успешных операций? Какую платформу предпочитают премиумные клиенты? Визуализируйте распределение возраста клиентов в зависимости от типа клиента (премиум или нет) Постройте график распределения числа успешных операций Визуализируйте число успешных операций, сделанных на платформе computer, в зависимости от возраста, используя sns.countplot (x – возраст, y – число успешных операций). Клиенты какого возраста совершили наибольшее количество успешных действий?

Описание данных user_data:
client – идентификатор пользователя premium – является ли клиент премиум age – возраст logs:
client – идентификатор пользователя success – результат (успех - 1, нет - 0) platform – платформа time – время в формате Unix

**FOR LESSON 4**:
Данные по поездкам на такси. На этот раз – из Перу, с рейтингами водителей, пассажиров, координатами, и другими деталями.

journey_id – уникальный id поездки
user_id – id пользователя
driver_id – id водителя
taxi_id – id машины
icon – тип поездки
start_type – тип заказа (asap, reserved, delayed)
start_at – время начала поездки
start_lat – исходное местоположение пользователя, широта
start_lon – исходное местоположение пользователя, долгота
end_at – время окончания поездки
end_lat – итоговое местоположение, широта
end_lon – итоговое местоположение, долгота
end_state – состояние заказа
driver_start_lat – исходное местоположение водителя, широта
driver_start_lon – исходное местоположение водителя, долгота
arrived_at – время прибытия водителя
source – платформа, с которой сделан заказ
driver_score – оценка водителя клиентом
rider_score – оценка клиента водителем
