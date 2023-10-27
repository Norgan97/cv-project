# cv-project 

В данном репозитории представлен проект multipage-приложения с использованием streamlit. 
Над проектом работали: Львов Даниил, Будажапов Дмитрий, Хлапушина Лариса.

Данное приложение решает несколько задач:
        
         1. Детекция объектов с помощьюYOLOv5:
            1.1 Предназначено для детекции опухолей мозга по фотографии.
            ![Опухоль](https://github.com/Norgan97/cv-project/blob/main/опухоль_zlokachestvennaya-opuhol.jpg
            1.2 Для детекции spiderman'а и ironman'а.
            Вы можете загрузить свое фото и приложение выделит область опухоли на снимке или покажет героев комиксов. 
         2. Детекция объектов с помощьюYOLOv8:  
            Используется для детекции ветрогенераторов.
            Вы можете загрузить фото. Наше приложение выделит все изображения ветрогенераторов на вашей картинке. Кроме того, в приложении можно загрузить видео-тест, на котором наша модель также               выделит расположение этих объектов.
         3. Очищение документов от шумов с помощью автоэнкодера:
            Это приложение позволит вам получить чистое изображение загруженного вами фото текста с различными дефектами.

Для запуска представленных приложений на вашем компьютере склонируйте данный репозиторий, загрузите библиотеки из файла requirements.txt и запустите в терминале команду #streamlit run Main.py#
