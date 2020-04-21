"# transferitems" 

Тестовое задание
Реализуйте небольшой модуль на базе 1С-Битрикс.
Название модуля: "Перенос элементов справочников".
Механика работы
1. Модуль устанавливается на один из сайтов. В настройках модуля указывается
один или более справочников (highload-блоков) для отслеживания изменений.
Модуль должен "запомнить" изменения, которые произошли с элементами при
дальнейшей работе сайта;
2. Администратор в интерфейсе выгружает изменения по справочнику в файл
(структура файла и формат остаётся на усмотрение кандидата);
3. На другой сайт устанавливается тот же модуль;
4. Администратор может импортировать изменения элементов;
5. Если измененный элемент не найден в справочнике, в который производится
импорт, должна быть зафиксирована ошибка "элемент не найден", но импорт
должен продолжиться;
6. У модуля должен быть режим расширенного логирования. При его включении
должен логироваться отчёт по импорту / экспорту элементов. В отчете должно
содержаться: количество добавленных/измененных/удаленных элементов и
зафиксированные ошибки.
