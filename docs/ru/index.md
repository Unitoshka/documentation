---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

head:
    - - meta
      - property: "title"
        content: GramIO - Telegram Bot API фреймворк для TypeScript/JavaScript

    - - meta
      - name: "description"
        content: GramIO это TypeScript/JavaScript фреймворк для создания Телеграм ботов. Чтобы начать, вы можете ввести в консоль "npx create gramio bot-dir" и запустить своего бота с помощью "npm run dev". Это всё что вам нужно чтобы начать работать с GramIO.

hero:
    name: "GramIO"
    text: "Создавай ботов с удобством!"
    image:
        src: /logo.svg
    actions:
        - theme: brand
          text: Давайте начнём
          link: /ru/get-started
        # - theme: alt
        #   text: API Examples
        #   link: /api-examples
features:
    - title: Ещё
      details:
    - title: не совсем готов (может быть)
      details:
    - icon: ✨
      title: Легко расширяется
      details: Благодаря нашей системе плагинов и хуков
    - icon: ⚙️
      title: Используется кодо-генерация
      details: Многие части библиотеки кодо-генерируются, что позволяет обновляться быстрее
    - icon: 🛡️
      title: Строгая типизация
      details: Написана на TypeScript с любовью ❤️
    - icon: 🌐
      title: Работает в разных рантаймах
      details: Node.js, Bun, Deno* – на ваш выбор
---

**Deno\*** [имеет проблему с библиотекой undici на Windows](https://github.com/denoland/deno/issues/19532)
