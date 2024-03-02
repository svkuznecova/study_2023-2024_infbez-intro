---
## Front matter
lang: ru-RU
title: Лабораторная работы №2
subtitle: Дискреционное разграничение прав в Linux. Основные атрибуты
author:
  - Кузнецова С. В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date:  1 марта  2024

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

## Guest

![Учётная запись guest](image/1.jpg){ #fig:001 width=70% }

## Вход в систему от имени пользователя guest

![Вход в систему от имени пользователя guest](image/2.jpg){ #fig:002 width=70% }

## pwd и whoami

![Команды pwd и whoami](image/3.jpg){ #fig:003 width=70% }

## id и groups

![Вывод id и вывод команды groups](image/4.jpg){ #fig:004 width=70% }

## uid и gid пользователя
	
![uid и gid пользователя](image/5.jpg){ #fig:005 width=70% }

![Фильтр](image/6.jpg){ #fig:006 width=70% }

## Список поддиректорий директории

![Список поддиректорий директории](image/7.jpg){ #fig:007 width=70% }

## Атрибуты установленные на поддиректориях

![Расширенные атрибуты установленные на поддиректориях](image/8.jpg){ #fig:008 width=70% }

## Команды ls -l и lsattr

![Команда ls -l](image/9.jpg){ #fig:009 width=50% }

![Команда lsattr](image/10.jpg){ #fig:010 width=50% }

## Снятие с директории всех атрибутов

![Снятие с директории всех атрибутов](image/11.jpg){ #fig:011 width=70% }

## Создание файла в директории dir1 и сообщение об ошибке отразилось на создании файла

![Создание файла в директории dir1](image/12.jpg){ #fig:012 width=10% }

![Ошибка](image/13.jpg){ #fig:013 width=10% }

![Ошибка](image/14.jpg){ #fig:014 width=10% }

# Выводы

В ходе выполнения лабораторной работы были приобретены практические навыки работы в консоли с атрибутами файлов, закрепление теоретических основ дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux1.

## {.standout}

Спасибо за внимание!


