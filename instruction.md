# Инструкция по языку MarkDodw

Новая строка - это олна пустая строка

**Полужирный текст**

*Курсив текст*

## Цитирование
> Первый уровень
>> Второй уровень

## Списки
### Ненумерованные списки
* Лист 1
* Лист 2
### Нумерованные списки
1. Лист 1
2. Лист 2
3. List three

## WEB ссылки
Текст [пример ссылки](http.example.com "Всплывающая подсказка")
# Инструкция по работе с удаленными репозитариями

## Основы работы с удаленным репозиторием:

**git clone** — создание копии (удаленного) репозитория

Для начала работы с центральным репозиторием, следует создать копию оригинального проекта со всей его историей локально.

Клонирует репозиторий, используя протокол http:
```sh
git clone http://user@somehost:port/~user/repository/project.git
```