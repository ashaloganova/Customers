# Customers
В рамках этого проекта я работаю с данными о клиентах некоторой компании. Задача работы – провести разведывательный анализ данных, включая проверку взаимосвязей с помощью статистических тестов, а также применить деревья решений для задачи классификации – предсказать, примет ли клиент предложение в рамках рекламной кампании (переменная Response).

Используется язык R.

Переменные:
* ID: уникальный id клиента
* Year_Birth: год рождения клиента
* Education: уровень образования клиента
* Marital_Status: семейный статус клиента
* Income: годовой доход клиента
* Kidhome: число детей
* Teenhome: число подростков
* Dt_Customer: дата, когда респондент стал клиентом компании
* Recency: число дней, прошедших с последней покупки 
* MntWines: сумма, потраченная на вино за последние два года
* MntFruits: сумма, потраченная на фрукты за последние два года
* MntMeatProducts: сумма, потраченная на мясо за последние два года
* MntFishProducts: сумма, потраченная на рыбу за последние два года
* MntSweetProducts: сумма, потраченная на сладости за последние два года
* NumDealsPurchases: число покупок, совершенных по скидке
* NumWebPurchases: число покупок, совершенных через сайт 
* NumStorePurchases: число покупок, совершенных в магазине
* AcceptedCmp: 1 = если клиент принял предложение в предыдущей кампании, 0 = иначе
* Complain: 1, если клиент отправлял жалобу в течение последних двух лет, 0 -- иначе
* Response: 1 = если клиент принял предложение в текущей кампании, 0 = иначе
