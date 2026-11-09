# SupaMalla — Gestión y Planificación Académica

**Autor:** Luis Sebastian Shagñay Ruiz · Aplicación **Flutter** con backend en **Supabase**

SupaMalla es una herramienta de **gestión y planificación académica** pensada para estudiantes: permite **visualizar la malla curricular de su carrera de forma interactiva**, entender su ruta de estudio periodo a periodo y **seguir su progreso** a medida que avanza, en lugar de pelearse con el PDF oficial de la malla o con hojas de cálculo improvisadas.

Nació con un propósito concreto: ofrecer a los estudiantes una forma más intuitiva y visual de organizar su trayectoria académica y mantener al día sus objetivos de estudio.

## Funcionalidades

- **Planificación visual:** visualización interactiva de la malla curricular para comprender mejor la ruta de estudio completa.
- **Monitoreo estudiantil:** seguimiento del progreso del estudiante para mantener actualizados sus objetivos académicos.
- **Gestión de información académica:** estructura de base de datos diseñada específicamente para la gestión académica (carreras, mallas, asignaturas y avance del estudiante), sobre **Supabase** (PostgreSQL).
- **Versión web instalable (PWA):** la compilación web incluida en este repositorio se distribuye como aplicación web progresiva (manifiesto «Malla Academica», modo standalone, versión **1.0.1+2**).

## Sobre este repositorio

Este repositorio conserva la **versión web de SupaMalla**, generada con Flutter a partir de la aplicación móvil original. El código fuente (Dart) de la app no forma parte de este repositorio: lo que se versiona aquí es la compilación web lista para servirse.

```
SupaMalla/
├── index.html              # Entrada de la aplicación web
├── main.dart.js            # Aplicación Flutter compilada a JavaScript
├── flutter_bootstrap.js    # Arranque de Flutter web
├── flutter_service_worker.js
├── manifest.json           # Manifiesto PWA
├── version.json            # supamalla 1.0.1 (build 2)
├── assets/                 # Recursos de la aplicación compilada
├── canvaskit/              # Motor de renderizado de Flutter web
└── icons/                  # Iconos PWA (192/512, maskable)
```

## Stack

| Capa | Tecnología |
|---|---|
| Aplicación | Flutter (app móvil original; compilación web en este repositorio) |
| Backend / Base de datos | Supabase (PostgreSQL y API) |
| Distribución web | PWA (manifiesto, service worker, iconos maskable) |

## Estado del proyecto

SupaMalla se encuentra **en pausa**. La aplicación funcionó contra su base de datos original en Supabase, pero esa base de datos dejó de estar disponible; sin reconstruirla por completo, la aplicación ya no puede operar. Este repositorio se mantiene como registro fiel del trabajo realizado y de la solución construida: la planificación visual de mallas y el seguimiento de progreso quedaron implementados y desplegados en su momento, y la compilación web conservada aquí es la evidencia de ese producto.

**Autor:** Luis Sebastian Shagñay Ruiz — diseño y desarrollo de la aplicación y de su modelo de datos académico.
