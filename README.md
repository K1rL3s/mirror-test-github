1. Создать пустую репу на гитхабе
2. Склонировать репу на пк и перейти в неё
    ```
    git clone https://github.com/K1rL3s/mirror-test-github.git
    cd mirror-test-github
    ```
3. Создать какие-то файлики
    ```
    echo Hello, world > README.md
    echo MIT LICENSE 2024 > LICENSE
    ```
4. Приготовить файлики для коммита
    ```
    git add README.md LICENSE
    ```
5. Закоммитить и запушить на гитхаб, \
   где origin - ремоут, master - ветка
    ```
    git commit -m "initial"
    git push origin master
    ```
6. Создать пустую репу на гитлабе
7. Добавил репу в ремоут
    ```
    git remote add gitlab https://gitlab.hackathon.uriit.ru/untitled.py/mirror-test-gitlab
    ```
8. Запушить в гитлаб, \
   где gitlab - название ремоута, master - название ветки
    ```
    git push gitlab master
    ```
9. Вставить эту инструкцию в ридмик, закоммитить её и запушить в оба ремоута
    ```
    git add README.md
    git commit -m "steps"
    git push origin master
    git push gitlab master
    ```
