# Коллекция пресетов для ИИ

> Status Github Actions
> 
> ![Status GitHub Pages](https://github.com/my-app-s/ai-presets-hub/actions/workflows/deploy-pages.yml/badge.svg)

Легвесное клиентское веб-приложение для управления коллекцией промтов и пресетов для искусственного интеллекта. Позволяет хранить пользовательские шаблоны локально, быстро копировать их в буфер обмена и мгновенно переходить к диалогу с Gemini.

## 🚀 Особенности

- **Локальное хранение:** Все пресеточные данные сохраняются в `localStorage` браузера и загружаются из `presets.json` при первом запуске.
- **Интеграция с Gemini:** Быстрая кнопка копирования текста промта с одновременным открытием официальной страницы Gemini в новой вкладке.
- **Современный интерфейс:** Полностью адаптивная верстка на чистом Tailwind CSS в темной цветовой гамме.
- **Безопасность:** Защита от инъекций благодаря использованию безопасных методов манипуляции с DOM (`textContent`).
- **Безопасность промтов:** ⚠️ **Важное предупреждение:**
  - **Внешние промты:** Не копируйте непроверенные промты из ненадежных источников (риск Prompt Injection и обхода защитных механизмов ИИ).
  - **Предустановленные промты:** Все зашитые шаблоны в файле `presets.json` перед использованием также требуют вашего личного аудита. Всегда проверяйте содержимое шаблонов перед отправкой в LLM.

## 🛠️ Технологии

- HTML5 / Vanilla JavaScript (ES6+)
- Tailwind CSS

## ⚙️ Установка и запуск

Поскольку проект является полностью клиентским (Static Frontend), для его запуска не требуется сложный бэкенд.

1. Клонируйте репозиторий:
```bash
   git clone https://github.com/your-username/ai-presets-hub.git

```

2. Перейдите в папку проекта:
```bash
cd your-repo-name

```

3. Откройте файл `index.html` в любом современном браузере (или запустите локальный сервер, например, с помощью расширения Live Server в VS Code).

## Disclaimer & License

* **Short Disclaimer (EN)**: Materials are provided ***as is*** under the LICENSE file. No warranties. Authors are not liable for damages. No partnership or obligations created.
* **Short Disclaimer (RU)**: Материалы предоставляются ***как есть*** и регулируются файлом LICENSE. Гарантий нет. Автор(ы) не несут ответственности за убытки. Партнёрство или обязательства не создаются.
* **Full Disclaimer**: Read the full text in the [DISCLAIMER](./DISCLAIMER.md) (Available in EN/RU).
* **License**: This project is dual-licensed:
  * **Open Source**: Licensed under the [GNU AGPLv3](./LICENSE).
  * **Commercial**: A separate proprietary commercial license is required for proprietary, closed-source, or enterprise use that does not comply with AGPLv3 terms. Contact the copyright holder for commercial licensing.

## Author & Contacts

* **GitHub**: [@my-app-s](https://github.com/my-app-s)
* **LinkedIn**: [In/my-app-s](https://www.linkedin.com/in/my-app-s)
* **Mail**: [myapps.mre.dev@gmail.com](mailto:myapps.mre.dev@gmail.com)
