# magic_taste.tobacco

Демо: https://denis1011101.github.io/magic_taste.tobacco/

## Воркфлоу клиента
1) Приходит в заведение, садится за столик
2) На столе qr который ведёт на сайт или в телеграм бот
3) Там наше web приложение по сбору заказа
4) Пользователь натыкивает
5) Подходит кальянщик и пользователь может обсудить свой заказ с кальянщиком либо заказать как есть

## Воркфлоу организации
1) Организация регается в нашем веб приложеннии
2) Оплачивает подписку или берёт триал на 30 дней
3) У неё получается свой домен (по примеру YClients)
4) При переходе на свой домен можно натыкать заказ

## Описание

Небольшой прототип на React для подбора микса табака: выбор нескольких вкусов, кальяна и уровня тяги (лёгкая/средняя/тяжёлая). Демо собирается как статическая страница для GitHub Pages из папки docs.

- Главный компонент: [`App`](docs/index.html)
- Файлы фронтенда: [docs/index.html](docs/index.html), [docs/style.css](docs/style.css)
- Лицензия: [LICENSE](LICENSE)

## Как открыть локально
Откройте файл [docs/index.html](docs/index.html) в браузере (или через расширение Live Server в VS Code).

## Публикация на GitHub Pages
1) Commit и push в ветку main.  
2) GitHub → Settings → Pages:  
   - Source: Deploy from a branch  
   - Branch: main, Folder: /docs  
3) Через ~1 минуту страница будет доступна по адресу, который покажет GitHub (обычно https://<username>.github.io/<repo>/).

## Стек
- React 18 (UMD) + Babel Standalone (для удобства, без сборки)
- Чистый HTML/CSS

## Статус
В разработке: кнопка «Сохранить заказ» пока показывает заглушку.
```// filepath: README.md
// ...existing code...
# magic_taste.tobacco

Небольшой прототип на React для подбора микса табака: выбор нескольких вкусов, кальяна и уровня тяги (лёгкая/средняя/тяжёлая). Демо собирается как статическая страница для GitHub Pages из папки docs.

- Главный компонент: [`App`](docs/index.html)
- Файлы фронтенда: [docs/index.html](docs/index.html), [docs/style.css](docs/style.css)
- Лицензия: [LICENSE](LICENSE)

## Как открыть локально
Откройте файл [docs/index.html](docs/index.html) в браузере (или через расширение Live Server в VS Code).

## Публикация на GitHub Pages
1) Commit и push в ветку main.  
2) GitHub → Settings → Pages:  
   - Source: Deploy from a branch  
   - Branch: main, Folder: /docs  
3) Через ~1 минуту страница будет доступна по адресу, который покажет GitHub (обычно https://<username>.github.io/<repo>/).

## Стек
- React 18 (UMD) + Babel Standalone (для удобства, без сборки)
- Чистый HTML/CSS

## Статус
В разработке: кнопка «Сохранить заказ» пока
