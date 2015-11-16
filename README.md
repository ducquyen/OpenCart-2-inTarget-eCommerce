# inTarget eCommerce

Tags: intarget, analytics, statistics, sales, widgets, ecommerce, интаргет, аналитика, статистика  
Requires at least: 2.0.3.1 (rs.2)
Tested up to: 2.1.0.1  
Stable tag: 1.0.1  
License: GNU General Public License, version 2  

**inTarget eCommerce** - система аналитики для интернет-магазинов, с возможностью отслеживать продажи и анализировать конверсии в реальном времени.

В inTarget реализованы следующие полезные опции для работы с конверсией на сайте:
 - добавление целей (например просмотр товара, добавление в корзину и т.д.) и отслеживание их выполнения посетителями на наглядных воронках;
 - возможность просмотреть данные по каждому посетителю (источник входа, дата рождения, страна и многое другое), а так же полную историю просмотров пользователем страниц сайта;
 - возможность увидеть социальные профили посетителей сайта (распознается около 20% трафика);
 - возможность писать пользователям личные сообщения в соцсетях;
 - возможность выгружать id пользователей и делать именной ретаргетинг ВК;
 - call back виджет - посетители сайта могут сами заказать обратный звонок с сайта;
 - возможность позвонить пользователям вашего сайта - intarget знает телефоны миллионов пользователей рунета;
 - возможность выборочного показа pop-up виджета (скидки, спецпредложения) отдельным сегментам посетителей;
 - сегментирование посетителей по набору признаков (мужчины, женщины, из москвы, не купившие, те кто заходил более 3-х раз и т.д.)

## Установка автоматически
  - В разделе *Extensions - Extension Installer* (*Модули - Установка расширений*) установите архив модуля intarget.ocmod.zip;
  - Установите и включите модификацию модуля в разделе *Extensions - Modifications* (*Модули - Модификации*) *intarget modification*.
  - Обносите кэш модификаций, чтобы они вступили в силу (в верхнем правом углу *Refresh* или *Обновить*).
  - Установите и включите модуль в разделе *Extensions - Мodules* (*Модули - Модули*).
  - Введите **email** и **ключ API** полученные в ЛК [inTarget](https://intarget.ru) и нажмите *Сохранить*.

*Если возникли сложности с настройками FTP, воспользуйтесь инструкцией по Установке модуля вручную.*

## Установка вручную
  - Распакуйте содержимое папки upload в корень сайта OpenCart2;
  - В разделе *Extensions - Extension Installer* (*Модули - Установка расширений*) установите модификатор модуля install.ocmod.xml;
  - Установите и включите модификатор модуля в разделе *Extensions - Modifications* (*Модули - Модификации*) *intarget modification*.
  - Обносите кэш модификаций, чтобы они вступили в силу (в верхнем правом углу *Refresh* или *Обновить*).
  - Установите и включите модуль в разделе *Extensions - Мodules* (*Модули - Модули*).
  - Введите **email** и **ключ API** полученные в ЛК [inTarget](https://intarget.ru) и нажмите *Сохранить*.

Более детальную информацию смотрите на сайте [inTarget](https://intarget.ru)

## Модуль "inTarget eCommerce"

Данный модуль находится на панели администрации в разделах *Extensions - Мodules* (*Модули - Модули*).

Здесь задаются:

**email:** необходимо указать email зарегистрированный в системе [inTarget](https://intarget.ru);
**ключ API:** необходимо указать ключ API, полученный в ЛК [inTarget](https://intarget.ru).

## Изменения

#### 1.0.1
 - Глобальный рефакторинг структуры модуля и кода.

#### 1.0
 * Релиз.

