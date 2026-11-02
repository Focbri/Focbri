<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1B2A,100:2F81F7&height=190&section=header&text=Joan%20P%C3%A9rez&fontSize=54&fontColor=ffffff&fontAlignY=38&desc=Desarrollador%20de%20Software&descSize=20&descAlignY=58" alt="Joan Pérez, Desarrollador de Software" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=680&lines=IoT+industrial+y+monitoreo+en+tiempo+real;Backend+y+arquitecturas+distribuidas;Aplicaciones+full+stack+con+Laravel+y+React" alt="IoT industrial, backend y aplicaciones full stack" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/developer-joan/"><img src="https://img.shields.io/badge/LinkedIn-developer--joan-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="mailto:focbri@gmail.com"><img src="https://img.shields.io/badge/Correo-focbri%40gmail.com-EA4335?style=for-the-badge" alt="Correo" /></a>
  <img src="https://img.shields.io/badge/Ubicaci%C3%B3n-Lima%2C%20Per%C3%BA-2F81F7?style=for-the-badge" alt="Lima, Perú" />
</p>

## 👋 Sobre mí

Construyo software que conecta el mundo físico con los datos. Diseño soluciones de monitoreo en tiempo real para entornos industriales, y también desarrollo aplicaciones web de principio a fin.

- 🏭 **Ahora:** IoT y telemetría para flotas en el sector minero.
- 🛡️ **Lo que me importa:** sistemas que siguen funcionando cuando falla la conexión.
- 🧩 **Mi experiencia:** IoT, backend, frontend, infraestructura y despliegue.

## 🛠️ Tecnologías

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,laravel,php,react,nextjs,astro,js,ts,tailwind&perline=10" alt="Node.js, Express, Laravel, PHP, React, Next.js, Astro, JavaScript, TypeScript y Tailwind CSS" />
  <br />
  <img src="https://skillicons.dev/icons?i=mysql,mongodb,sqlite,docker,ubuntu,nginx,git,github&perline=10" alt="MySQL, MongoDB, SQLite, Docker, Ubuntu, Nginx, Git y GitHub" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MQTT-Mosquitto-660066?style=flat-square" alt="MQTT Mosquitto" />
  <img src="https://img.shields.io/badge/TCP%2FIP-1F6FEB?style=flat-square" alt="TCP/IP" />
  <img src="https://img.shields.io/badge/CAN-1F6FEB?style=flat-square" alt="CAN" />
  <img src="https://img.shields.io/badge/Telemetr%C3%ADa-1F6FEB?style=flat-square" alt="Telemetría" />
  <img src="https://img.shields.io/badge/Dataloggers-1F6FEB?style=flat-square" alt="Dataloggers" />
  <img src="https://img.shields.io/badge/Geolocalizaci%C3%B3n-1F6FEB?style=flat-square" alt="Geolocalización" />
  <img src="https://img.shields.io/badge/Windows%20Server-IIS-0078D4?style=flat-square" alt="Windows Server e IIS" />
  <img src="https://img.shields.io/badge/VPN-1F6FEB?style=flat-square" alt="VPN" />
  <img src="https://img.shields.io/badge/SCADA-Ignition-1F6FEB?style=flat-square" alt="Arquitecturas adaptables a SCADA Ignition" />
</p>

## 📡 Cómo construyo un sistema IoT resiliente

Este es el enfoque general que aplico, simplificado:

```mermaid
flowchart LR
    A[Equipos industriales] --> B[Datalogger]
    B -->|Con conexión| C[Broker MQTT]
    B -->|Sin conexión| D[(Almacenamiento local)]
    D -->|Retransmisión automática| C
    C -->|VPN| E[Servidor central]
    E --> F[(Histórico)]
    E --> G[Clientes y dashboards]
```

## 💼 Experiencia

<details open>
<summary><b>Software Developer, IoT & Infrastructure</b> · Sector minero · <i>Ago 2025 – Presente</i></summary>
<br />

- Diseño e implementación de una solución IoT para monitorear flotas en tiempo real.
- Datalogger para capturar variables operativas de forma continua.
- Almacenamiento local en SQLite y retransmisión automática ante caídas de conectividad.
- Microservicios de reconexión automática y tolerancia a fallos.
- Administración del broker MQTT y del servidor central de ingestión, histórico y redistribución de datos.
- Despliegue con Docker y comunicaciones seguras mediante VPN.

</details>

<details>
<summary><b>Full Stack Developer</b> · Grupo de Negocios Corporativos Comerciales E.I.R.L. · <i>Jul 2024 – Jul 2025</i></summary>
<br />

- Sistema de gestión clínica con Laravel, React y MySQL.
- Digitalización del 100 % de las historias clínicas físicas.
- Reducción del 40 % en los tiempos de búsqueda.
- Generación automática de documentos médicos en PDF.
- Configuración y despliegue en Windows Server (IIS).

</details>

<details>
<summary><b>Web Developer</b> · Centro Cómputo Corporación S.A.C. · <i>Jul 2023 – Dic 2024</i></summary>
<br />

- Plataformas web con Astro, React y Next.js.
- Optimización del rendimiento con SSR y lazy loading.
- Integración con CMS y soluciones en PHP.
- Mejora del 25 % en la retención de usuarios.

</details>

## 🚀 Proyectos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Focbri/sistemaHistorialClinico">🏥 Historial clínico</a></h3>
      Gestión de pacientes y consultas médicas, con autenticación.<br /><br />
      <code>Laravel</code> <code>React</code> <code>Inertia.js</code> <code>MySQL</code>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Focbri/Poke_API">🎮 Pokédex</a></h3>
      Reto técnico con búsqueda, filtros, detalle y favoritos.<br /><br />
      <code>React</code> <code>Vite</code> <code>React Router</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Focbri/podo">🦶 Pododinamic</a></h3>
      Sitio web con especialidades, cursos y contacto.<br /><br />
      <code>Astro</code> <code>React</code> <code>Tailwind CSS</code>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Focbri/GrupoNec">💻 Grupo NEC</a></h3>
      Sitio corporativo con catálogo de productos de cómputo.<br /><br />
      <code>Astro</code> <code>TypeScript</code> <code>Tailwind CSS</code>
    </td>
  </tr>
</table>

## 🎓 Formación

- **Técnico en Desarrollo de Software** · SENATI (2022 – 2025)
- **Inglés, nivel intermedio** · ICPNA (2020 – 2021)

## 🐍 Mi actividad en GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Focbri/Focbri/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/Focbri/Focbri/output/github-snake.svg" alt="Animación de mis contribuciones en GitHub" />
  </picture>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F81F7,100:0D1B2A&height=100&section=footer" alt="" width="100%" />
</p>
