# OpenCart Exchange 1C #

 Модуль обмена данными с 1С 8.x в формате CommerceML2 для OpenCart
 
 * Домашняя страница: http://zenwalker.ru/lab/opencart-exchange1c/
 * Видеоинструкция установки: https://www.youtube.com/watch?v=wv_-ve_p1LA
 * Исходные коды: https://github.com/ethernet1/opencart-exchange1c
 * Тема поддержки: http://opencartforum.ru/topic/15471-opencart-exchange-1c/

## Возможности ##
 
 * Выгрузка полной иерархии категорий
 * Выгрузка изображений
 * Выгрузка скидок
 * Выгрузка свойств (в атрибуты)
 * Обмен заказами (односторонний, OpenCart → 1C)
 * Наложение водяных знаков на загружаемые картинки товаров
 * Ручной импорт товаров через форму в админке
 * Автогенерация SEO URL (требуется Deadcow SEO 2.1)
 * Автогенерация SEO URL (путем транслитерации, применяется к товарам, производителям, категориям) (issue #12)

## Установка ##

 Установка модуля ничем не отличается от остальных, но для работы потребуется [vQmod](http://code.google.com/p/vqmod/downloads/list).

 1. Загрузить содержимое директории upload в корень сайта
 2. Активировать модуль в настройках и задать логин/пароль
 3. В 1С в качестве адреса выгрузки указать http://%sitename%/export/exchange1c.php

## Лицензия ##

 Данное программное обеспечение распространяется на условиях [GNU General Public License v3.0](http://www.gnu.org/licenses/gpl.html).
 
