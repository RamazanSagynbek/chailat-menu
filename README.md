# CHAILAT — QR-меню ресторана

Электронное меню для ресторана **CHAILAT kitchen & lounge** (Алматы, пр. Жамбыла, 162). Гость сканирует QR-код на столе и открывает меню на телефоне: категории, фото блюд, цены и корзина для подсчёта заказа.

**Живая версия:** https://rinatdidar800-dot.github.io/chailat-menu/

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?logo=githubpages&logoColor=white)

## Возможности
- Три языка: қазақша, русский, English (`i18n.js`)
- Разделы меню с баннерами и фото блюд
- Корзина: гость собирает заказ и видит итоговую сумму
- Сделано mobile-first: меню открывают с телефона
- Статика без сборки и бэкенда, хостинг бесплатный на GitHub Pages

## Структура
| Файл | Назначение |
|---|---|
| `index.html` | Разметка, стили и логика меню (данные блюд, `PHOTO_SETS`, `BANNERS`) |
| `i18n.js` | Переводы на три языка |
| `photos/` | Баннеры и оптимизированные квадратные фото блюд |

Связанный проект: [welcome_site](https://github.com/RamazanSagynbek/welcome_site), сайт-визитка того же ресторана.

---
Реальный проект для заказчика.
