## Задачи за упражнение.
# Задача 1.
Да се реализира клас `Room`, който описва помещение с площ (в дробно число кв.м) и описание (низ с произволна дължина). 
Да се реализира клас `Apartment`, който описва апартамент с произволен (потенциално неограничен) брой помещения. За двата класа да се реализират:
* подходящи конструктори и голяма четворка, ако е нужна;
* подходящи селектори и мутатори;
* операция `>>` за въвеждане от стандартен вход;
* операция `<<` за извеждане на стандартен изход.

Допълнително, за клас `Apartment` да се реализират следните функции:
* метод, който намира общата площ на даден апартамент;
* операция `[]`, която връща стая в апартамент по зададено име;
* операции за сравнение, които сравняват два апартамента по "просторност”, като за по-просторен се счита този апартамент, за който средната площ на стая е по-голяма.

Забележка. Не е нужно да се реализират мутатори за свойства, които не е смислено да бъдат променяни.

## Задачи за самостоятелна работа.
# Задача 2.
Да се реализира клас `Cashier`, който описва каса  в магазин с име на касиера (низ с произволна дължина) и оборот 
(дробно число лева). Да се реализира клас `Store`, който описва магазин с произволен (потенциално неограничен) брой каси. За двата класа да се реализират:
* подходящи конструктори и голяма четворка, ако е нужна;
* подходящи селектори и мутатори;
* операция `>>` за въвеждане от стандартен вход;
* операция `<<` за извеждане на стандартен изход.

Допълнително, за клас `Store` да се реализират следните функции:
* метод, който намира общия оборот за магазина;
* операция `[]`, която връща каса в магазина по зададено име на касиер;
* операции за сравнение, които сравняват два магазина по "доходност”, като за по-доходен се счита този магазин, за който средният доход на каса е е по-голям.

Забележка. Горната забележка е в сила и за тази задача.