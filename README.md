# SIGES

### Sistema para la Gestión de los Indicadores y Metas de la Universidad de Holguín

<p align="center">
  <img src="https://img.shields.io/badge/.NET-10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 10" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/Blazor_Server-512BD4?style=for-the-badge&logo=blazor&logoColor=white" alt="Blazor Server" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="Entity Framework Core" />
</p>

<p align="center">
  <b>Proyecto de tesis de Ingeniería Informática · Universidad de Holguín</b><br/>
  Facultad de Informática y Matemática · Sede Oscar Lucero Moya
</p>

<p align="center">
  <a href="#-sobre-el-proyecto">Sobre el proyecto</a> ·
  <a href="#-características-principales">Funcionalidades</a> ·
  <a href="#-tecnologías-utilizadas">Tecnologías</a> ·
  <a href="docs/PORTFOLIO.md">Caso de estudio</a> ·
  <a href="docs/FEATURES.md">Documentación</a>
</p>

---

## 📌 Sobre el proyecto

**SIGES** es una aplicación web desarrollada para digitalizar y centralizar la gestión de los indicadores y metas institucionales de la **Universidad de Holguín**.

El proyecto surge como respuesta a un proceso que se realizaba principalmente mediante documentos de Microsoft Word, hojas de cálculo de Microsoft Excel y documentos impresos. Esta forma de trabajo dificultaba la consolidación de la información, la trazabilidad de los cambios, la confiabilidad de los cálculos y la disponibilidad oportuna de resultados para la toma de decisiones.

SIGES permite administrar indicadores y metas, vincularlos con procesos universitarios y objetivos estratégicos, establecer metas por áreas y automatizar la evaluación del cumplimiento según las tablas de evaluación del Ministerio de Educación Superior (MES).

> 🎓 **Trabajo de diploma en opción al título de Ingeniero Informático.**

---

## 🎯 El problema que resuelve

### Antes

- Información distribuida entre documentos y hojas de cálculo.
- Consolidación manual de datos provenientes de diferentes áreas.
- Cálculos manuales de porcentajes de cumplimiento.
- Riesgo de errores al aplicar las reglas de evaluación.
- Dificultad para conocer el historial y la trazabilidad de los cambios.
- Comunicación informal para negociar o solicitar cambios de metas.

### Con SIGES

- Gestión centralizada de indicadores y metas.
- Registro estructurado de procesos, áreas y objetivos estratégicos.
- Metas diferenciadas por áreas.
- Registro de resultados reales.
- Cálculo automatizado del porcentaje de cumplimiento.
- Evaluación automática de indicadores, procesos y objetivos.
- Gestión de usuarios según responsabilidades y permisos.
- Mayor trazabilidad del proceso de evaluación institucional.

---

## ✨ Características principales

### 📊 Gestión de indicadores
Administración de indicadores institucionales con información como meta, resultado real, tipo, origen, proceso y objetivo estratégico asociado.

### 🔄 Gestión de procesos
Organización de los procesos universitarios y consolidación de su evaluación a partir del desempeño de sus indicadores.

### 📍 Gestión de áreas
Administración de las áreas responsables, incluyendo facultades y municipios, con metas y resultados específicos.

### 🚩 Objetivos estratégicos
Gestión de los objetivos estratégicos y evaluación de su cumplimiento a partir de los indicadores asociados.

### 🧮 Evaluación automatizada
El sistema calcula el cumplimiento y clasifica los resultados en categorías como:

- Sobrecumplido
- Cumplido
- Parcialmente cumplido
- Incumplido
- No evaluado

### 👥 Usuarios y roles
El sistema contempla cuatro roles diferenciados:

- **Administrador**
- **Jefe de Proceso**
- **Jefe de Área**
- **Usuario Normal**

Cada rol dispone de responsabilidades y permisos específicos dentro del proceso de gestión y evaluación.

### 🔔 Flujo de responsabilidades
Los responsables de área registran los resultados alcanzados y pueden solicitar cambios de metas. Los responsables de proceso gestionan los indicadores bajo su responsabilidad y atienden las solicitudes relacionadas. El administrador controla la configuración general, los usuarios y el proceso de evaluación.

### 📈 Resúmenes de evaluación
SIGES ofrece vistas consolidadas para analizar el estado de los indicadores, procesos y objetivos estratégicos.

Para una descripción más detallada de los módulos, consulta [docs/FEATURES.md](docs/FEATURES.md).

---

## 🏗️ Tecnologías utilizadas

| Tecnología | Uso en el proyecto |
|---|---|
| **C#** | Lenguaje principal de desarrollo |
| **.NET 10** | Plataforma de desarrollo |
| **Blazor Server** | Interfaz web y experiencia de usuario |
| **SQL Server** | Persistencia de datos |
| **Entity Framework Core** | Acceso y gestión de datos |
| **FluentUI Blazor** | Componentes de interfaz |
| **ASP.NET Core** | Servicios y funcionalidades web |
| **REST API** | Comunicación mediante operaciones HTTP |

---

## 📐 Alcance funcional

El proyecto de tesis define **50 requisitos funcionales**, organizados en ocho paquetes, y **42 operaciones REST** distribuidas en seis servicios web.

La solución está orientada a gestionar el ciclo completo de los indicadores institucionales: configuración, asignación, definición de metas, registro de resultados, cálculo del cumplimiento, evaluación y consolidación de resultados.

---

## 🔐 Roles del sistema

| Rol | Responsabilidad principal |
|---|---|
| **Administrador** | Gestiona usuarios, configuración general y evaluación del sistema |
| **Jefe de Proceso** | Gestiona indicadores asociados a su proceso y consolida información relacionada |
| **Jefe de Área** | Registra resultados reales y participa en la gestión de metas de su área |
| **Usuario Normal** | Accede a las funcionalidades habilitadas según su nivel de permisos |

---

## 💼 Proyecto de portfolio

Además de su contexto académico, SIGES representa una experiencia práctica en el desarrollo de una aplicación de gestión con reglas de negocio, distintos roles de usuario, persistencia de datos, APIs y una interfaz web para un contexto institucional real.

📄 **[Leer el caso de estudio del proyecto →](docs/PORTFOLIO.md)**

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio.
2. Abre la solución `WEB.sln` con Visual Studio o JetBrains Rider.
3. Configura la cadena de conexión y los parámetros necesarios para el entorno.
4. Restaura las dependencias del proyecto.
5. Ejecuta la aplicación desde el proyecto web configurado como proyecto de inicio.

> La configuración concreta puede depender del entorno de desarrollo y de los servicios configurados en el proyecto.

---

## 🎓 Contexto académico

Este proyecto fue desarrollado como **Trabajo de Diploma en opción al título de Ingeniería Informática** para la **Universidad de Holguín**, en la **Facultad de Informática y Matemática**, sede **Oscar Lucero Moya**.

El objetivo de la investigación fue desarrollar un sistema web que informatizara la gestión de los indicadores y metas institucionales, siguiendo los lineamientos del Proyecto Estratégico del Ministerio de Educación Superior de Cuba.

---

## 👨‍💻 Autor

**José Osvaldo Verdecia Argota**

Ingeniero Informático | .NET Developer

- GitHub: https://github.com/JoseVerdecia
- Proyecto: https://github.com/JoseVerdecia/Web

---

<p align="center">
  <i>Proyecto académico desarrollado para resolver un problema real de gestión y evaluación institucional.</i>
</p>
