# Первичные технические источники

Проверены при подготовке 10.10.2026; совместимость и версии повторно проверить перед реализацией/выпуском. Функциональные сценарии, палитры, лимиты и архитектура — проектные решения, не факты из источников.

- S01. WebKit: [Web Push for Web Apps on iOS and iPadOS](https://webkit.org/blog/13878/web-push-for-web-apps-on-ios-and-ipados/) — Home Screen, iOS 16.4, запрос разрешения после пользовательского действия.
- S02. OpenAI: [Custom instructions with AGENTS.md](https://developers.openai.com/codex/guides/agents-md) — проектные инструкции; при проверке перенаправлялся на официальный ChatGPT Learn.
- S03. MDN: [getUserMedia](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia) — защищённый контекст, разрешение микрофона, ошибки.
- S04. MDN: [SpeechRecognition](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition) — особенности доступности браузерного распознавания.
- S05. MDN: [MediaRecorder.isTypeSupported](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder/isTypeSupported_static) — выбор формата в runtime.
- S06. MDN: [Background Synchronization API](https://developer.mozilla.org/en-US/docs/Web/API/Background_Synchronization_API) — ограниченная поддержка, не универсальный механизм.
- S07. W3C: [WCAG Contrast Minimum](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html) — 4,5:1 для обычного и 3:1 для крупного текста.
- S08. MDN: [prefers-reduced-motion](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion) — уменьшение движения.
- S09. Socket.IO: [Delivery guarantees](https://socket.io/docs/v4/delivery-guarantees/) — транспорт не заменяет долговечный журнал/replay.
- S10. OWASP: [Password Storage](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html) — дополнительная справка для возможного резервного секрета; обязательный пароль/email в текущую модель не входит.
- S11. SYSTRAN: [faster-whisper](https://github.com/SYSTRAN/faster-whisper) — первичный README прочитан через GitHub; серверный STT, CPU/int8. Ресурсы и скорость замерять отдельно.
- S12. [React Quick Start](https://react.dev/learn) и [Vite Getting Started](https://vite.dev/guide/) — основы предложенного клиентского стека.
- S13. [Fastify documentation](https://fastify.dev/docs/latest/) — предложенный API-сервер.
- S14. [Inter font family](https://rsms.me/inter/) — настоящее семейство UI-шрифта. Файлы шрифта не включены в пакет.
- S15. [Nunito — Google Fonts](https://fonts.google.com/specimen/Nunito) — акцентное семейство. Карточка динамическая; лицензию и кириллицу конкретной версии дополнительно проверить перед включением. Название Nunito Rounded на постере не считать точным.
- S16. PostgreSQL: [Explicit Locking](https://www.postgresql.org/docs/current/explicit-locking.html) — блокировки в транзакциях.
- S17. W3C: [Target Size Minimum](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html) — нормативный минимум и исключения; наши 44–56 px являются отдельной целью удобства.
- S18. MDN: [Manifest icons](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Manifest/Reference/icons) и web.dev [Installation](https://web.dev/learn/pwa/installation) — статические иконки, системная установка.
- S19. MDN: [transform-style](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-style) — preserve-3d и свойства, схлопывающие слои.
- S20. OWASP: [Authentication](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html) — идентификатор не заменяет аутентификацию.
- S21. OWASP: [Session Management](https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html) — управление сессиями.
- S22. OWASP: [Multifactor Authentication](https://cheatsheetseries.owasp.org/cheatsheets/Multifactor_Authentication_Cheat_Sheet.html) — ограничения SMS и способы восстановления/дополнительной защиты.

Пакет не содержит юридического заключения, утверждения о безусловной безопасности SMS или гарантированной доставке push. Даты, случайные цены и названия шрифтов на бренд-постерах не являются источниками требований.
