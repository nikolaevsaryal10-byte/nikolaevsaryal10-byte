<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14,24,36&height=220&section=header&text=AltzGamerz&fontSize=56&fontAlignY=36&desc=Projects%20%E2%80%A2%20Tech%20Notes%20%E2%80%A2%20Hackathons&descSize=18&descAlignY=62" width="100%" alt="AltzGamerz Header" />

<a href="https://github.com/nikolaevsaryal10-byte">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+AltzGamerz+(@nikolaevsaryal10-byte)+%F0%9F%91%8B;Personal+archive+%26+project+reports;Just+doing+what+I+enjoy;FastAPI+%E2%80%A2+Kotlin+Compose+%E2%80%A2+Go+%E2%80%A2+Tailwind" alt="Typing SVG" />
</a>

<br/>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=nikolaevsaryal10-byte&color=009688&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Focus-High--Performance%20Networks-blueviolet?style=for-the-badge&logo=wireguard&logoColor=white" alt="Focus" />
  <img src="https://img.shields.io/badge/Flagship-TabisVPN-0061A4?style=for-the-badge&logo=shield&logoColor=white" alt="Project" />
</p>

</div>

---

### 📝 About Me / Обо мне

> *"Просто личный репортаж о проектах, экспериментах и том, что интересно пробовать на практике."*

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaXpsaHlpdHFvdm5xcXNycXo5dnVjcWs5anBndzkyMzk5aGhrNnR3dSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/IKFVtPf8jP6KJH16dB/giphy.gif" width="480" alt="Anime Vibe" />
</p>

