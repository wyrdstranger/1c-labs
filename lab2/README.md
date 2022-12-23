Задания:  
Подсистемы  
Создайте подсистемы: “НСИ и Администрирование”, “Отчеты” и еще 2 на ваше усмотрение, например “Расписание”, или “Закупка”, или “Продажа”, или “Склады” исходя из темы ЛР  

![image](https://user-images.githubusercontent.com/107550671/209158757-74f1ef96-c949-4b98-b713-f3ae8c7e93b1.png)  

Добавьте картинки к подсистемам  
![image](https://user-images.githubusercontent.com/107550671/209158967-94da94fc-0351-459e-9a06-a275d7e53f8e.png)  

Расположите подсистемы по алфавиту  

![image](https://user-images.githubusercontent.com/107550671/209159072-7508b96d-017c-4309-9636-00cf71046538.png)  
![image](https://user-images.githubusercontent.com/107550671/209159113-25bb9791-b269-4cdd-aa9d-341ff8c5629e.png)  

Создайте минимум 2 подчиненных подсистемы, например “Справочники”, “Администрирование, подчиненные “НСИ и Администрирование”  

![image](https://user-images.githubusercontent.com/107550671/209159240-205f84e0-dced-4838-b354-69d30aadd92c.png)  

В режиме конфигуратора скройте видимость подсистемы “Отчеты”, проверьте, что данная подсистема уже не появляются при старте  

![image](https://user-images.githubusercontent.com/107550671/209159320-b8ba3fcb-cc05-46d6-adfe-af785372eae9.png)  
![image](https://user-images.githubusercontent.com/107550671/209159424-586f518f-6ab6-4dc8-a069-8aee9ea393e1.png)  
  
Продемонстрируйте изменения в интерфейсе в режиме предприятия скриншотами   
  
Справочники  
Созданные в ЛР №1 справочники необходимо добавить в подсистемы.  

![image](https://user-images.githubusercontent.com/107550671/209159583-16bd786d-2296-4aea-8d51-6dca4757c720.png)  

В каждый справочник нужно добавить 2-3 реквизита с разными типами (пример в теме №1 к ЛР)  

![image](https://user-images.githubusercontent.com/107550671/209160196-b6fc84ca-4d70-408e-ac26-cf23a9154c41.png)  

Минимум один из справочников нужно сделать иерархическим  

![image](https://user-images.githubusercontent.com/107550671/209160369-cc371932-a406-4843-939a-797e26c06c85.png)  

Создайте в иерархическом справочнике предопределенные группы и элементы  

![image](https://user-images.githubusercontent.com/107550671/209160714-a2a8791e-1ffc-457f-af6f-596833217383.png)  
![image](https://user-images.githubusercontent.com/107550671/209161002-eea117e6-8b4b-41ea-9d89-140ce6000ad9.png) 

Минимум в одном из справочников необходимо создать табличную часть с реквизитами  

![image](https://user-images.githubusercontent.com/107550671/209161356-8f82d603-25c9-41b2-82c7-c612171030d9.png)  

Несколько справочников нужно связать между собой через объект-ссылку. Тип реквизита должен быть СправочникСсылка (пример в теме №1 к ЛР)  

![image](https://user-images.githubusercontent.com/107550671/209162463-49d180fd-ba81-4c41-b101-71523958a3a3.png)  
![image](https://user-images.githubusercontent.com/107550671/209162598-c78479d3-a816-4bc5-ae4c-d1e94c518ac8.png)  

Необходимо создать форму списка и форму элемента для каждого справочника  

![image](https://user-images.githubusercontent.com/107550671/209163154-a1cb385c-29d8-4db1-8058-efc4fcb0bea6.png)  

Для иерархического справочника необходимо изменить форму элемента, сгруппировать реквизиты, добавить закладки  

![image](https://user-images.githubusercontent.com/107550671/209163501-2a0d7503-bb08-4066-b04c-7f6f015b1504.png)  
  
Продемонстрируйте изменения в интерфейсе в режиме предприятия скриншотами  

![image](https://user-images.githubusercontent.com/107550671/209163664-fe881b3d-1111-47ad-a723-f4c4b1439d37.png)  
![image](https://user-images.githubusercontent.com/107550671/209163717-6b88f48f-378b-4982-890d-e1806a7b9d3a.png)  
  

Необходимо создать внешнюю обработку для автоматического заполнения иерархического справочника. Используйте генератор случайных чисел  

![image](https://user-images.githubusercontent.com/107550671/209165373-5d121817-1232-4186-98da-3bd8fa2315ae.png)  
![image](https://user-images.githubusercontent.com/107550671/209165410-529985dd-f189-4033-b14d-38369a821fbe.png)  

Добавьте в обработке кнопку “УдалитьЭлементы”, а в ее обработчике напишите программный код, удаляющий сгенерированные прежде элементы из всех групп иерархического справочника. Для этого потребуется использовать методы НайтиПоНаименованию, ПолучитьОбъект, Удалить.  

![image](https://user-images.githubusercontent.com/107550671/209165479-2884c4fc-2d56-465e-9623-df9697bfdf90.png)  
![image](https://user-images.githubusercontent.com/107550671/209165517-7fdd1d36-2139-4b7c-904d-fa0c44782fce.png)  
![image](https://user-images.githubusercontent.com/107550671/209165571-13a08db3-2175-46a2-a028-e8f9d1b91c57.png)  
  

Выгрузите в git информационную базу (dt) и файл внешней обработки. Скриншоты также добавьте в репозиторий.  
