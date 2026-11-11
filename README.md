<div align="center">
  <img src="https://raw.githubusercontent.com/sedergsoft/SedergPay_oficial/main/docs/assets/banner.png" alt="SEDERG_PAY" width="100%">
</div>

<div align="center">

# Hola, soy **SEDERG** 👋

💻 Ingeniero de producto · Construyo plataformas de remesas con trazabilidad y control
🌍 Specialist in **remesas Rusia → Cuba** · 🇷🇺🇨🇺
📍 Construyendo software **desde Cuba hacia el mundo**

[🚀 Demo en vivo](https://sedergsoft.github.io/SedergPay_oficial/) · [🔌 API](https://5-22-219-30.sslip.io/health) · [📦 Código](https://github.com/sedergsoft/SedergPay_oficial)

[Español](./README.md) · [Русский](https://github.com/sedergsoft/SedergPay_oficial/blob/main/README.ru.md)

</div>

---

<div align="center">

[![CI](https://github.com/sedergsoft/SedergPay_oficial/actions/workflows/ci.yml/badge.svg)](https://github.com/sedergsoft/SedergPay_oficial/actions/workflows/ci.yml)
[![Pages](https://github.com/sedergsoft/SedergPay_oficial/actions/workflows/deploy-pages.yml/badge.svg)](https://github.com/sedergsoft/SedergPay_oficial/actions/workflows/deploy-pages.yml)
[![Deploy](https://github.com/sedergsoft/SedergPay_oficial/actions/workflows/deploy.yml/badge.svg)](https://github.com/sedergsoft/SedergPay_oficial/actions/workflows/deploy.yml)

[![React](https://img.shields.io/badge/React-18.3-61DAFB?style=flat-square&logo=react&logoColor=20232A)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6-3178C6?style=flat-square&logo=typescript&logoColor=20232A)](https://www.typescriptlang.org/)
[![PHP](https://img.shields.io/badge/PHP-8.3-777BB4?style=flat-square&logo=php&logoColor=20232A)](https://www.php.net/)
[![Yii2](https://img.shields.io/badge/Yii2-2.0-00AEEF?style=flat-square)](https://www.yiiframework.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-4169E1?style=flat-square&logo=postgresql&logoColor=20232A)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=20232A)](https://docs.docker.com/)
[![Caddy](https://img.shields.io/badge/Caddy-2.0-2C5FD4?style=flat-square)](https://caddyserver.com/)
[![i18n](https://img.shields.io/badge/i18n-ES%20%7C%20RU-00AEEF?style=flat-square)](https://github.com/sedergsoft/SedergPay_oficial)

</div>

---

## 🧭 ¿Qué construyo?

> **SEDERG_PAY** — una plataforma de **gestión, control y conciliación de remesas**
> entre Rusia y Cuba, con cotización en vivo, trazabilidad unitaria, control de
> cumplimiento y un panel administrativo.

No es una maqueta: es un producto **desplegado y en funcionamiento**, con frontend en
GitHub Pages y backend en la nube con TLS, PostgreSQL, ClamAV y despliegue automatizado
desde GitHub Actions.

<div align="center">
  <img src="https://raw.githubusercontent.com/sedergsoft/SedergPay_oficial/main/docs/assets/app-home.png" alt="Portal de SEDERG_PAY" width="100%">
</div>

---

## 🧩 En cifras

| | |
|---|---|
| 🔗 Endpoints REST documentados | 17 |
| 🗄️ Migraciones PostgreSQL | 16 |
| 🧠 Clases de dominio | 29 |
| ✅ Tests en verde | 27 (56 aserciones) |
| ⚙️ Workflows de CI/CD | 4 |
| 🌍 Idiomas de la interfaz | Español · Русский |
| 🔐 Módulos de seguridad | 2FA TOTP, KYC con ClamAV, idempotencia, auditoría, cifrado |

---

## 🏗️ Lo que hay dentro

| Módulo | Detalle |
|---|---|
| **Cotizaciones** | Tasa oficial del Banco Central de Cuba, comisión configurable y límites por par |
| **Remesas** | Máquina de estados completa: cotización → orden → depósito → cumplimiento → conciliación |
| **KYC** | Validación de firma real de archivo, escaneo antimalware **fail-closed** y cifrado en reposo |
| **Seguridad de cuenta** | 2FA con códigos de recuperación, cambio y recuperación de contraseña |
| **Administración** | Ajustes operativos, tasas por par, usuarios, panel e historial auditado |
| **Ledger** | Partida doble, idempotencia por clave y saldos verificables |

---

## 🛠️ Stack

**Frontend** React 18 · TypeScript 5.6 · Vite 5.4 · Nginx
**Backend** PHP 8.3 · Yii2 2.0 · PHPUnit 10.5 · OpenAPI
**Datos** PostgreSQL 17 · ClamAV
**Infraestructura** Docker Compose · Caddy 2 (TLS automático) · UpCloud · GitHub Actions

---

## 🚀 Encuéntrame en

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-sedergsoft-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sedergsoft)
[![App](https://img.shields.io/badge/App_en_vivo-00AEEF?style=for-the-badge&logo=react&logoColor=white)](https://sedergsoft.github.io/SedergPay_oficial/)
[![API](https://img.shields.io/badge/API-0B4F9C?style=for-the-badge&logo=postman&logoColor=white)](https://5-22-219-30.sslip.io/health)
[![Documentación](https://img.shields.io/badge/Runbook-10264D?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/sedergsoft/SedergPay_oficial/blob/main/deploy/UPCLOUD.md)
[![Issues](https://img.shields.io/badge/Issues-abierto-E53935?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sedergsoft/SedergPay_oficial/issues)

</div>

---

## 📚 Documentación que escribo

- **[Memoria técnica](https://github.com/sedergsoft/SedergPay_oficial/blob/main/SEDERG_PAY_Memoria_Tecnica.docx)** — arquitectura, modelo de datos y flujos.
- **[Presentación comercial](https://github.com/sedergsoft/SedergPay_oficial/blob/main/SEDERG_PAY_Presentacion_Comercial.docx)** — propuesta de valor y Hoja de ruta.
- **[Runbook de despliegue](https://github.com/sedergsoft/SedergPay_oficial/blob/main/deploy/UPCLOUD.md)** — de cero a producción, con backups y rollback.
- **[Plan de acción](https://github.com/sedergsoft/SedergPay_oficial/blob/main/PLAN_DE_ACCION.md)** — fases, entregables y *gates* de salida.

---

## 💬 Contacto

> ¿Hablamos de remesas, trazabilidad o tu próximo proyecto fintech?
> Abre un *issue* en el repositorio o escríbeme por los canales que configures aquí.

<!-- Añade tus enlaces reales: LinkedIn · Telegram · X · email -->

---

<div align="center">

**SEDERG_PAY** — *Conectando personas, sin fronteras* 🇷🇺 🇨🇺

Hecho con ☕, PHP y mucho cuidado con los centavos.

</div>
