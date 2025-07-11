[🌐 Версия на испанском](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README.md) | [🌐 Английская версия](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README-ENGLISH.md)

[🖥️ Безопасный и быстрый хостинг n8n](https://djar.co/hostingn8n)

# 🧠 Коллекция рабочих процессов n8n

Этот репозиторий является **форком** оригинальной инициативы [@Zie619](https://github.com/Zie619/n8n-workflows), который собрал рабочие процессы n8n из различных источников, таких как:

- официальный сайт [n8n.io](https://n8n.io/) и его форум сообщества;
- примеры, общедоступные на GitHub, в блогах и на других сайтах.

Цель репозитория — предоставить консолидированный ресурс, который вдохновит вас, упростит обучение и позволит повторно использовать рабочие процессы в ваших собственных проектах n8n.

## 📂 Внесённые улучшения

- **Описания на английском**. Каждый файл `.json` был проанализирован, и на основе выполняемых действий ему было дано понятное описание на английском языке.
- **Удаление дубликатов**. Уникальный хэш каждого файла проверен и подтверждён, что позволило обнаружить и удалить дублирующиеся рабочие процессы и гарантировать уникальность каждого из них.
- **Переименование файлов**. Названия файлов обновлены так, чтобы точнее отражать их основную функциональность и облегчить поиск.

## 🛠 Инструкция по использованию

Чтобы импортировать любой рабочий процесс в свою инстанцию n8n, выполните следующие шаги:

1. Откройте свою инстанцию n8n.
2. Нажмите меню «Импорт» (☰ → Import workflow).
3. Выберите нужный файл `.json` из папки `workflows`.
4. При необходимости обновите учётные данные или URL-адреса вебхуков.
5. Сохраните и запустите рабочий процесс.
6. [Если вы не находите нужный рабочий процесс, используйте этот Custom GPT, который поможет его найти или решить проблемы с n8n.](https://chatgpt.com/g/g-6840a79abd348191966dd06abd7236c8-asistente-de-flujos-n8n)
7. Также можно общаться с этим репозиторием по адресу [https://gitmcp.io/DragonJAR/n8n-workflows-es/chat](https://gitmcp.io/DragonJAR/n8n-workflows-es/chat)

## 🖥️ MCP Server (Model Context Protocol)

MCP-сервер для этого репозитория, позволяющий взаимодействовать с большой базой задокументированных рабочих процессов n8n:

`https://gitmcp.io/DragonJAR/n8n-workflows-es`

[Здесь вы найдёте инструкции по использованию в Cursor, Claude Desktop, Windsurf, VSCode, Cline или Highlight AI](https://gitmcp.io/DragonJAR/n8n-workflows-es).

## 🤝 Вклад

Если вы нашли интересный рабочий процесс или разработали его сами, не стесняйтесь внести его в эту коллекцию! Помните только:

- **Описательное имя**. Выбирайте такое имя файла, которое ясно отражает основную функцию рабочего процесса.
- **Указание источника**. Если рабочий процесс взят из другого места, добавьте в начале файла небольшой комментарий с указанием его происхождения.

Чтобы предложить изменения, отправьте Pull Request с новым рабочим процессом или улучшением.

## ⚠️ Предупреждение

Все размещённые здесь рабочие процессы предоставляются «как есть». **Перед использованием в продакшене обязательно протестируйте их в контролируемой среде.** Убедитесь, что вы полностью понимаете каждый узел, учётные данные и связи, чтобы избежать возможных ошибок или проблем с безопасностью.

## 📋 Список рабочих процессов

- [0001-nostr-damus-ai-report.json](workflows/0001-nostr-damus-ai-report.json) Описание: этот автоматизированный процесс анализирует контент Nostr с хештегом #damus с помощью языковых моделей, формирует отчёты и отправляет результаты по электронной почте и в Telegram.
*Перевод остальных описаний пока не готов.*
