В этом коде мы объявляем функцию express_delivery, которая принимает количество товаров в заказе и возвращает общую стоимость доставки для всех товаров. 
Мы также определяем декоратор delivery_decorator, который выводит информацию о времени запуска функции, количестве переданных товаров и стоимости доставки. 
Затем мы применяем декоратор к функции express_delivery. 
В основной программе мы запрашиваем у пользователя количество товаров в заказе, вызываем функцию express_delivery с этим аргументом и выводим общую стоимость доставки на экран.
