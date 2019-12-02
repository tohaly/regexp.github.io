# Валидация на регулярке
*Актуальная версия: v 0.0.5*

## Опсиание 
Пример формы с использованием регулярных выражений для валидации.


#### Валидация имени
- только кириллица
- первая буква заглавная
- можно ввести от 2 до 20 символов
- возможна запись двойных имён — например "Анна-Мария"

#### Валидация Email
- только латиница
- «собака» `@` — обязательный символ
- точка `.` — обязательный символ
- цифры, подчерк, тире — разрешённые символы

#### Телефон
 - Шаблон для телефона должен находить номера в таких форматах:
```
+7(925)900-90-90
+7(925) 900-90-90
+7 925-900-90-90
+79259009090
89259009090
```

#### Сайт
- нинаться с `http://` или `https://`
- затем `www.` — это необязательная группа
- IP-адрес — `255.255.255.255` или доменное имя — `stasbasov.ru`
- порт — тоже необязательная группа. Порт начинается с двоеточия, за которым идут от 2 до 5 цифр. Например: `:8080`
- путь — последовательность из цифр, слешей и латинских букв, на конце которого может стоять решётка `#`

## Планы

Придать проекту уникальный внешний вид.

## Ссылка на проект
https://tohaly.github.io/regexp.github.io/
