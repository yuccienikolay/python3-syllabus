# python3-syllabus

Специально для ПК Энерегия от студентов.



__Дерево проекта__

* `dist` - конечно собранное в один файл приложение
* `docs` - документация
* `src` - раздел с исходным _читаемым_ кодом. 
	* `modules` - раздел с модулями, в котрых содержится _один_ класс привязанный к `../__main__.py`
		* `Syllabus` - модуль для развертывания класса `Syllabus`. `__init__.py` представляет собой загрузчик класса
		* `Teacher` - модуль для развертывания класса `Teacher`. `__init__.py` представляет собой загрузчик класса
	* `__main__.py` - основной файл для запуска через `python3 -B .` в текущей директории
* `tests` - автотесты и примеры работы