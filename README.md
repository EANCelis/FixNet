# Fixnet 🔧

**Plataforma web responsive para la búsqueda y contratación de profesionales del hogar.**

Fixnet conecta usuarios que necesitan servicios de plomería, gas, electricidad o soporte técnico informático con profesionales verificados, de forma rápida y desde cualquier dispositivo.

---

## 📋 Descripción

Fixnet es una aplicación web desarrollada como Proyecto Final del **Grupo 3 - FRGP**. Permite a los usuarios buscar profesionales por categoría de servicio, ver sus perfiles y contactarlos. Los profesionales, a su vez, pueden registrarse y ofrecer sus servicios en la plataforma.

### Categorías de servicio disponibles

- ⚡ Electricista
- 🔧 Plomero
- 💻 Técnico de PC
- ❄️ Técnico de aires acondicionados
- 🧱 Albañil
- 🎨 Pintor
- 🔥 Gasista
- 🌿 Jardinero
- 🪑 Carpintero
- 🔑 Cerrajero
- 🚛 Fletero
- 🧹 Limpieza
- 👨‍🍳 Cocinero
- 🏠 Vidriero
- ⚙️ Herrero
- 🔒 Instalador de alarmas
- 🐕 Paseador de perros

---

## 🚀 Funcionalidades principales

- Registro e inicio de sesión para **usuarios** y **profesionales**
- Búsqueda de profesionales por categoría de servicio
- Visualización de perfiles de profesionales
- Diseño **responsive** adaptado a dispositivos móviles y de escritorio

---

## 🛠️ Tecnologías utilizadas

| Capa | Tecnología |
|---|---|
| Frontend | ASP.NET, JavaScript, CSS |
| Backend | C# |
| Base de datos | SQL Server (T-SQL) |
| IDE | Visual Studio |

---

## 🏗️ Arquitectura

El proyecto sigue una **arquitectura en capas**:

```
Proyecto-Final/
├── Dominio/        # Entidades y modelos del sistema
├── Negocio/        # Lógica de negocio y reglas de la aplicación
├── Servicios/      # Capa de acceso a datos y servicios externos
├── Fixnet/         # Proyecto web principal (frontend + controladores)
└── Script sql/     # Scripts de creación y población de la base de datos
```

---

## ⚙️ Instalación y configuración

### Requisitos previos

- Visual Studio 2022 o superior
- SQL Server 2019 o superior
- .NET Framework / .NET (según versión del proyecto)

### Pasos

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/EANCelis/FixNet.git
   ```

2. **Configurar la base de datos**
   - Abrir SQL Server Management Studio
   - Ejecutar los scripts ubicados en la carpeta `Script sql/`
   - Esto creará la base de datos con toda la estructura necesaria

3. **Configurar la cadena de conexión**
   - Abrir el proyecto en Visual Studio
   - Actualizar la cadena de conexión en el archivo de configuración con los datos de tu instancia de SQL Server

4. **Ejecutar el proyecto**
   - Compilar la solución `Proyecto-Final.sln`
   - Presionar `F5` o hacer clic en **Ejecutar** en Visual Studio

---

## 👥 Equipo de desarrollo

Proyecto realizado por:

- Emanuel Alejandro Celis
- Marcos Daniel Selvaggi
- Andrés Bellas Tolosa

**Grupo 3 — FRGP**

---

## 📄 Licencia

Este proyecto fue desarrollado con fines académicos.
