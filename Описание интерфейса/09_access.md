# Группы прав доступа

К настройке группы прав доступа (ГПД) можно перейти, выбрав в верхней части Программы вкладку «Настройки программы» и нажать кнопку «Группы прав доступа к таблицам базы» (рис.1)

<p align="center">
<img src="images/09_access_01.png"><br>
<i>Рисунок 1. Переход к настройке групп прав доступа из меню</i>
</p>

Также в форме настроек бизнес-ролей пользователей можно нажать ПКМ на строке «Группа прав доступа к таблицам базы данных» и выбрать пункт «Добавить новую группу доступа к таблицам базы данных» (рис.2).

<p align="center">
<img src="images/09_access_02.png"><br>
<i>Рисунок 2. Переход к настройке групп прав доступа из формы БР</i>
</p>
 
Откроется форма (рис.3), состоящая из трех рабочих областей:

- Панель поиска (выделена зеленым).
- Панель меню (выделена желтым).
- Настройки ГПД (выделены голубым).

<p align="center">
<img src="images/09_access_03.png"><br>
<i>Рисунок 3. Форма настройки ГПД</i>
</p>

Чтобы посмотреть имеющиеся в Программе ГПД, нужно в панели поиска выбрать вариант отображения:

- Показать все.
- Показать последние 10.
- Показать ранее выбранные.

Будет отображен список ГПД (на рис.4 выделен желтым). После установки в Программе имеется только одна ГПД – Администратор.

<p align="center">
<img src="images/09_access_04.png"><br>
<i>Рисунок 4. Список имеющихся ГПД</i>
</p>

Описание кнопок панели меню приведено в табл.1.

<table border="1">
<tr>
    <td align="center"><b>Вид кнопки</b></td>
    <td align="center"><b>Название</b></td>
    <td align="center"><b>Назначение</b></td>
    <td align="center"><b>«Горячие» клавиши</b></td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_12.png"></td>
    <td>Показать панель поиска</td>
    <td>Отображает/скрывает панель поиска</td>
    <td>Ctrl+F</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_13.png"></td>
    <td>Создать новую запись</td>
    <td>Производиться очистка текущей формы ГПД и подготовка к внесению информации о новой ГПД</td>
    <td>Ctrl+N</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_01.png"></td>
    <td>Сохранить изменения</td>
    <td>Сохраняет изменения, сделанные в форме. Форма остается открытой</td>
    <td>Ctrl+S</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_14.png"></td>
    <td>Удалить запись</td>
    <td>Удаляет выбранную в панели поиска ГПД</td>
    <td></td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_15.png"></td>
    <td>Информация о текущей записи</td>
    <td>Выводит подробную информацию о ГПД, выбранной в панели поиска</td>
    <td>Ctrl+I</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_02.png"></td>
    <td>Обновить форму</td>
    <td>Обновляет данные о ГПД и перерисовывает форму. При этом информация считывается из базы данных, а значит, все несохраненные изменения будут потеряны</td>
    <td>Ctrl+R или F5</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_03.png"></td>
    <td>Перезагрузить форму</td>
    <td>Заново перезагружает форму и все данные в ней. Информация загружается из базы данных, все несохраненные изменения будут потеряны</td>
    <td>Ctrl+F5 или F6</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_16.png"></td>
    <td>Сформировать текстовый документ</td>
    <td>Формирует текстовый документ</td>
    <td>Ctrl+P</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_04.png"></td>
    <td>Сохранить изменения и закрыть форму</td>
    <td>Сохраняет сделанные в настройках ГПД изменения и закрывает форму</td>
    <td>Ctrl+E</td>
</tr>
</table>

<p align="center"><i>Таблица 1. Назначение кнопок формы настройки ГПД</i></p>

При нажатии кнопки ![](images/buttons/button_15.png) («Информация о текущей записи») откроется окно с дополнительными сведениями о ГПД, выбранной в панели поиска (рис.5).

<p align="center">
<img src="images/09_access_05.png"><br>
<i>Рисунок 5. Дополнительные сведения о ГПД</i>
</p>

Помимо просмотра информации, здесь можно изменить статус доступа к ГПД и состояние активности ГПД. Изменения выполняются путем выбора нужного значения из выпадающего списка.

Статус доступа к записи может принимать одно из следующих значений:

- Все действия разрешены.
- Нельзя удалять запись.
- Нельзя изменять данные (только добавление).
- Только чтение.
- Запись невидима.

