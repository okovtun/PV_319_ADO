https://github.com/okovtun/PV_319_ADO.git
https://www.youtube.com/playlist?list=PLeqyOOqxeiINU_oiVfrFFUtdIjISweOYT

Best of the best WinAPI lessons:
	https://www.youtube.com/watch?v=kQ2TTgfvR94&list=PL0_nf9F9pvZNQsdlmE6s0UyixTnT4778Y

Max Payne:
	https://github.com/MaSidrenko/ManagePassword/tree/master/ManagePassword

DataSet:
https://learn.microsoft.com/en-us/dotnet/framework/data/adonet/dataset-datatable-dataview/creating-a-dataset

TODO:
1. Прикрутить обработчик к выпадающему списку 'cbStudentsGroup';
2. Подумать над тем, как определять зависимые ComboBox-ы и фильтровать в них значения
   при выборе значения в основном ComboBox-е, например, когда мы выбираем направление,
   то в cbStudentsGroup должны отображаться только группы выбранного направления;

TODO:
0. Сделать COMMIT и создать ветку 'Decomposition';
1. Обеспечить обновление кэша каждые 5 минут, и при необходимости обновить кэш прямо сейчас должна быть кнопка Refresh;
2. Вынести класс Cache в отдельный проект;
3. Вынести класс Connector в отдельный проект и попробовать применить его в основном проекте 'Academy' из другого проекта;
4. Все ComboBox-ы должны обрабатываться одной функцией;

DONE:
1. DataTable:	https://learn.microsoft.com/en-us/dotnet/api/system.data.datatable?view=net-9.0
2. DataSet:		https://learn.microsoft.com/en-us/dotnet/api/system.data.dataset?view=net-9.0

DONE:
Метод Print() должен определять, есть ли у таблицы родитель, и если он есть,
то вместо числового значения ключа должно выводиться его целевое значение.

DONE:
1. Сделать COMMIT и создать ветку 'DataSetOptimisation';
2. В этой ветке оптимизировать код создания и заполнения 'DataSet' прямо в классе 'MainForm';

DONE:
1. На вкладку 'Directions' добавить галочку "Показать пустые направления";

TODO:
1. Создать ветку 'Filters';
2. На вкладке 'Directions' для каждого направления отобразить количество групп и студентов;	DONE
3. На вкладке 'Groups' добавить ComboBox с направлениями обучения,
   и при выборе направления из ComboBox в таблице отображаются только группы выбранного направления;
4. На вкладке 'Students' добавить два ComboBox-а, для групп и направлений соответсвено.
   При выборе направления в 'dgvStudents' отображаются только студенты выбранного направления,
   а из comboBoxGroups можно выбрать только группы указанного направления;

DONE:
1. Отобразить соответсвующие таблицы на всех вкладках;
2. В строке состояние (statusStrip) отобразить количество студентов, групп, .... преподавателей;

DONE:
1. Написать метод, который по названию дисциплины возвращает 'id' дисциплины;
2. Написать метод, который по фамилии преподавателя возвращает 'id' преподавателя;
3. Написать метод, который подсчитывает количество студентов;

	Каждый из этих методов будет возвращать скалярное значение;

DONE:
1. При помощи SQL-запроса удалить лишние пробелы из таблицы 'Directors';	DONE
2. Сделать COMMIT;
3. Создать ветку 'MoviesConnector' и в этой ветке подключение к Базе,
   и получение данных вынести в класс 'Connector';
4. Залить репозиторий на GitHub;