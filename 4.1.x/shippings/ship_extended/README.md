"Расширение способов доставки"
==============================

* id модуля: ship_extended
* проверен на: CS-Cart 4.1.2 
* разработан: dbazhenov

Описание работы модуля
----------------------

Модуль расширяет отображение способов доставки на странице оформления заказа.
Для каждого способа доставки будет добавлен всплывающий блок с детальный описанием. 

Модуль имеет два вида отображения детального описания: 

1. (?) - tooltip всплывающий блок
2. "Нажмите здесь для детальной информации"

### Настройки в панели администратора

1. В настройках модуля можно выбрать тип отображения информации.
2. В настройких способа доставки появится новая текстовая область "Детальное описание". 

>Детальное описание необходимо указывать для каждого языка. 
>Текстовая область "Детальное описание" будет доступна только после создания способа доставки.

### Зона покупателя

Пройдите на шаг выбора способа доставки страницы оформления заказа.
Вы увидете выбранный вариант отображения.

Модуль подключает собственный файл style.css, поэтому внешний вид отображения можно редактировать в файле:

* >/var/design/themes/basic/css/addons/ship_extended/style.css

* >Информация будет отображаться только у способа доставки добавлено "Детальное описание"

Инструкция по установке
-----------------------

1. Перенести все директории (app, design, var) из данного раздела в основной каталог CS-Cart
2. Установить модуль из панели администратора

Скачать весь репозиторий Вы можете в основном каталоге репозитория ["public_addons_for_cscart"](https://github.com/dani32iz/public_addons_for_cscart "Основной каталог")
 по кнопке "Download Zip"

