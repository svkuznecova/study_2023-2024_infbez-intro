---
## Front matter
lang: ru-RU
title: Лабораторная работы №3
subtitle: Дискреционное разграничение прав в Linux. Два пользователя
author:
  - Кузнецова С. В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date:  15 марта  2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Кузнецова София Вадимовна
  * Российский университет дружбы народов

:::
::: {.column width="30%"}

:::
::::::::::::::

# Ход работы

## В установленной операционной системе создаём учётную запись пользователя gest

![Учётную запись пользователя gest](image/1.jpg){#fig:001 width=70%}

## Аналогично создаём второго пользователя gest2.

![Учётную запись пользователя gest2](image/2.jpg){#fig:002 width=70%}

## Добавляем пользователя gest2 в группу gest

![Добавление пользователя gest2 в группу gest](image/3.jpg){#fig:003 width=70%}

## Вход в систему от пользователей gest и gest2 в разных консолях

![Вход в систему от пользователя gest](image/4.1.jpg){#fig:04.1 width=50%}

![Вход в систему от пользователя gest2](image/4.2.jpg){#fig:04.2 width=50%}

## Команда pwd
	
![Команда pwd](image/5.1.jpg){#fig:05.1 width=50%}

![Команда pwd](image/5.2.jpg){#fig:05.2 width=50%}

## Уточняем имя пользователя, его группу, кто входит в неё и к каким группам принадлежит он сам. Команды groups gest и groups gest2 и  id -Gn и id -G.

![Имя пользователя, его группа](image/6.1.jpg){#fig:06.1 width=50%}

![Имя пользователя, его группа](image/6.2.jpg){#fig:06.2 width=50%}

## Просматриваем файл командой cat /etc/group.

![Команда cat /etc/group](image/7.jpg){#fig:007 width=70%}

## Команда newgrp gest

![Команда newgrp gest](image/8.jpg){#fig:008 width=70%}

## Изменяем права директории /home/gest, разрешив все действия для пользователей группы

![Команда chmod g+rwx /home/gest](image/9.jpg){#fig:009 width=70%}

## От имени пользователя gest снимаем с директории /home/guest/dir1 все атрибуты командой chmod 000 dir.

![Команда chmod 000 dir](image/10.jpg){#fig:010 width=70%}

## Таблица

![Таблица 3.1](image/11.jpg){#fig:011 width=70%}

# Выводы

Получила практические навыки работы в консоли с атрибутами файлов для групп пользователей.

## {.standout}

Спасибо за внимание!
