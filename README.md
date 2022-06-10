Тестирование API

Вспомните, какого важного элемента разработки и тестирования сайта мы ещё не коснулись? Верно, это API! 

В этом спринте вам предстоит хорошо потрудиться, чтобы написать хорошие тесты для тестирования API всем известной социальной сети. 
Скорее приступайте!

			                            Объекты тестирования третьей недели: JSON и API
 

JSON

1.     Скачайте и установите Nodepad++ или Sublime Text (для пользователей macOS недоступен Notepad++. 
        Ориентируйтесь на свою ОС, предложенные программы близки по функциональности)/

	- Добавьте плагин для работы с JSON.
	- Перейдите по ссылке https://jsonplaceholder.typicode.com/posts.
	- Сохраните данные в файл *.json или *.txt (или любой другой удобный вам формат).
	- Замените текущее значение у ключа title на значение введите какой-нибудь уникальный текст для всех userId.
	- Приложите итоговый файл.
		  json_1.json
		
2.     Скачайте и установите Postman, если вы ещё этого не сделали.

{
    "key1": "data",
    "key2": 123;
    "key3": ,
    "key4": "type 44"
    "task":
    {
        "key5": "OOO "РТК ИТ""
        "key6": true
        "key6": 'info',
    }
    "user": [
        {
            "key8": ["text1"; "text2", "text3"]
            "key9": "number",
        },
       {
            "key8": "text";
            "key9": null
        }
    ]
}
Исправьте все ошибки в теле POST-запроса (формат JSON) и приложите скриншот получившегося результата.

![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/json_2.typeOfData2.png)

Перечислите тип данных у каждого ключа в теле запроса из предыдущего пункта. Пример: "key1: string"
		  json_2.typeOfData.txt
 

 API

Ознакомьтесь с описанием API.

Предоставьте скриншот из postman (обязательно отображение запроса и ответа) и vk по каждому заданию ниже:

1.     Создайте пустой альбом для фотографий https://dev.vk.com/method/photos.createAlbum.
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_1.Create.png)
2.     Загрузите две фотографии в альбом.
		The first photo:
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_2.1.UploadPhoto.png)
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_2.2.UploadPhoto.png)
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_2.3.SavePhoto.png)
		The second photo:
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_2.1.UploadPhoto2.png)
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_2.2.UploadPhoto2.png)
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_2.3.SavePhoto2.png)
3.     Получите список фотографий в альбоме.
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_3.1.GetList.png)
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_3.2.GetList.png)
4.     Добавьте к каждой фотографии по одному разному комментарию.
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_4.1.AddComment-1.png)
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_4.2.AddComment-2.png)
5.     Отредактируйте комментарий у одной фотографии.
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_5.EditComment.png)
6.     Удалите одну фотографию.
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_6.DeletePhoto.png)
7.     Удалите альбом.
	![Image alt](https://github.com/EugeneVovk/Internship-Sprint-3/raw/main/img/api_7.DeleteAlbum.png)
	
	https://loom.com/share/2a53785729fd419185f6205ca7bea5b7
