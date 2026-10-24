<h1 align="center">Антон Пархоменко · <code>lemitz</code></h1>

<p align="center">
  <b>AI-Driven системный разработчик · ИИ-автоматизация · Технический Pre-Sale и продюсер проектов</b><br>
  Проектирую архитектуру и собираю работающий локальный софт, self-hosted системы и утилиты полностью через управление ИИ-моделями.<br>
  <i>Архитектура, ТЗ и контроль — мои. Код — сгенерирован ИИ. Результат — реальные программы на каждый день.</i>
</p>

<p align="center">
  <a href="https://about.kobyla.by"><img src="https://img.shields.io/badge/досье-about.kobyla.by-8b8cff" alt="about.kobyla.by"></a>
  <a href="https://kobyla.by"><img src="https://img.shields.io/badge/система-kobyla.by-e8590c" alt="kobyla.by"></a>
  <a href="https://www.linkedin.com/in/lemitz/"><img src="https://img.shields.io/badge/LinkedIn-in%2Flemitz-0077b5" alt="LinkedIn"></a>
  <a href="https://t.me/LemiTZ"><img src="https://img.shields.io/badge/Telegram-%40LemiTZ-24c8db" alt="Telegram"></a>
  <a href="mailto:hello@kobyla.by"><img src="https://img.shields.io/badge/почта-hello%40kobyla.by-2ea043" alt="Email"></a>
</p>

<p align="center">
  <a href="README.md">English</a> · <b>Русский</b>
</p>

---

### Метод работы (100% AI-Driven разработка)

По первому образованию я лингвист (английский **C2**, немецкий), а **не классический программист, пишущий код руками**. Я не набиваю синтаксис строчка за строчкой — я использую современные ИИ-модели и агентов как полноценный производственный цех («второй мозг»):
- **На моей стороне:** постановка задачи, проектирование клиент-серверной архитектуры и БД, продумывание логики безопасности и UX, сборка билдов, отладка на реальном железе (Orange Pi, Windows, Android, внешние ЦАП) и доведение продукта до релиза.
- **На стороне ИИ:** генерация кода на нужном под задачу стеке (`Kotlin`, `C# / .NET`, `Rust / Tauri`, `Go`, `Flutter`, `TypeScript`) под моим жёстким архитектурным контролем.
- **Результат:** стабильный софт без телеметрии и лишнего мусора, которым я сам пользуюсь каждый день.

### Собранные AI-Driven проекты

| Проект | Стек и платформа | Суть и архитектура | Статус / Релиз |
| :--- | :--- | :--- | :--- |
| **[Rocket](https://github.com/lemitz/Rocket)** | `Go` · `Direct2D` · `Kotlin` *(Windows 10/11 и Android 14+)* | Мгновенная переброска файлов по Wi-Fi («выбрал, сдвинул слайдер, улетело»). Чистый Go без сторонних библиотек на ПК + нативный Kotlin на Android, проверка CRC32C, автопоиск в сети. | [![v0.2.0](https://img.shields.io/badge/release-v0.2.0-8b8cff)](https://github.com/lemitz/Rocket/releases) |
| **[FeatherW8](https://github.com/lemitz/FeatherW8)** | `Kotlin` · `Jetpack Compose` · `Media3` · `C++/JNI` *(Android 9+)* | Лёгкий офлайн-плеер с нативным декодером **DSD (`DSF`/`DSDIFF`) → PCM**, true-black AMOLED интерфейсом, поддержкой 120 Гц и интеграцией под Nothing/realme. Полностью без доступа в сеть. | [![v1.4.1](https://img.shields.io/badge/release-v1.4.1-3ddc84)](https://github.com/lemitz/FeatherW8/releases) |
| **[FeatherW8-CLI](https://github.com/lemitz/FeatherW8-CLI)** | `C#` · `.NET 10` · `ASIO` · `WASAPI Exclusive` *(Windows 10/11)* | Терминальный bit-perfect аудиоплеер (`MP3`, `WAV`, `FLAC`, `Ogg`, `Opus`, нативный `DSD` через ASIO). Создан под внешние ЦАП (FiiO K11) — честная передача потока без ресемплинга и микшера Windows. | [![v1.2.1](https://img.shields.io/badge/release-v1.2.1-0078d4)](https://github.com/lemitz/FeatherW8-CLI/releases) |
| **[MDPad](https://github.com/lemitz/MDPad)** | `Rust` · `Tauri 2` · `TypeScript` · `CodeMirror 6` *(Windows 10/11)* | Мгновенный нативный Markdown-блокнот. Split-превью CommonMark/GFM, автосохранение кодировок (`UTF-8`, `UTF-16`, `Windows-1251`), работа хоткеев по физическим кодам клавиш на русской раскладке. | [![v1.0.3](https://img.shields.io/badge/release-v1.0.3-24c8db)](https://github.com/lemitz/MDPad/releases) |
| **[HomeLAN_2026](https://github.com/lemitz/HomeLAN_2026)** | `Go` · `SQLCipher` · `Flutter` · `WebSockets` *(Orange Pi / Linux / Win / Android)* | Приватный self-hosted LAN-мессенджер со сквозным шифрованием (`X25519` + `ChaCha20-Poly1305`). Аппаратный USB-ключ, пароль принуждения (экстренный вайп БД), синхронизация времени без внешнего NTP. | [![v0.5.0-rc](https://img.shields.io/badge/source-v0.5.0_RC-7f52ff)](https://github.com/lemitz/HomeLAN_2026) |
| **[KOBYLA.BY](https://kobyla.by)** | `Nuxt 3` · `TypeScript` · `Cloudflare Pages` *(Web)* | Интерактивная цифровая система: **122 контентных узла**, граф причинных маршрутов, режим Windows XP и автономные прототипы. Профессиональное досье: **[about.kobyla.by](https://about.kobyla.by)**. | [![live](https://img.shields.io/badge/status-live-2ea043)](https://about.kobyla.by) |

### Ключевые компетенции

- **AI-Driven прототипирование и системная архитектура:** Превращение задач и идей в работающие десктопные, мобильные и серверные приложения за счёт управления ИИ-агентами — от ТЗ и архитектуры до сборки релиза и развёртывания на железе.
- **Автоматизация процессов и внедрение ИИ:** Построение внутренних инструментов (автоматизация отчётности `.docx`), ускорение аналитической обработки данных и генерации контента.
- **Технические коммуникации, Pre-Sale и медиа:** Английский **C2** (EF SET 86/100), немецкий язык, технический копирайтинг и локализация, видеомонтаж (`Premiere Pro`, `Vegas Pro`), органическое продвижение (**300 000+** просмотров на единицу контента).
- **Железо и локальная инфраструктура:** Сборка, диагностика и настройка ПК, одноплатных серверов (Orange Pi), периферии и локальных сетей.
