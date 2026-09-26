Ausfig12 V5 — OFFLINE WORKING

- Интерфейс без изменений.
- Argon2id хранится локально: argon2-bundled.min.js.
- Нет внешнего CDN для криптографии.
- V5: Argon2id → HKDF-SHA-512 → SUB → SHUFFLE → MIX → AES-256-GCM.
- Расшифровка V4 сохранена.
- Service Worker кэширует все локальные файлы, включая Argon2.
