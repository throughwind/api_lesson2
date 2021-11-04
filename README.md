# Обрезка ссылок с помощью Битли

Скрипт предназначен для обрезки длинных ссылок с помощью сервиса [Bitly](https://bitly.com)

## Как установить

####Перед взаимодействием в API Bitly нужно получить токен.

Токен выглядит как строка наподобие следующей: `17c09e20ad155405123ac1977542fecf00231da7`. Bitly предлагает несколько видов токенов, но для скрипта, хватит `GENERIC ACCESS TOKEN`. Ссылка для генерации токена указана на [странице документации](https://dev.bitly.com).

Python3 должен быть уже установлен. Затем используйте pip (или pip3, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```

## Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков dvmn.org.