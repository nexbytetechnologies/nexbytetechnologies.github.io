# Nexbyte Technologies

Sitio web oficial de **Nexbyte Technologies**, enfocado en soluciones digitales modernas para pequeñas y medianas empresas (PYMEs).

El proyecto presenta los servicios de Nexbyte, demostraciones de trabajos desarrollados y un canal de contacto para potenciales clientes.

## 🌐 Sitio web

https://nexbytetechnologies.github.io/

## 🚀 Características

- Diseño moderno y responsive
- Modo claro y oscuro
- Navegación adaptada a dispositivos móviles
- Identidad visual propia de Nexbyte Technologies
- Sección de servicios
- Portafolio de proyectos
- Formulario de contacto funcional
- Integración segura con Formspree
- Validación de formularios
- Protección anti-spam mediante honeypot
- Mensajes de éxito y error sin abandonar la página
- Despliegue automático con GitHub Actions
- Publicación mediante GitHub Pages

## 🛠️ Tecnologías

- Astro
- Tailwind CSS
- TypeScript / JavaScript
- HTML
- CSS
- Git
- GitHub
- GitHub Actions
- GitHub Pages
- Formspree

## 📁 Estructura principal

```text
src/
├── components/
│   ├── About.astro
│   ├── Contact.astro
│   ├── Footer.astro
│   ├── Hero.astro
│   ├── Navbar.astro
│   ├── Projects.astro
│   ├── Services.astro
│   └── ThemeToggle.astro
│
├── layouts/
│   └── Layout.astro
│
├── pages/
│   └── index.astro
│
└── styles/
    └── global.css

public/
├── projects/
│   └── nexopyme.png
├── nexbyte-icon.png
├── nexbyte-logo.png
└── nexbyte-wordmark.png
```

## 💼 Portafolio

### NexoPyme

Primera demostración desarrollada por Nexbyte Technologies.

Landing page moderna y responsiva orientada a PYMEs que buscan fortalecer su presencia digital.

**Ver demo:**

https://nexbytetechnologies.github.io/landing-pyme/

## 📬 Contacto

El sitio incorpora un formulario de contacto conectado a Formspree.

La implementación evita almacenar credenciales privadas en el frontend y utiliza:

- solicitudes HTTPS
- método POST
- validación de campos
- honeypot anti-spam
- restricción de dominio
- procesamiento externo mediante Formspree

La integración con **WhatsApp Business** está preparada para ser incorporada cuando exista un número comercial destinado a Nexbyte Technologies.

## 🔐 Seguridad

Este repositorio no debe contener información sensible como:

- contraseñas
- tokens
- claves API privadas
- credenciales
- secretos
- archivos `.env` reales

Los archivos de variables de entorno se encuentran excluidos mediante `.gitignore`.

```gitignore
.env
.env.*
!.env.example
```

Las futuras integraciones con APIs, backend, autenticación o bases de datos deberán mantener los secretos exclusivamente fuera del código público.

## 💻 Desarrollo local

Clonar el repositorio:

```bash
git clone https://github.com/nexbytetechnologies/nexbytetechnologies.github.io.git
```

Entrar al proyecto:

```bash
cd nexbytetechnologies.github.io
```

Instalar dependencias:

```bash
npm install
```

Ejecutar el entorno de desarrollo:

```bash
npm run dev
```

Por defecto Astro estará disponible en:

```text
http://localhost:4321/
```

## 📦 Build de producción

```bash
npm run build
```

La versión optimizada se genera en:

```text
dist/
```

## ☁️ Despliegue

Cada actualización enviada a la rama `main` ejecuta automáticamente el workflow de GitHub Actions.

```text
Push a main
     ↓
GitHub Actions
     ↓
Build de Astro
     ↓
GitHub Pages
     ↓
nexbytetechnologies.github.io
```

## 📌 Estado

**Nexbyte Technologies — Web principal V1**

El proyecto continúa evolucionando con nuevas demostraciones, servicios e integraciones orientadas a PYMEs.

---

Developed by **Nexbyte Technologies**
