# Создание окружения

## Codelab

Зайти на [Codelab](https://colab.research.google.com/)

    (залогиниться), 
    выбрать GitHub, вставить линк к файлу в репо example: https://github.com/Letch49/ML_VVSU_2023/blob/main/lec01/lec01.ipynb

    ну или создать тетрадку самому :)

## Linux, MacOS, WSL, Windows

    Скачать [python](https://www.python.org/downloads/)

    # создаем виртуальное окружение
    python3 -m venv env
    
    #активируем
    source env/bin/active

    # устанавливаем зависимости из репо https://github.com/Letch49/ML_VVSU_2023/blob/main/requirements.txt

    pip3 install -r requirements.txt

    # запускаем среду jupyter
    jupyter-lab
