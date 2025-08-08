<p align="center">
	<img src="logo.png" width="376" height="128" alt="Winlator Logo" />  
</p>

<p align="center">
	<a href="README.md">🇺🇸 English</a>
</p>

---

# 🪟 Winlator

**Winlator** — это мощное Android-приложение, позволяющее запускать приложения и игры для Windows (x86_64) на вашем устройстве с помощью **Wine** и **Box86/Box64**.

---

## 📥 Установка

1. 📦 Скачайте последнюю версию APK (**Winlator_7.1.apk**) с [страницы релизов](https://github.com/Tenn888/Winlator/releases)
2. 📲 Установите и откройте приложение
3. ⏳ Дождитесь окончания процесса установки окружения

---

## 🎥 Видеодемонстрации

Нажмите на изображение, чтобы посмотреть видео:

[![Смотреть на Youtube](https://img.youtube.com/vi/8PKhmT7B3Xo/1.jpg)](https://www.youtube.com/watch?v=8PKhmT7B3Xo)
[![Смотреть на Youtube](https://img.youtube.com/vi/9E4wnKf2OsI/2.jpg)](https://www.youtube.com/watch?v=9E4wnKf2OsI)
[![Смотреть на Youtube](https://img.youtube.com/vi/czEn4uT3Ja8/2.jpg)](https://www.youtube.com/watch?v=czEn4uT3Ja8)
[![Смотреть на Youtube](https://img.youtube.com/vi/eD36nxfT_Z0/2.jpg)](https://www.youtube.com/watch?v=eD36nxfT_Z0)

---

## 💡 Полезные советы

- ⚙️ Если наблюдаются проблемы с производительностью, попробуйте изменить **пресет Box86/Box64** в  
  **Настройки контейнера → Вкладка "Дополнительно"**

- 🧩 Для работы приложений, использующих **.NET Framework**, установите **Wine Mono**  
  *(Пуск → Системные утилиты)*

- 🎮 Если старые игры не запускаются, добавьте переменную окружения:  
  `MESA_EXTENSION_MAX_YEAR=2003`  
  *(Настройки контейнера → Переменные окружения)*

- 🛠️ Запускайте игры через ярлыки на главном экране Winlator — можно задать индивидуальные настройки для каждой игры

- ⚡ Для ускорения установок попробуйте изменить пресет Box86/Box64 на **Intermediate**

---

## 🧩 Зависимости и благодарности

**Используемые компоненты:**

- 🐧 Ubuntu RootFs ([Focal Fossa](https://releases.ubuntu.com/focal))
- 🍷 Wine ([winehq.org](https://www.winehq.org/))
- 📦 Box86/Box64 от [ptitseb](https://github.com/ptitSeb)
- 🔒 PRoot ([proot-me.github.io](https://proot-me.github.io))
- 🎨 Mesa (Turnip, Zink, VirGL) ([mesa3d.org](https://www.mesa3d.org))
- ⚡ DXVK ([github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk))
- 🎮 VKD3D ([gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d))
- 🕹️ D8VK ([github.com/AlpyneDreams/d8vk](https://github.com/AlpyneDreams/d8vk))
- 🚀 CNC DDraw ([github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw))

**Особая благодарность:**

- 💡 [ptitSeb](https://github.com/ptitSeb) — за Box86/Box64
- 🧪 [Danylo](https://blogs.igalia.com/dpiliaiev/tags/mesa/) — за Turnip
- 🛠️ [alexvorxx](https://github.com/alexvorxx) — за полезные модификации
- ❤️ Всем, кто поддерживает и верит в проект Winlator!

---
