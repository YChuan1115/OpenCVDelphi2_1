Заголовочные файлы OpenCV 2.1 для Delphi (OpenCV wrapper for Delphi)

Введение
Примеры работы OpenCV являются примерами из курса http://robocraft.ru/page/opencv/ портированными на Delphi. Огромная благодарность создателям данного курса за столь замечательные уроки.
Библиотека OpenCV взята отсюда http://sourceforge.net/projects/opencvlibrary/. Спасибо создателям библиотеки за их труд.

Лицензия
GNU GPL v2

Комментарии к заголовочным файлам
Вместо функции cvCopyImage используйте функцию cvCopy с теми же параметрами.

Комментарии к примерам
Для примеров LoadImage, ImageAA, MouseEvent, ResizeImage, ROI, ROI2 для загрузки картинки по умолчанию скопируйте изображение image0.jpg в папку с откомпилированным exe. Это особенно актуально для Delphi XE и выше который создает exe файл не в корневой папке проекта.
Для примера ROI2 так же необходимо скопировать изображение eye.jpg в папку с откомпилированным exe.

Контакты
По всем вопросам обращайте на мою почту pascal.ilya@gmail.com