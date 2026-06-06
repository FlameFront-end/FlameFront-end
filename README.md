<div align="center">
  <img src="assets/Header.gif" alt="header" width="100%" />
</div>

<br />

<div align="center">
  <h1>Artem Kaliganov</h1>
  <p><strong>Senior Frontend Developer</strong></p>
  <p>AI SaaS · Real-time Systems · React Native · Open Source</p>
  <p>
    <a href="#english">EN</a>
    ·
    <a href="#russian">RU</a>
  </p>
  <p>
    <a href="mailto:flame.kaliganov@gmail.com">Email</a>
    ·
    <a href="https://t.me/Artem_Kaliganov">Telegram</a>
    ·
    <a href="https://www.npmjs.com/~flamefrontend">npm</a>
  </p>
</div>

---

<div align="center">
  4.5+ years building products in AI SaaS, ERP, and Telegram Mini Apps
  <br />
  Open source: <a href="https://github.com/FlameFront-end/sse-runtime">sse-runtime</a> ·
  Real-time on SSE and WebSocket ·
  Cross-platform with React Native and Next.js
</div>

---

<a id="english"></a>

## English

Senior Frontend Developer with 4.5+ years building products in AI SaaS, ERP, and Telegram Mini Apps.

Main focus: React, TypeScript, SPA architecture, real-time on SSE and WebSocket, complex forms, and React Native.

### What I Build

<table width="100%">
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/FlameFront-end/sse-runtime">sse-runtime</a></h3>
      TypeScript runtime for Server-Sent Events. I built it to cover what the native <code>EventSource</code> API is missing in real products: auth headers, typed events, React Native support, reconnect logic, and single-tab coordination.<br /><br />
      <blockquote>
        <strong>Replaced 3,455 lines of custom SSE code.</strong>
      </blockquote>
      <code>5 packages</code> · <code>300+ tests</code> · <code>no runtime deps in core</code> · <code>transports for browser and React Native</code><br /><br />
      <strong>What is inside</strong>
      <ul>
        <li>Stateful SSE parser with partial chunk handling and <code>Last-Event-ID</code> recovery.</li>
        <li>Auth refresh on <code>401</code> without dropping the stream.</li>
        <li>Recovery after laptop sleep and network loss.</li>
        <li>Single shared connection across tabs via <code>BroadcastChannel</code> and <code>Web Locks</code>.</li>
      </ul>
      <a href="https://www.npmjs.com/package/@flamefrontend/sse-runtime-core">
        <img src="https://img.shields.io/badge/@flamefrontend%2Fsse--runtime--core-CB3837?style=flat-square&logo=npm&logoColor=white&label=npm" alt="npm" />
      </a>
      &nbsp;
      <a href="https://github.com/FlameFront-end/sse-runtime">
        <img src="https://img.shields.io/badge/FlameFront--end%2Fsse--runtime-161b22?style=flat-square&logo=github&logoColor=white&label=github" alt="github" />
      </a>
    </td>
  </tr>
</table>

### Where I Worked

<table width="100%">
  <tr>
    <td width="33%" valign="top">
      <strong>AI SaaS Platform</strong><br />
      Senior Frontend Developer<br />
      <div style="border-top: 1px solid #3d444d; margin: 8px -14px 10px;"></div>
      Built the frontend from scratch for AI-agent workflows, multimodal chats, teams, templates, and subscriptions.<br /><br />
      Shipped MVP in <strong>1.5 months</strong>, then took the product to production for enterprise and government clients.
    </td>
    <td width="33%" valign="top">
      <strong>wame.tools / Kokoc Group</strong><br />
      Frontend / Fullstack Developer<br />
      <div style="border-top: 1px solid #3d444d; margin: 8px -14px 10px;"></div>
      Worked on a SaaS Telegram Mini Apps platform used across multiple verticals.<br /><br />
      Delivered <strong>10+ projects in 1.5 years</strong>, including HR and fintech products, and led frontend work on a leasing product.
    </td>
    <td width="33%" valign="top">
      <strong>BSO Real Estate Management</strong><br />
      Frontend Developer<br />
      <div style="border-top: 1px solid #3d444d; margin: 8px -14px 10px;"></div>
      Built complex ERP interfaces: schema-driven forms, OCR-assisted document flows, server-side tables, and real-time updates.<br /><br />
      Worked with large data sets, heavy business logic, and performance under load.
    </td>
  </tr>
</table>

<br />

