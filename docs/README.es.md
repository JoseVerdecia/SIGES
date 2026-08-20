# SIGES

### Sistema para la Gestión de los Indicadores y Metas de la Universidad de Holguín

<p align="center">
  <img src="https://img.shields.io/badge/.NET-10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 10" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/Blazor_Server-512BD4?style=for-the-badge&logo=blazor&logoColor=white" alt="Blazor Server" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
</p>

<p align="center"><b>Proyecto de tesis de Ingeniería Informática · Universidad de Holguín</b><br/>Facultad de Informática y Matemática · Sede Oscar Lucero Moya</p>

<p align="center"><a href="../README.md">🇬🇧 English</a> | <a href="README.es.md">🇪🇸 Español</a> | <a href="README.pt-BR.md">🇧🇷 Português</a></p>

---

##  Sobre el proyecto

**SIGES** es una aplicación web desarrollada para digitalizar y centralizar la gestión de los indicadores y metas institucionales de la **Universidad de Holguín**.

El proyecto surge como respuesta a un proceso que se realizaba principalmente mediante documentos de Microsoft Word, hojas de cálculo de Microsoft Excel y documentos impresos. Esta forma de trabajo dificultaba la consolidación de la información, la trazabilidad de los cambios, la confiabilidad de los cálculos y la disponibilidad oportuna de resultados para la toma de decisiones.

SIGES permite administrar indicadores y metas, vincularlos con procesos universitarios y objetivos estratégicos, establecer metas por áreas y automatizar la evaluación del cumplimiento según las tablas de evaluación del Ministerio de Educación Superior (MES).

>  **Trabajo de diploma en opción al título de Ingeniero Informático.**

##  El problema que resuelve

### Antes
- Información distribuida entre documentos y hojas de cálculo.
- Consolidación manual de datos de diferentes áreas.
- Cálculos manuales de porcentajes de cumplimiento.
- Riesgo de errores al aplicar las reglas de evaluación.
- Dificultad para mantener el historial y la trazabilidad.

### Con SIGES
- Gestión centralizada de indicadores y metas.
- Registro estructurado de procesos, áreas y objetivos estratégicos.
- Metas diferenciadas por áreas.
- Registro de resultados reales.
- Cálculo automatizado del porcentaje de cumplimiento.
- Evaluación automática de indicadores, procesos y objetivos.
- Gestión de usuarios según responsabilidades y permisos.

##  Características principales

###  Gestión de indicadores
Administración de indicadores institucionales con meta, resultado real, tipo, origen, proceso y objetivo estratégico asociado.

###  Gestión de procesos
Organización de los procesos universitarios y consolidación de su evaluación a partir del desempeño de sus indicadores.

###  Gestión de áreas
Administración de facultades y municipios responsables, con metas y resultados específicos.

###  Objetivos estratégicos
Gestión de objetivos estratégicos y evaluación de su cumplimiento a partir de los indicadores asociados.

###  Evaluación automatizada
El sistema clasifica los resultados como **Sobrecumplido, Cumplido, Parcialmente cumplido, Incumplido** o **No evaluado**.

###  Usuarios y roles
- **Administrador**
- **Jefe de Proceso**
- **Jefe de Área**
- **Usuario Normal**

##  Galería del sistema

### Creación de cuenta
<p align="center"><img src="Crear%20Cuenta.jpg" alt="Creación de cuenta en SIGES" width="850" /></p>

### Gestión de indicadores
<p align="center"><img src="Indicadores.jpg" alt="Gestión de indicadores" width="900" /></p>

### Creación de un indicador
<p align="center">
<img src="Paso%231%20Crear%20Indicador.png" alt="Paso 1" width="850" />
<img src="Paso%232%20Crear%20Indicador.png" alt="Paso 2" width="850" />
<img src="Paso%233%20Crear%20Indicador.png" alt="Paso 3" width="850" />
</p>

### Áreas y objetivos estratégicos
<p align="center"><img src="Areas.jpg" alt="Gestión de áreas" width="850" /></p>
<p align="center"><img src="Objetivos.jpg" alt="Objetivos estratégicos" width="850" /></p>

### Evaluación de indicadores y procesos
<p align="center"><img src="Porcentaje%20de%20Cumplimiento.png" alt="Porcentaje de cumplimiento" width="850" /></p>
<p align="center"><img src="Evaluacion%20del%20Indicador.jpg" alt="Evaluación del indicador" width="850" /></p>
<p align="center"><img src="Evaluacion%20Proceso.png" alt="Evaluación de proceso" width="850" /></p>

##  Tecnologías utilizadas

| Tecnología | Uso en el proyecto |
|---|---|
| **C#** | Lenguaje principal |
| **.NET 10** | Plataforma de desarrollo |
| **Blazor Server** | Interfaz web |
| **SQL Server** | Persistencia de datos |
| **Entity Framework Core** | Acceso a datos |
| **FluentUI Blazor** | Componentes de interfaz |
| **ASP.NET Core** | Servicios y funcionalidades web |
| **REST API** | Comunicación mediante HTTP |

##  Alcance funcional

El proyecto de tesis define **50 requisitos funcionales**, organizados en ocho paquetes, y **42 operaciones REST** distribuidas en seis servicios web.

##  Proyecto de portfolio

SIGES representa una experiencia práctica en el desarrollo de una aplicación de gestión con reglas de negocio, distintos roles de usuario, persistencia de datos, APIs y una interfaz web para un contexto institucional real.

📄 [Caso de estudio](PORTFOLIO.md) · 📋 [Documentación de funcionalidades](FEATURES.md) · 💼 [Presentación para LinkedIn](LINKEDIN.md)

##  Autor

**José Osvaldo Verdecia Argota**

Ingeniero Informático | .NET Developer

- GitHub: https://github.com/JoseVerdecia
- Proyecto: https://github.com/JoseVerdecia/Web
