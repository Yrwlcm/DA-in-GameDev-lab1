# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Холстинин Егор Алексеевич
- РИ220943
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Написать программу Hello World на Python с запуском в Jupiter Notebook.
- Задание 2.
- Написать программу Hello World на C# с запуском на Unity. 
- Задание 3.
- Оформить отчет в виде документации на github (markdown-разметка).
- Выводы.
- ✨Magic ✨

## Цель работы
Установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.
Ход работы:
- Скачать дистрибутив анаконды с сайта anaconda.com
- Открыть Anaconda.Navigator
- Открыть Jupyter Notebook
- Создать новый файл HelloWorld.ipynb
- Написать в файле

```py
print('Hello World')
```
- Запускаем

![image](https://github.com/Yrwlcm/DA-in-GameDev-lab1/assets/99079920/a1c1a877-7cdd-4e8a-87f7-ab5707ada16f)

## Задание 2
### Написать программу Hello World на C# с запуском на Unity. 

Ход работы:
- Скачать установщик Unity с сайта unity.com
- Регестрируем аккаунт
- Создаем новый пустой проект
- Создаем новый обьект Ui -> Text - TextMashPro с текстом Hello World
![image](https://github.com/Yrwlcm/DA-in-GameDev-lab1/assets/99079920/31c16656-27eb-47c7-82a9-d2787ea33ea4)
- Создаем новый скрипт с названием HelloWorldScript
- Внутрь скрипта пишем
``` C#
using System;
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class HelloWorldScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        Debug.Log("Hello world!");
    }
}
```
- Привязываем его к обьекту Canvas
![image](https://github.com/Yrwlcm/DA-in-GameDev-lab1/assets/99079920/99f4ad08-3f28-4b35-8e32-0d6b4593fd57)

- Теперь при запуске программы на экране будет надпись Hello World и в консоль будет выведено Hello World
![image](https://github.com/Yrwlcm/DA-in-GameDev-lab1/assets/99079920/6e320b91-e4c3-4716-8e3e-6de24ca6a482)

## Задание 3
### Оформить отчет в виде документации на github (markdown-разметка).

- Открыть репозиторий с лабораторной работой
- Создать его клон с помощью Fork
- Оформить отчет

## Выводы

В ходе этой лабораторной работой, я установил Anaconda и Unity на свой ПК и познакомился с основами работы с ними.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