Состояние активности можно изменить с «активный» на «архив». При этом запись станет недействующей, но не будет удалена из Программы. При необходимости архивную ГПД можно вернуть в статус активной. Для сохранения изменений нужно нажать кнопку ![](images/buttons/button_04.png)(«Сохранить изменения и закрыть форму»). При закрытии формы с помощью ![](images/buttons/cross_quit.png) внесенные изменения будут отменены.

Зеленым на рис.4 выделены дополнительные наборы кнопок для работы в форме ГПД:

- Вариант режима работы (рис.6).

<p align="center">
<img src="images/09_access_06.png"><br>
<i>Рисунок 6. Набор кнопок «Варианты режима работы»</i>
</p>

- Настройка вида (рис.7).

<p align="center">
<img src="images/09_access_07.png"><br>
<i>Рисунок 7. Набор кнопок «Настройка вида»</i>
</p>

Назначение кнопок описано в табл.2. 

<table border="1">
<tr>
    <td align="center"><b>Вид кнопки</b></td>
    <td align="center"><b>Название</b></td>
    <td align="center"><b>Назначение</b></td>
</tr>
<tr>
    <td colspan="3" align="center"><b>Набор кнопок «Варианты режима работы»</b></td>
</tr>
<tr>
    <td>-</td>
    <td>Показать разрешенные на чтение</td>
    <td>Отображает таблицы БД, доступные для чтения</td>
</tr>
<tr>
    <td>-</td>
    <td>Показать разрешенные на добавление</td>
    <td>Отображает таблицы БД, доступные для добавления</td>
</tr>
<tr>
    <td>-</td>
    <td>Показать разрешенные на удаление</td>
    <td>Отображает таблицы БД, доступные для удаления</td>
</tr>
<tr>
    <td>-</td>
    <td>Показать неразрешенные</td>
    <td>Отображает таблицы БД, доступ к которым запрещен</td>
</tr>
<tr>
    <td colspan="3" align="center"><b>Набор кнопок «Настройка вида»</b></td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_18.png"></td>
    <td>Автоподбор высоты строк</td>
    <td>Автоматически настраивает высоту строк в таблице доступов</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_19.png"></td>
    <td>Автоподбор ширины колонок</td>
    <td>Автоматически настраивает ширину колонок в таблице доступов</td>
</tr>
<tr>
    <td></td>
    <td>Раскрыть все</td>
    <td>Раскрывает все вложенные элементы в таблице доступов</td>
</tr>
<tr>
    <td></td>
    <td>Свернуть все</td>
    <td>Скрывает все вложенные элементы в таблице доступов</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_20.png"></td>
    <td>Обновить</td>
    <td>Обновляет права доступа в таблицы данными из БД. Несохранные изменения будут потеряны</td>
</tr>
<tr>
    <td align="center"><img src="images/buttons/button_21.png"></td>
    <td>Экспорт и печать</td>
    <td>Позволяет экспортировать матрицу доступов в нужный формат, сохранить в виде файла и/или распечатать</td>
</tr>
</table>

<p align="center"><i>Таблица 2. Назначение наборов кнопок</i></p>

<p align="center">
<img src="images/09_access_08.png"><br>
<i>Рисунок 8. Меню «Экспорт и печать» матрицы доступов</i>
</p>

Кнопка ![](images/buttons/button_41.png) («Расширенный экспорт») открывает матрицу доступа в редакторе, позволяющем настроить различные параметры (верхний/нижний колонтитулы, цвет фона, размер бумаги, ориентацию, масштаб, водяной знак и др.), после чего сохранить файл и/или отправить его на печать (рис.9).

<p align="center">
<img src="images/09_access_09.png"><br>
<i>Рисунок 9. Матрица доступа в редакторе расширенного экспорта</i>
</p>
 
## Создание ГПР и настройка прав доступа

После нажатия кнопки ![](images/buttons/button_13.png) («Создать новую запись») текущая форма будет очищена и подготовлена для создания новой ГПД. После этого нужно ввести название новой ГПД и примечание (необязательно) (рис.10).

<p align="center">
<img src="images/09_access_10.png"><br>
<i>Рисунок 10. Создание новой ГПД</i>
</p>

После ввода названия ГПД и примечания необходимо настроить права доступа к таблицам БД, выставив флагами (![](images/buttons/flagon.png)) режимы доступа к нужным таблицам.

>ВАЖНО! Описанная настройка прав доступа посредством ГПД устанавливает верхнеуровневые права по работе с таблицами БД и обычно выполняется администратором информационной безопасности.
>
>По умолчанию для всех вновь созданных ГПД установлен доступ ко всем элементам - в настройках сняты все флаги. Если хотя бы один флаг будет выставлен, активным становится лишь отмеченный режим доступа к выбранному элементу, доступ к остальным элементам блокируется.