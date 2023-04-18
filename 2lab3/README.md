Задание 1. Объектная модель данных. Задание сформулировано на примере работы с иерархическим справочником номенклатуры. Выполните задание исходя из имеющегося в вашей теме ЛР иерархического справочника и его реквизитов. Например, услуги, сотрудники, студенты, экскурсии и т.д  
  
1.1. Создать интерфейс для пользователя (общая форма), в котором можно заполнить 4 поля:  
Наименование товара (тип строка);  
Группа товаров (тип строка);  
Цену;   
Производитель;  
![image](https://user-images.githubusercontent.com/107550671/209289975-2c69251a-1714-41cc-8579-5cbef1fbfe3c.png)  
1.2. Создать 2 кнопки “Завести номенклатуру” и “Найти номенклатуру”  
![image](https://user-images.githubusercontent.com/107550671/209290008-17c84cac-dba5-4323-be71-ea4136060201.png)  
1.3. При нажати на кнопку “Завести номенклатуру” должен создаваться новый элемент справочника со всеми указанными данными  
![image](https://user-images.githubusercontent.com/107550671/209291175-305da246-9fbc-417e-8292-a61e1dd67a87.png)  
![image](https://user-images.githubusercontent.com/107550671/209291207-b3acd9fc-508f-472e-9d36-77523d53d6ee.png)  
![image](https://user-images.githubusercontent.com/107550671/209291292-7a65d83c-f342-4af9-8344-1f0176dc2fdf.png)  
1.4. При нажатии на кнопку “Найти номенклатуру” должен производиться поиск по данным из поля с наименованием товара. Поля формы должны автоматически заполняться данными найденной номенклатуры. Если номенклатура не найдена выведите соответствующее сообщение  
![image](https://user-images.githubusercontent.com/107550671/209291426-4a1de038-b583-42a7-8626-84fe51534f1c.png)  
![image](https://user-images.githubusercontent.com/107550671/209291465-7e3edcce-9638-40e6-8953-e4119c6a747c.png)  
  


Задание 2. Загрузка данных из файла в таблицу значений  

2.1. Создайте файл csv, в котором хранятся данные аналогичный полям документа прихода (см. тему ЛР)  
![image](https://user-images.githubusercontent.com/107550671/209293210-a0c8fcc3-a757-47ef-af93-4cd336481456.png)  
2.2. Добавьте кнопку “Загрузить данные из файла”. Результат загрузки данных из файла отобразите в поле на форме.  
![image](https://user-images.githubusercontent.com/107550671/209293410-defa8e7f-cd12-44d0-a43e-69f8c33933f4.png)  
![image](https://user-images.githubusercontent.com/107550671/209293489-e4c5ffd5-3129-490a-8361-25b21789a150.png)  
2.3. Добавьте кнопку “Загрузите данные в таблицу значений”. Подсчитайте итог по одной из числовых колонок таблицы значений и выведите сообщение с результатом на форму  
![image](https://user-images.githubusercontent.com/107550671/209293825-4b9a7e71-c490-46d7-9f96-0fcc4bf8c664.png)  
![image](https://user-images.githubusercontent.com/107550671/209293958-6ecaa38f-a1d6-4c18-9a2e-5a7ae679a64f.png)  
2.4. Выбор файла/каталога, загрузку информации из файлов и загрузку данных в таблицу значений реализуйте в общем модуле  
![image](https://user-images.githubusercontent.com/107550671/209294049-aedbbc23-bf6d-45ce-9b2f-1745509aca74.png)  
![image](https://user-images.githubusercontent.com/107550671/209294088-27b8fabb-0af4-4be4-afde-e2a1310e2328.png)  
![image](https://user-images.githubusercontent.com/107550671/209294187-1f47c9ba-89b9-4c12-a76a-8659ec186a21.png)  
2.5. Сверните таблицу значений по одной или нескольким колонкам. Отсортируйте таблицу значений по нескольким колонкам.  
![image](https://user-images.githubusercontent.com/107550671/209294507-e21de6ba-e560-4edb-808e-cc84a112ddd7.png)  
![image](https://user-images.githubusercontent.com/107550671/209294556-683571f8-c89d-443d-8ce3-6d1059659cc9.png)  
![image](https://user-images.githubusercontent.com/107550671/209294639-d6cce040-837b-47fb-86be-1adf8a53cdda.png)  
![image](https://user-images.githubusercontent.com/107550671/209294673-f3561037-4eb9-4e4d-92e7-93009298a039.png)  
2.6. Добавьте поле табличного документа на форму. Добавьте кнопку “Загрузите данные в табличный документ. Реализуйте вывод данных из таблицы значений в табличный документ.  
![image](https://user-images.githubusercontent.com/107550671/209294343-c5257c3e-4fe2-4f38-94f6-4ec4d530c02f.png)  
![image](https://user-images.githubusercontent.com/107550671/209294415-29c6da9f-c59b-4ec3-911e-6683319452be.png)  
![image](https://user-images.githubusercontent.com/107550671/209294450-afffa2e3-5bec-4f7a-91c6-09243b157cf5.png)  
  
Выгрузите в git файл копию вашей базы (dt). Скриншоты выполнения 2-х заданий также добавьте в репозиторий.  
