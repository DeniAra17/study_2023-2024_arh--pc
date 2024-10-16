---
## Front matter
title: "Отчет по лабораторной работе №3"
subtitle: "Архитектура компьютера"
author: "Арсакаев Дени Умарович"

## Generic otions
lang: ru-RU


## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы
Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.

   
   
# Выполнение лабораторной работы
   
   

## 1. Установка ПО   
   
   
### Скачиваю архив TexLive с оф. сайта   
![..](image/1.png){#fig:001 width=70%}
   
   
Перехожу в папку Downloads и разврхивирую файл   
Перехожу в разархивированную папку /install-tl-20241010   
Запускаю perl script c помощью команды sudo perl ./install-tl --no-interaction   
   
   
![..](image/2.png){#fig:001 width=70%}
   
   
Добавляю /usr/local/texlive/2022/bin/x86_64-linux в свой PATH для текущей и
будущих сессий   


![..](image/3.png){#fig:001 width=70%}



### Скачиваю аривы pandoc и pandos-crossref с Github'a   
![..](image/4.png){#fig:001 width=70%}   
   
   
Перехожу в папку /Downloads и разархивирую скачанные архивы    
![..](image/5.png){#fig:001 width=70%}    
   
   
Далее с помощью команды cp копирую разархивированные папки в /usr/local/bin/   
![..](image/6.png){#fig:001 width=70%}    
![..](image/7.png){#fig:001 width=70%} 
   
   

## Задание   
    
    
Перехожу в папку /report локального репазитория    
![..](image/8.png){#fig:001 width=70%}     
     
     
Компилирую шаблон с использованием Makefile, вводя команду make   
![..](image/9.png){#fig:001 width=70%}
   
   
Проверяю файлы .pdf и .docx  на работоспособность   
Удаляю полученные файлы с использованием Makefile, вводя команду make clean   
![..](image/10.png){#fig:001 width=70%}   
    
    
Открываю report.md используя mousepad и начинаю заполнять работу   
    
    
![..](image/11.png){#fig:001 width=70%}
    
Сохраняю  файл и загружаю на Github    
   
## Задание для самостоятельной работы   
   
Перехожу в директорию lab03/report   
Открываю report.md c помощью mousepad   
Заполняю отчет и удаляю лишнее   
Сохраняю работу и отправляю на Github  


### Меняю название файла с report.md на Lab03ArsakaevDeni  

      
## Выводы
         
В результате выполнения данной лабораторной работы я освоил процедуры
оформления отчетов с помощью легковесного языка разметки Markdown.



::: {#refs}
:::
