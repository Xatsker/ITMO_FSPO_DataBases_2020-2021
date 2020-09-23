# ITMO_FSPO_DataBases_2020-2021
Репозиторий для реализации дистанционного обучения по дисциплине "Основы проектирования баз данных" (09.02.07, ФСПО)
========================

[Учебный журнал](https://docs.google.com/spreadsheets/d/1k71sJcYyiZF1uwEFcRt_R7RyZIVw-MtyMmiqFLP4Bm8/edit?usp=sharing) по дисциплине. Здесь доступна информация о сроках сдачи работ, о текущей успеваемости студентов и описаны все материалы, необходимые для реализации курса.

[Лекционные материалы](https://drive.google.com/drive/folders/1-xtMz1V1sXno7OQmVdRXnx1N_Ru-Lrze?usp=sharing)

[Лабораторные работы](https://drive.google.com/open?id=1p1iBROaV6hcRC9uCLMxAdRDz01V6qCMv) - задания, оцениваемые преподавателем.

[Практические задания](https://drive.google.com/open?id=1sUM8PVWfFH3-Cg_NFGrEplNCZx3cZV3r) - задания, которые необходимо выполнить перед выполнением лабораторной работы для того, чтобы освоить тему.

## Лабораторная работа №1

Лабораторная работа №1 выполняется в ErwinProcessModeler. Два варианта установки: новая версия с оффициального сайта и получение студенческой лицензии, либо использование триальной версии. Скачивание старой версии с гугл диска.

Практические задания и лабораторные работы можно выполнять в группах до двух человек.

#### Практическая часть 1
Реализовать idef0 модель работы автомойки.
Желательно в [этой](https://creately.com/diagram/example/i8r0q06q1/New%20IDEF0) программе.
Пример [тут](https://drive.google.com/file/d/1B2gukd5gE6f3jBcs9tSYxR77K8vEOYSe/view?usp=sharing)

Отчет о практической части содержит PDF/JPEG-файл с вашей функциональной моделью и отправляется пул реквестом в этот репозиторий в папку Pr0_idef0 **(Пример  students/k3340/Petrov_Vasya/Pr0_idef0 )**. Шаблон названия пул реквеста "ИТМО ФСПО Номер_группы Практическая работа ФИО". Пример: "ИТМО ФСПО К3340 Практическая работа №1 Филимонов Филипп". 

#### Практическая часть 2
Перед выполнением задания необхордимо выполнить практикум в соответствии с инструкциями из папки "Практические работы".
После выполнения заданий, указанных в тексте практикума, составить функциональную модель, по одному из вариантов рассмотренных на занятии. Варианты:

- *Процесс производства меховых шуб. В процессе существуют заказы, проекты, подбор материалов, рассчет материалов, заказ материалов, рассчет производственных мощностей, поставка товара, производство.*

- *Процесс заказа товара в интернет магазине. Выбор - заказа - оформление доставки - доставка - получение.*

(лекция) Пример и объяснение того, как сделать функциональную модель, можно посмотреть [тут](https://www.youtube.com/watch?v=flGjJMsjnG0)

Отчет о практической части содержит PDF-файл с вашей функциональной моделью и отправляется пул реквестом в этот репозиторий в папку **students/k3340/Petrov_Vasya/Pr1_dfd**. Шаблон названия пул реквеста "ИТМО ФСПО Номер_группы Практическая работа ФИО". Пример: "ИТМО ФСПО К3340 Практическая работа №1 Филимонов Филипп". 

#### Лабораторная часть

Лабораторная работа выполняется в соответствии с [заданием](https://drive.google.com/file/d/0B7AOfG5ohMyAVTJQQ0RsU0c1eTg/view?usp=sharing). При желании необходимо объединиться в группы и обратиться к преподавателю, написав ему в социальной сети ["Вконтакте"](https://vk.com/govorof) для получения варианта.
Для сдачи работы необходимо сделать презентацию и защитить ее преподавателю на консультации. Подробнее задание описано в тексте работы.

### Сдача работы №1

На гит должен быть загружен пдф файл с моделью, презентация в пдф, ервин файл. Пул реквест должен содержать информация о варианте.

## Сдача работ

Для сдачи работы в связи с переходом на дистанционную форму обучения введены дополднительные правила игры.

Все отчеты сохраняются в **pdf** (документы и презентации).

Все студенческие работы хранятся в папке **Students**
Для сдачи работы необходимо:
1. Зарегиться на гите.
2. Сделать форк репозитория с заданиями в свой аккаунт (на странице https://github.com/TonikX/ITMO_FSPO_DataBases_2020-2021 кнопка fork справа, сверху).
3. Установить гит на компьютер.
4. Открыть папку, где хранятся Ваши проекты. В контекстом меню нажать "Open Git Bash here". Склонировать форкнутый репозиторий на компьютер (git clone https://github.com/ваш аккаунт/ITMO_FSPO_DataBases_2020).
5. В файловой системе Вашего компрьютера, в склонированном репозитории создать в папке students/группа Вашу личную папку в формате Фамилия_Имя латиницей (Пример **students/k3340/Petrov_Vasya**).
6. В личной папке сделать подпапку с текущей работой в формате lr_номер (Пример **students/k3340/Petrov_Vasya/Lr1**).
7. Записать в папку отчетные материалы.
8. Сделать коммит, описать его адекватно (Пример "был добавлен файл перезентация_петров.pdf"). Набрать команлы git add и git commit -m "название комита".
9. Сделать push в Ваш форкнутый репозиторий (git push).
10. Сделать пул-реквест в мой репозиторий из вашего форкнутого, описать его адекватно.
Пока пользуйтесь [этой](https://vk.com/@efimchik_post_edu-tfm-2019-1) инструкцией, у нас нет веток с заданиями, как тут, но Вам поможет. Скоро запишу ролик.
Все работы сдаются средствами создания Pull Requests в папку students в этом репозитории.
**Прошедшие работы тоже необходимо запулреквестить.**

Еще один мануал о том, как сделать Pull Request, описан [тут](https://rustycrate.ru/%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%B0/2016/03/07/contributing.html).


