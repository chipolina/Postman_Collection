# Postman_Collection

В данной коллекции Postman представлены несколько основных методов, созданных по определенному ТЗ.
Для загрузки файлов необходимо нажать `Import` в основном окне Postman <br> <br>
![image](https://user-images.githubusercontent.com/50044846/125923662-d2a2aa1d-f0fe-4f3e-90c5-ffdb655060e2.png) <br>

Нажать кнопку `Upload Files` <br><br>
Выбрать 2 файла и импортировать их.

В рабочей области Postman изменить значение окружения с `No environment` на `Окружение к тестовому заданию`

![image](https://user-images.githubusercontent.com/50044846/125924007-74a592a2-554a-4378-9e01-6a3d1009cc2e.png)

Для запуска всех сценариев необходимо: <br><br>
Нажать на `***` справа от названия коллекции <br>
Выбрать `Run Collection` <br>
Нажать синюю кнопку `Run` <br><br>
![image](https://user-images.githubusercontent.com/50044846/125924197-5efab75c-92ff-4240-9686-2bc4a76bfcd7.png)



Переменные:

Посмотреть список пременных можно несколькими способами:

Способ 1:
Нажать `Environments`
Выбрать нужное окружение и справа будут видны все созданные на текущий момент переменные с их значениями
![image](https://user-images.githubusercontent.com/50044846/125925561-83d782c3-30dc-4643-aa81-40a6c449bd0c.png)

Способ 2:
Нажать на `знак глаза` справа от выбора Окружения
Далее можно зайти в редактор переменных путем нажатия на кнопку `Edit`, либо просмотреть список и значения переменных на текущий момент.

![image](https://user-images.githubusercontent.com/50044846/125925706-b3e46105-7703-4e22-9a4c-1352f6261235.png)


Переменные, необходимые для первоначального запроса прописаны вручную. <br>
Переменные, полученные из из response записываются в переменные окружения для дальнейшего использования. <br>
Запись значений и создание самих переменных происходит с помощью языка JavaScript в разделе Tests