- 🛡️ **[TabisVPN](https://github.com/nikolaevsaryal10-byte/tabisvpn)** — проект экосистемы сетевого туннелирования (Android, Windows, Web, Backend).
- ⚡ **Используемый стек в проектах:** бэкенды (**Python / FastAPI**), мобильные клиенты (**Kotlin / Jetpack Compose**), сетевые компоненты (**Go Xray-core / C HEV tunnel**) и веб-страницы (**Tailwind CSS / ES6+**).
- 🔐 **Интерес к сетевым темам:** протоколы обхода DPI-фильтрации, VLESS / Reality / XTLS, Hysteria 2 (QUIC), маршрутизация Tun2Socks, криптография Argon2id и AES-256.
- 📍 **GitHub:** [@nikolaevsaryal10-byte](https://github.com/nikolaevsaryal10-byte) &nbsp;|&nbsp; **Никнейм:** `AltzGamerz`

---

### 🚀 Проект: [TabisVPN](https://github.com/nikolaevsaryal10-byte/tabisvpn)

<div align="center">
  <img src="https://img.shields.io/badge/Android-Kotlin%202.x%20%7C%20Compose-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Backend-FastAPI%20%7C%20Uvicorn-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Web-TailwindCSS%20%7C%20ES6+-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Core-Go%20%7C%20Xray%20%7C%20C%20HEV-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Protocols-VLESS%20%7C%20Hysteria%202-FF6F00?style=for-the-badge&logo=cloudflare&logoColor=white" />
</div>

<br/>

**TabisVPN (ТАБЫС)** — проект защищённого сетевого туннелирования. Включает мобильный клиент, десктопное приложение, бэкенд с автоматизированным биллингом и веб-интерфейсы.

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaXpsaHlpdHFvdm5xcXNycXo5dnVjcWs5anBndzkyMzk5aGhrNnR3dSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/1448TKNMMg4BFu/giphy.gif" width="480" alt="Anime Project Vibe" />
</p>

#### 🌐 1. Frontend & Web Touchpoints (Веб-интерфейсы)
- **Технологический стек:** Modern HTML5, Tailwind CSS, Vanilla JavaScript (ES6+ async/await, Fetch API), Google Fonts, QRious.
- **Архитектура и компоненты:**
  - **Landing & Download Portal (`index.html`, `/android`, `/windows`, `/ios`):** Mobile-First лендинг с тёмной/светлой темой, стеклянными карточками (Glassmorphism), анимацией и скачиванием дистрибутивов.
  - **User Cabinet (`profile/auth`, `profile/`):** Личный кабинет пользователя с просмотром подписки, таймером активности, интеграцией чекаута ЮKassa, генерацией QR-кодов и live-чатом.
  - **Admin Dashboard (`admin/`):** Административная панель: метрики в реальном времени, мониторинг нод сервера, учёт трафика, управление клиентами и логи.

#### ⚙️ 2. Backend & Core Services (Серверная часть и демоны)
- **Технологический стек:** Python 3.11+, FastAPI, Uvicorn ASGI Server, SQLite3 с оптимизацией WAL (`PRAGMA journal_mode=WAL`), Pydantic v2, Cryptography (Argon2id, AES-256-GCM, HMAC-SHA256).
- **Архитектура сервисов и микромодулей:**
  - **API Routers (`routers/`):** - `auth.py` — авторизация, генерация OTP, выдача JWT/Bearer-сессий.
    - `profile.py` — управление профилем, генерация клиентских конфигов, интеграция платёжного шлюза.
    - `client.py` — протокол синхронизации мобильных клиентов, валидация ключей доступа.
    - `admin.py` — управление пулом пользователей, ручное продление, аналитика и статистика.
  - **Автономные фоновые демоны (`services/`):**
    - `billing_service.py` — автоматический контроль сроков подписок, grace-периоды, сверка платежей.
    - `traffic_service.py` — сбор и агрегация сетевого трафика из системных журналов (`journalctl`) Hysteria 2.
    - `xray_service.py` — динамическая генерация конфигураций Xray-core и балансировка нагрузки.
    - `email_service.py` — асинхронная отправка email-уведомлений, чеков и одноразовых кодов (SMTP).
  - **Платёжная инфраструктура:** ЮKassa API с криптографической проверкой вебхуков и автоматической фискализацией чеков (54-ФЗ / 422-ФЗ).

#### 📱 3. Mobile Client / Android (Мобильный клиент)
- **Технологический стек:** Kotlin 2.x, Android SDK 35 (minSdk 24), Jetpack Compose, Material Design 3, Kotlin Coroutines, StateFlow / SharedFlow, Tencent MMKV, OkHttp3 / Retrofit, WorkManager, Gradle Kotlin DSL.
- **Низкоуровневое ядро туннелирования:**
  - **`AndroidLibXrayLite` (Golang / Go Mobile):** Интеграция ядра Xray-core v5 в виде AAR-библиотеки.
  - **`hev-socks5-tunnel` (C / CMake / Android NDK):** C-туннель для перехвата IP-пакетов из `VpnService` и трансляции в SOCKS5/Tun2Socks.
  - **Архитектура UI:** MVVM-архитектура, экраны авторизации, управления серверами, настройки протоколов и встроенный загрузчик обновлений.

#### 🖥️ 4. Desktop Client / Windows (Десктопный клиент)
- **Технологический стек:** Python 3.11+, Tkinter / CustomTkinter, WinINet Windows API.
- **Функциональность:** Управление системным прокси-сервером через реестр Windows, фоновые процессы туннелирования, графический интерфейс подключения.

#### 🛡️ 5. Protocols & Network Routing (Сетевые протоколы и маршрутизация)
- **Протоколы:** **VLESS**, **Trojan**, **VMess**, **Shadowsocks-2022**.
- **Транспорт:** **Hysteria 2** (протокол на базе UDP/QUIC с контролем перегрузок для сетей с потерями пакетов).
- **Маскировка:** **XTLS / Reality** для обхода фильтрации и противодействия активному зондированию (DPI).
- **Маршрутизация:** Раздельное туннелирование (Split Tunneling), обход локальных сетей и доменные правила на базе GeoIP/GeoSite.

#### 🛠️ 6. DevOps & Infrastructure (Инфраструктура и развёртывание)
- **Окружение:** Linux (Ubuntu / Debian Server), Systemd-юниты для работы фоновых служб.
- **Контейнеризация:** Docker, Docker Compose для воспроизводимости и тестирования.
- **Веб-сервер:** Nginx Reverse Proxy (SSL/TLS Let's Encrypt Certbot, HTTP/2, проксирование WebSockets и FastCGI).

---

### 🏆 Хакатоны и соревновательный опыт

| Проект & Событие | Результат | Стек | Описание и технические детали |
|:---|:---|:---|:---|
| 🥈 **Региональный хакатон**<br>*(Сайт-квиз & Мини-CRM)* | **2 место** 🏆 | `Python`, `SQLite`, `JavaScript`, `Tailwind CSS`, `HTML5` | Интерактивная платформа-квиз для организации с внутренней системой учёта заявок (мини-CRM). Реализация проекта в сжатые сроки хакатона в связке с дизайнером и менеджером. |
| 🥉 **Школьный хакатон**<br>**[Tactical Medic Rescue Site](https://github.com/nikolaevsaryal10-byte/tactical-medic-rescue-site)**<br>👉 [Живое демо](https://nikolaevsaryal10-byte.github.io/tactical-medic-rescue-site/) | **3 место** 🏆 | `HTML5`, `CSS3`, `JavaScript`, `WebP`, `Optimization` | Интерактивный экспресс-справочник тактической медицины (навигация по 3 зонам: Красная, Жёлтая, Зелёная, сортировка ранений по анатомическим зонам). **Ключевой вызов:** работа в условиях слабой связи (2G/EDGE). Оптимизация графики (WebP) и минимизация кода — общий вес страницы со всеми схемами составил **всего ~6 МБ**. |

---

### 🔬 Другие проекты и эксперименты

- 👁️ **FaceID School Security System (Система биометрической идентификации)** *Стек:* `Python`, `Computer Vision`, `Face Recognition`, `Web UI`  
  Прототип бесконтактной верификации учащихся на турникетах с детекцией посторонних лиц и интеграцией базы розыска.  
  *Нюанс реализации:* Решение вопроса распознавания азиатских лиц из-за смещения обучающих выборок стандартных моделей, подбор альтернативных моделей эмбеддингов и калибровка векторов признаков.

---

### 💻 Используемые технологии / Tech

<div align="center">
  <img src="https://skillicons.dev/icons?i=kotlin,python,fastapi,go,c,androidstudio,tailwind,js,html,css,sqlite,docker,linux,bash,git,github" alt="Skills Wall" />
</div>

<br/>

| Категория | Технологии и инструменты |
|:---|:---|
| **Языки** | `Kotlin`, `Python 3.11+`, `Go (Golang)`, `C`, `JavaScript (ES6+)`, `Bash / Shell`, `SQL` |
| **Frontend & UI** | `Tailwind CSS`, `HTML5`, `Vanilla JS`, `Jetpack Compose`, `Material Design 3` |
| **Backend & APIs** | `FastAPI`, `Uvicorn (ASGI)`, `Pydantic v2`, `SQLite (WAL mode)`, `RESTful APIs`, `Webhooks` |
| **Android** | `Android SDK`, `Android VpnService`, `Tun2Socks`, `MMKV`, `WorkManager`, `OkHttp3`, `Coroutines` |
| **Сеть & Ядра** | `Xray-core`, `Hysteria 2 (QUIC)`, `VLESS`, `Trojan`, `Shadowsocks`, `XTLS / Reality`, `HEV Tunnel` |
| **Безопасность & Криптография** | `Argon2id`, `AES-256-GCM`, `HMAC-SHA256`, `OAuth2 / Bearer Tokens`, `SSL / TLS 1.3` |
| **Платёжные интеграции** | `YooKassa API`, `Фискализация 54-ФЗ / 422-ФЗ`, `Вебхуки` |
| **Инфраструктура** | `Docker`, `Docker Compose`, `Linux (Debian/Ubuntu)`, `Systemd`, `Nginx`, `Git / GitHub Actions` |

---

### 🛠️ Сетап / Setup & Tools

<div align="center">

<img src="https://img.shields.io/badge/OS-Windows%20%7C%20Linux-0078D6?style=for-the-badge&logo=linux&logoColor=white" alt="OS" />
&nbsp;
<img src="https://img.shields.io/badge/IDE-Android%20Studio%20%7C%20VS%20Code-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white" alt="IDEs" />
&nbsp;
<img src="https://img.shields.io/badge/Tools-Docker%20%7C%20Git%20%7C%20Postman%20%7C%20Termius-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Tools" />

</div>

---

### 📊 Активность / GitHub Analytics

<div align="center">
  <table>
    <tr>
      <td align="center" valign="middle">
        <a href="https://github.com/nikolaevsaryal10-byte">
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=nikolaevsaryal10-byte&theme=tokyonight" alt="Top Languages" />
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://github.com/nikolaevsaryal10-byte">
          <img src="https://streak-stats.demolab.com/?user=nikolaevsaryal10-byte&theme=tokyonight&hide_border=true&background=1a1b27" alt="GitHub Streak Stats" />
        </a>
      </td>
    </tr>
  </table>
</div>

---

### 🤝 Связь / Links

<div align="center">

<a href="https://github.com/nikolaevsaryal10-byte">
  <img src="https://img.shields.io/badge/GitHub-nikolaevsaryal10--byte-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
&nbsp;
<a href="https://t.me/AltzGamerz">
  <img src="https://img.shields.io/badge/Telegram-@AltzGamerz-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
</a>
&nbsp;
<a href="mailto:nikolaevsaryal10-byte@users.noreply.github.com">
  <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<br/><br/>

<img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZGdhdHBzZnpwZnd0aGI0MGJla3dzbXJpeDYzeDVjaGo5aDJteWF2cSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/yALcFbrKshfoY/giphy.gif" width="220" alt="Wave Goodbye" />

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14,24,36&height=120&section=footer" width="100%" alt="Footer" />
</div>
