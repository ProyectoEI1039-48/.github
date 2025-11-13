# **Proyecto de Prácticas: App de Movilidad (EI1039 / EI1048)**
**Grupo CaDaMi**

![Status](https://img.shields.io/badge/Status-En%20Desarrollo-yellow) ![License](https://img.shields.io/badge/License-MIT-blue)

Bienvenidos al repositorio de organización del proyecto conjunto para las asignaturas **EI1039 - Diseño de Software** y **EI1048 - Paradigmas de Software** de la Universitat Jaume I. Este espacio centraliza la documentación general, la planificación y el acceso al código fuente.

---

## **1. Sobre el Proyecto** 

El objetivo principal es desarrollar una aplicación de movilidad sostenible y eficiente. El sistema permite a los usuarios planificar sus desplazamientos teniendo en cuenta no solo la distancia, sino también el tiempo y el coste (económico o energético).

### **Funcionalidades Clave:**
* **Gestión de Usuarios:** Registro, autenticación y gestión de perfil.
* **Lugares de Interés (POI):** Creación y gestión de ubicaciones personalizadas (Casa, Trabajo, etc.).
* **Gestión de Vehículos:** Configuración de vehículos propios (consumo, tipo de combustible) para cálculos precisos.
* **Cálculo de Rutas:** Obtención de rutas óptimas conectando con APIs externas de mapas.
* **Estimación de Costes:** Cálculo del coste del trayecto en € (combustible) o Kilocalorías (caminando/bici).

### **Filosofía de Desarrollo:**
El proyecto sigue estrictamente la metodología ágil **ATDD (Acceptance Test-Driven Development)**. Priorizamos un diseño de software robusto, aplicando **Patrones de Diseño** y manteniendo una **Arquitectura Desacoplada** para asegurar la mantenibilidad y escalabilidad.

---

## **2. Repositorios y Manuales de Instalación** �

El código del proyecto está desacoplado en dos repositorios principales. **Para ver las guías de instalación y ejecución paso a paso, por favor visita el repositorio correspondiente:**

| Componente | Descripción | Enlace al Repositorio |
| :--- | :--- | :--- |
| **Backend ** | Lógica de negocio, gestión de datos y conexión con APIs externas (NestJS). | [ Ir al Repositorio Backend](https://github.com/ProyectoEI1039-48/back) |
| **Frontend ** | Interfaz de usuario web/móvil e interacción con mapas (React/Vite). | [ Ir al Repositorio Frontend](https://github.com/ProyectoEI1039-48/front). |

---

## **3. Arquitectura del Sistema** 

El sistema sigue una arquitectura cliente-servidor desacoplada. El Backend actúa como una fachada para los servicios externos, normalizando los datos para el Frontend.


## **4. Stack Tecnológico** 

* **Backend:** NestJS, TypeScript.
* **Frontend:** React, Vite, TypeScript.
* **Testing:** 
* **Mapas:** Leaflet.
* Control de Versiones:** GitHub.



---

## **5. Equipo de Desarrollo** 

| Nombre | Email | Usuario de GitHub |
| :--- | :--- | :--- |
| **Miguel Ruiz Tena** | al408883@uji.es | [`MiguelRT27`](https://github.com/MiguelRT27) |
| **Alexandru Dragomir** | al394814@uji.es | [`al394814`](https://github.com/al394814) |
| **Carlos Mestre González** | al386101@uji.es | [`bujapetas`](https://github.com/bujapetas) |
| **Daniel González Mingarro** | al416791@uji.es | [`raky76`](https://github.com/raky76) |

---

## **6. Licencia** 

Este proyecto se distribuye bajo la licencia **MIT**. 

---
*Proyecto desarrollado para el curso académico 2025/2026 - Universitat Jaume I.*
