# Урок 1. Принципы ООП: Инкапсуляция, наследование, полиморфизм.

- Создать наследника реализованного класса ГорячийНапиток с дополнительным полем int температура.
- Создать класс Горячих Напитков Автомат реализующий интерфейс Торговый Автомат и реализовать перегруженный метод getProduct(int name, int volume, int temperature), выдающий продукт соответствующий имени, объёму и температуре.
- В main проинициализировать несколько ГорячихНапитков и Горячих Напитков Автомат и воспроизвести логику, заложенную в программе.
- Всё вышеуказанное создать согласно принципам ООП, пройденным на семинаре.

  Решение:
  
  1.Создаём класс Горячих Напитков//HotDrink
  
  2.Создаём наследника класса Горячих Напитков//HotDrink
  
  3.Создаём интерфейс Торгового Автомата//interface VendingMachine
  
  4.Реализуем класс Горячих Напитков Автомат//class HotBeverageMachine implements VendingMachine
  
  5.Создаём нескольких Горячих Напитков//HotDrink tea//HotBeverage coffee и использование Горячих Напитков Автомата//HotDrink product1 и HotBeverage product2.
  
 
  Описание:
  Класс HotDrink, имеет поля - name (название напитка) и - volume (объем напитка). Затем создается наследник этого класса - HotBeverage, который добавляет дополнительное поле temperature (температура напитка).
  Создается интерфейс interface VendingMachine, который содержит два перегруженных метода getProduct. Реализуем класс HotBeverageMachine, который реализует интерфейс VendingMachine.
  В этом классе перегруженные методы getProduct создают объекты соответствующих классов.

  В методе main происходит создание нескольких объектов классов HotDrink и HotBeverage, а также объекта класса HotBeverageMachine.
  Затем используя объект HotBeverageMachine, вызываются методы getProduct, которые возвращают нужные продукты.
