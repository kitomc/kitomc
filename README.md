<div align="center">

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

# Francis Alexander Gonzalez Almonte

**Desarrollador Full Stack · SDD · DDD · POO · Ingeniería asistida por agentes LLM**

Construyo ERPs, plataformas SaaS e integraciones con IA en producción.
Trabajo con **SDD · DDD · POO** y desarrollo **únicamente con asistencia de
agentes LLM** por eficiencia y tiempo: especificación primero, dominio en el
centro y pruebas que verifican.

`TypeScript` · `React` · `Convex` · `Supabase` · `Flutter` · `Docker`

[![Ubicación](https://img.shields.io/badge/Rep%C3%BAblica_Dominicana-1F2937?style=flat-square&logo=googlemaps&logoColor=white)](#)
[![Correo](https://img.shields.io/badge/kitomc.rd@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kitomc.rd@gmail.com)
[![GitHub](https://img.shields.io/badge/@kitomc-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kitomc)

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">

</div>

## Qué hago

Diseño y entrego productos full stack de punta a punta: modelo de datos, backend,
superficie de API e interfaz que la gente realmente usa. El hilo conductor de mi
trabajo es software que se mantiene: límites de módulo claros, pruebas reales y
documentación sobre la que un ingeniero puede actuar.

- **Backend y datos** — backends serverless en Convex, PostgreSQL con Supabase, modelado relacional, APIs REST
- **Frontend y móvil** — React y TypeScript en web, Flutter para móvil multiplataforma
- **Automatización** — pipelines resilientes, herramientas de línea de comandos y automatización de navegador desatendida
- **Entrega asistida por IA** — agentes LLM como parte de la cadena de herramientas, guiados por especificación y verificados por pruebas

<br>

## Cómo trabajo

Desarrollo exclusivamente con asistencia de IA (Claude Code, MCP, agentes
especializados) por eficiencia y tiempo. La metodología es lo que hace que ese
código sea mantenible:

| Metodología | Qué significa en mi trabajo |
| :--- | :--- |
| **SDD — Spec-Driven Development** | Cada cambio arranca con una especificación versionada en el repositorio: requisitos, escenarios y criterios de aceptación. El código se verifica contra la spec, no contra la memoria. |
| **DDD — Domain-Driven Design** | El modelo de dominio manda: entidades, agregados e invariantes con un lenguaje ubicuo compartido con el cliente. La infraestructura queda fuera de las reglas de negocio (arquitectura hexagonal). |
| **POO — Programación Orientada a Objetos** | Responsabilidades claras, principios SOLID y contratos explícitos entre módulos, para que el sistema sobreviva al siguiente cambio sin reescrituras. |
| **Desarrollo asistido por IA** | Los agentes LLM ejecutan bajo especificación y pruebas. El ingeniero es dueño de la arquitectura y las decisiones; el agente, del tecleo. |
| **Pruebas que describen comportamiento** | Playwright y Vitest. La cobertura es una consecuencia, no el objetivo. |

<br>

## Proyectos

| Proyecto | Qué es | Mi rol | Stack |
| :--- | :--- | :--- | :--- |
| **FHG Distribuidora — ERP** | Gestión para distribuidora mayorista: ventas a cuotas, cartera, cobros, cuadres de caja, inventario ABC, comisiones y reportería. 440+ commits. | Diseño y desarrollo completo | React, Supabase, PL/pgSQL, Playwright |
| **[Sandov Structure](https://structure.sandov.ai)** | SaaS de cálculo estructural: motor FEM 3D, verificación ACI 318 / AISC 360, sísmico dinámico, BIM/IFC, asesor IA y reportes PDF trazables. | Diseño y desarrollo completo | React, Convex, Cloudflare Workers, LLM |
| **[EstimaPro / Estimator AI](https://estimapro-rd.pages.dev)** | Conecta el presupuesto del ingeniero con ferreterías: escáner de planos con IA, cuantificación y cotización. | Diseño y desarrollo completo | React, Convex, Cloudflare Pages, visión IA |
| **[CookSnap](https://cooksnap-4kh.pages.dev)** | App de cocina con IA: recetas a partir de ingredientes, auth, i18n, mobile-first. | Diseño y desarrollo completo | React, Convex, Cloudflare Pages, LLM |
| **[Colegio Ciudad Real](https://cocire.edu.do)** | Sitio institucional de admisiones + ERP escolar interno. | Diseño y desarrollo completo | React, Supabase, Cloudflare |
| **Spatium** | Sitio corporativo de oficinas/coworking y ERP de operación interna (Boosty Digital / Spatium). | Integrador sénior y desarrollo | React, Node.js, PostgreSQL, automatización |
| **[Planix](https://planixapp.com.do)** | Portal transaccional de compras empresariales en RD con integraciones a Oracle NetSuite, SAP, Odoo, Exactus e Infor. | Desarrollo y mantenimiento como parte del equipo | Angular, Node.js, integraciones ERP |

<br>

## Trabajo actual

Estos son los sistemas en los que trabajo a diario. **El código es privado por
acuerdo con el cliente**, pero puedo explicar la arquitectura y las decisiones
técnicas en una entrevista.

### FHG Distribuidora — Sistema de gestión para distribuidora mayorista

`449 commits` · `TypeScript` · `PL/pgSQL`

- Frontend en React + Vite con sistema de componentes propio sobre shadcn/ui y Radix
- Backend en Supabase: PostgreSQL con funciones y lógica en PL/pgSQL
- Estado de servidor con TanStack Query; formularios validados con React Hook Form + Zod
- Inventario con escaneo de códigos QR y geolocalización de rutas con Leaflet
- Reportería con Recharts y exportación a Excel
- Suite de pruebas de extremo a extremo con Playwright
- Especificaciones versionadas en el repositorio (`openspec/`)

### Yina Bank — Plataforma de financiamiento y control de cuotas

`TypeScript` · `en desarrollo activo`

- Backend serverless en Convex con autenticación mediante Convex Auth
- Frontend en React con TanStack Router y animación con Framer Motion
- Generación y lectura de documentos PDF para contratos y cronogramas de cuotas
- Despliegue en Cloudflare Workers
- Pruebas de extremo a extremo con Playwright y requisitos documentados en `PRD.md`

<br>

## Código público

### [colmado-saas](https://github.com/kitomc/colmado-saas) — Plataforma SaaS multiinquilino

`Convex` · `Dart/Flutter` · `TypeScript`

Backend serverless en Convex, consola de administración web y cliente móvil
multiplataforma en Flutter, sobre un modelo de datos multiinquilino.

<br>

## Stack

**Lenguajes**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL_%2F_PL%2FpgSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

**Frontend y móvil**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)

**Backend y datos**

![Convex](https://img.shields.io/badge/Convex-EE342F?style=flat-square&logo=convex&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

**Pruebas y calidad**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)

**Infraestructura y herramientas**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)
![tmux](https://img.shields.io/badge/tmux-1BB91F?style=flat-square&logo=tmux&logoColor=white)

**Ingeniería asistida por IA**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-000000?style=flat-square)
![Spec-Driven Development](https://img.shields.io/badge/Spec--Driven_Development-6A5ACD?style=flat-square)

<br>

## Contacto

Disponible para posiciones full stack y colaboración en productos donde la
arquitectura y la mantenibilidad importan de verdad.

**Correo** — [kitomc.rd@gmail.com](mailto:kitomc.rd@gmail.com)

**GitHub** — [@kitomc](https://github.com/kitomc)

<div align="center">
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%">
</div>
