# 🧹 Unreal Demo Fucker

![Made with C++](https://img.shields.io/badge/Made%20with-C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Platform Windows](https://img.shields.io/badge/Platform-Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen?style=flat-square)
![Game](https://img.shields.io/badge/Game-CS%201.6-orange?style=flat-square)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=FF3333&center=true&vCenter=true&width=500&lines=Unreal+Demo+Fucker;Clean+.dem+files+from+UDS+detects;Made+for+CS+1.6" alt="Typing SVG" />
</p>

---

## 📑 Меню

- [🤔 О чём тут](#-о-чём-тут)
- [⚡️ Что убирает](#-что-убирает)
- [🚀 Как юзать](#-как-юзать)
- [❓ Что осталось за бортом](#-что-осталось-за-бортом)
- [🙏 Респект](#-респект)
- [⚠️ Дисклеймер](#-дисклеймер)

---

## 🤔 О чём тут

**UDF** — консольная утилита для очистки демо-файлов Counter-Strike 1.6 от следов, которые находит сканер [UnrealDemoScanner](https://github.com/UnrealKaraulov/UnrealDemoScanner).

Работает по принципу "вставил лог → нажал 2 → готово". Не палит демку и не ломает её воспроизведение в игре.

---

## ⚡️ Что убирает

| Категория | Детекты |
|---|---|
| 🎯 **AIM** | AIM TYPE 5.1 / 5.4 / 5.5 / 5.7 / 5.8, AIM TYPE 7.2, AIM TYPE 8.2, AIM TYPE 11 (BETA) |
| 🦆 **DUCK** | DUCK HACK TYPE 1, TYPE 3, TYPE 5.1 |
| 🏃 **MOVEMENT** | MOVEMENT HACK TYPE 1, TYPE 2, FORWARD HACK TYPE 1 |
| 🐇 **BHOP** | BHOP HACK TYPE 1.2, 1.3, 2.1, 2.2 |
| ⬆️ **JUMPHACK** | JUMPHACK TYPE 1, TYPE 2, JUMPHACK HPP |
| 💥 **CMD** | CMD HACK TYPE 2, TYPE 6 |
| 🔫 **WEAPON** | AUTORELOAD TYPE 1 |
| ⏸️ **OTHER** | AIRSTUCK HACK, TIMEHACK TYPE 1.1, THIRD PERSON TYPE 1 |
| 🧾 **CMD BLACKLIST** | UNKNOWN CMD |

---

## 🚀 Как юзать

1. Открой [UnrealDemoScanner](https://github.com/UnrealKaraulov/UnrealDemoScanner) и просканируй свою `.dem`
2. Скопируй **весь лог с детектами** (Ctrl+A → Ctrl+C)
3. Запусти `UDF.exe`
4. Перетащи свою `.dem` в консоль или введи путь вручную
5. Введи `1` → вставь скопированный лог → нажми Enter на пустой строке
6. Введи `2` → жди `=== RESULTS ===`
7. Готово. Рядом появится файл `имя_cleaned.dem`
8. Прогони cleaned-файл через UDS ещё раз для проверки

> [!TIP]
> Если после первого прогона остались детекты — вставь их через `1` и снова нажми `2`. Обычно за 2-3 прогона всё уходит полностью.

---


## ❓ Что осталось за бортом

Метод основан на обнулении фреймов вокруг детекта. Работает практически для всех типов, но **не тестировалось** на:

- NO SPREAD TYPE X
- KNIFEBOT / TRIGGERBOT (AIM 1.x)
- FASTRUN
- NORELOAD
- WHEELJUMP

---

## 🙏 Респект

| Кто | За что |
|---|---|
| **exz666** | сделал этот проект |
| **squizof** | демки для тестирования |
| **hpp forever** | демки для тестирования |
| **UnrealKaraulov** | автор UnrealDemoScanner а точнее бездарь 😂| 

Канал автора: **[t.me/originalHNS](https://t.me/originalHNS)**

---

## ⚠️ Дисклеймер

**Этот проект создан исключительно в образовательных и исследовательских целях.**

**Запрещено:**
1. Использовать очищенные демки для обмана администрации серверов
2. Выдавать результат работы за "честную игру"
3. Использовать против других игроков, читеров или античитов

**Ты соглашаешься, что:**
1. Автор **не несёт ответственности** за баны, разбаны, беспруф-баны или любые последствия
2. Все риски — на тебе
3. Используешь на свой страх и риск