### Core Stack

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <strong>Frontend</strong><br />
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/TypeScript-1E293B?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Next.js-111111?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
      <img src="https://img.shields.io/badge/Vite-1E1B33?style=flat-square&logo=vite&logoColor=646CFF" alt="Vite" />
      <img src="https://img.shields.io/badge/Expo-111827?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
    </td>
    <td width="50%" valign="top">
      <strong>State and Data</strong><br />
      <img src="https://img.shields.io/badge/TanStack_Query-1F2937?style=flat-square&logo=reactquery&logoColor=FF4154" alt="TanStack Query" />
      <img src="https://img.shields.io/badge/Zustand-2A2A2A?style=flat-square&logoColor=white" alt="Zustand" />
      <img src="https://img.shields.io/badge/Redux_Toolkit-2B1F3A?style=flat-square&logo=redux&logoColor=764ABC" alt="Redux Toolkit" />
      <img src="https://img.shields.io/badge/RTK_Query-2B1F3A?style=flat-square&logo=redux&logoColor=764ABC" alt="RTK Query" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Real-time</strong><br />
      <img src="https://img.shields.io/badge/SSE-1F2937?style=flat-square&logoColor=white" alt="SSE" />
      <img src="https://img.shields.io/badge/WebSocket-1F2937?style=flat-square&logoColor=white" alt="WebSocket" />
      <img src="https://img.shields.io/badge/BroadcastChannel-1F2937?style=flat-square&logoColor=white" alt="BroadcastChannel" />
      <img src="https://img.shields.io/badge/Web_Locks_API-1F2937?style=flat-square&logoColor=white" alt="Web Locks API" />
    </td>
    <td width="50%" valign="top">
      <strong>Backend and Infra</strong><br />
      <img src="https://img.shields.io/badge/Node.js-1C2B22?style=flat-square&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" />
      <img src="https://img.shields.io/badge/NestJS-2A1517?style=flat-square&logo=nestjs&logoColor=E0234E" alt="NestJS" />
      <img src="https://img.shields.io/badge/PostgreSQL-1B2333?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/TypeORM-2A1517?style=flat-square&logo=typeorm&logoColor=FE0803" alt="TypeORM" />
      <img src="https://img.shields.io/badge/Redis-2A1517?style=flat-square&logo=redis&logoColor=DC382D" alt="Redis" />
      <img src="https://img.shields.io/badge/Docker-102033?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
      <img src="https://img.shields.io/badge/CI%2FCD-1F2937?style=flat-square&logo=githubactions&logoColor=white" alt="CI/CD" />
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Testing</strong><br />
      <img src="https://img.shields.io/badge/Jest-2B1620?style=flat-square&logo=jest&logoColor=C21325" alt="Jest" />
      <img src="https://img.shields.io/badge/Testing_Library-1F1F1F?style=flat-square&logo=testinglibrary&logoColor=E33332" alt="Testing Library" />
      <img src="https://img.shields.io/badge/Playwright-1A2A1F?style=flat-square&logo=playwright&logoColor=2EAD33" alt="Playwright" />
    </td>
  </tr>
</table>

---

<a id="russian"></a>

## Русский

Senior Frontend Developer с 4.5+ годами в AI SaaS, ERP и Telegram Mini Apps.

Основной фокус: React, TypeScript, SPA-архитектура, real-time на SSE и WebSocket, сложные формы и React Native. Есть и практический fullstack-опыт с Next.js, NestJS и PostgreSQL.

### Что я делаю

<table width="100%">
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/FlameFront-end/sse-runtime">sse-runtime</a></h3>
      TypeScript runtime для production SSE-клиентов. Я сделал его, чтобы закрыть реальные ограничения нативного <code>EventSource</code>: заголовки авторизации, типизированные события, поддержку React Native, переподключение и single-tab coordination.<br /><br />
      <blockquote>
        <strong>После перехода на него я удалил 3 455 строк собственного SSE-клиента из приложения.</strong>
      </blockquote>
      <code>5 пакетов</code> · <code>300+ тестов</code> · <code>в core нет runtime-зависимостей</code> · <code>транспорты для browser и React Native</code><br /><br />
      <strong>Что внутри</strong>
      <ul>
        <li>Stateful SSE parser с поддержкой частичных чанков и recovery через <code>Last-Event-ID</code>.</li>
        <li>Обновление авторизации при <code>401</code> без потери стрима.</li>
        <li>Восстановление после сна ноутбука и потери сети.</li>
        <li>Одно общее соединение между вкладками через <code>BroadcastChannel</code> и <code>Web Locks</code>.</li>
      </ul>
    </td>
  </tr>
</table>

### Где работал

<table width="100%">
  <tr>
    <td width="33%" valign="top">
      <strong>AI SaaS Platform</strong><br />
      Senior Frontend Developer<br />
      <div style="border-top: 1px solid #3d444d; margin: 8px -14px 10px;"></div>
      С нуля построил frontend для AI-агентов, мультимодальных чатов, команд, шаблонов и подписок.<br /><br />
      MVP вышел за <strong>1.5 месяца</strong>, потом продукт был доведен до production для корпоративных и государственных клиентов.
    </td>
    <td width="33%" valign="top">
      <strong>wame.tools / Kokoc Group</strong><br />
      Frontend / Fullstack Developer<br />
      <div style="border-top: 1px solid #3d444d; margin: 8px -14px 10px;"></div>
      Работал над SaaS-конструктором Telegram Mini Apps для разных отраслей.<br /><br />
      За <strong>1.5 года</strong> прошел через <strong>10+ проектов</strong>, включая HR- и fintech-сценарии, и вел frontend на лизинговом проекте.
    </td>
    <td width="33%" valign="top">
      <strong>BSO Real Estate Management</strong><br />
      Frontend Developer<br />
      <div style="border-top: 1px solid #3d444d; margin: 8px -14px 10px;"></div>
      Разрабатывал сложные ERP-интерфейсы: schema-driven формы, OCR-сценарии, серверные таблицы и real-time обновления.<br /><br />
      Основная сложность была в тяжелой бизнес-логике, больших объемах данных и производительности под нагрузкой.
    </td>
  </tr>
</table>

<br />

### Основной стек

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <strong>Frontend</strong><br />
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/TypeScript-1E293B?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Next.js-111111?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
      <img src="https://img.shields.io/badge/Vite-1E1B33?style=flat-square&logo=vite&logoColor=646CFF" alt="Vite" />
      <img src="https://img.shields.io/badge/Expo-111827?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
    </td>
    <td width="50%" valign="top">
      <strong>State и Data</strong><br />
      <img src="https://img.shields.io/badge/TanStack_Query-1F2937?style=flat-square&logo=reactquery&logoColor=FF4154" alt="TanStack Query" />
      <img src="https://img.shields.io/badge/Zustand-2A2A2A?style=flat-square&logoColor=white" alt="Zustand" />
      <img src="https://img.shields.io/badge/Redux_Toolkit-2B1F3A?style=flat-square&logo=redux&logoColor=764ABC" alt="Redux Toolkit" />
      <img src="https://img.shields.io/badge/RTK_Query-2B1F3A?style=flat-square&logo=redux&logoColor=764ABC" alt="RTK Query" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Real-time</strong><br />
      <img src="https://img.shields.io/badge/SSE-1F2937?style=flat-square&logoColor=white" alt="SSE" />
      <img src="https://img.shields.io/badge/WebSocket-1F2937?style=flat-square&logoColor=white" alt="WebSocket" />
      <img src="https://img.shields.io/badge/BroadcastChannel-1F2937?style=flat-square&logoColor=white" alt="BroadcastChannel" />
      <img src="https://img.shields.io/badge/Web_Locks_API-1F2937?style=flat-square&logoColor=white" alt="Web Locks API" />
    </td>
    <td width="50%" valign="top">
      <strong>Backend и Infra</strong><br />
      <img src="https://img.shields.io/badge/Node.js-1C2B22?style=flat-square&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" />
      <img src="https://img.shields.io/badge/NestJS-2A1517?style=flat-square&logo=nestjs&logoColor=E0234E" alt="NestJS" />
      <img src="https://img.shields.io/badge/PostgreSQL-1B2333?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/TypeORM-2A1517?style=flat-square&logo=typeorm&logoColor=FE0803" alt="TypeORM" />
      <img src="https://img.shields.io/badge/Redis-2A1517?style=flat-square&logo=redis&logoColor=DC382D" alt="Redis" />
      <img src="https://img.shields.io/badge/Docker-102033?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
      <img src="https://img.shields.io/badge/CI%2FCD-1F2937?style=flat-square&logo=githubactions&logoColor=white" alt="CI/CD" />
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <strong>Тестирование</strong><br />
      <img src="https://img.shields.io/badge/Jest-2B1620?style=flat-square&logo=jest&logoColor=C21325" alt="Jest" />
      <img src="https://img.shields.io/badge/Testing_Library-1F1F1F?style=flat-square&logo=testinglibrary&logoColor=E33332" alt="Testing Library" />
      <img src="https://img.shields.io/badge/Playwright-1A2A1F?style=flat-square&logo=playwright&logoColor=2EAD33" alt="Playwright" />
    </td>
  </tr>
</table>

---

<div align="center">
  <img src="assets/github-snake.svg" alt="snake" />
</div>
