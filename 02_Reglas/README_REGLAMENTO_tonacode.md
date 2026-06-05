# 📜 Reglamento de Trabajo Colaborativo con Git y GitHub

## 🎯 Objetivo

Establecer las normas, responsabilidades y procedimientos que seguirá el equipo para desarrollar el proyecto de manera organizada, transparente y profesional utilizando Git y GitHub como herramientas de control de versiones.

## 👥 Información del Equipo

**Nombre del equipo:** OllinTech

**Repositorio del proyecto:** https://mmildred.github.io/

**Líder del proyecto:** Mildred Mariana Banda López

## 🤝 Principios de Trabajo en Equipo

Todos los integrantes se comprometen a:

* Mantener una comunicación respetuosa y profesional.
* Cumplir con las actividades asignadas.
* Documentar adecuadamente los cambios realizados.
* Utilizar Git y GitHub siguiendo las buenas prácticas.
* Participar en revisiones de código y documentación.
* Informar oportunamente cualquier problema o retraso.

## 📂 Estructura de Ramas

**Rama principal:** `main`

**Ramas de trabajo:**

* `feature_autenticacion`
* `feature_pacientes`
* `feature_citas`
* `feature_reportes`

## 🔄 Flujo de Trabajo Obligatorio

### Paso 1. Actualizar repositorio local

```bash
git checkout main
git pull origin main
```

### Paso 2. Crear rama de trabajo

```bash
git checkout -b feature_nombre_modulo
```

### Paso 3. Realizar cambios

Desarrollar únicamente la funcionalidad asignada.

### Paso 4. Registrar cambios

```bash
git add .
git commit -m "Implementa módulo correspondiente"
```

### Paso 5. Subir cambios

```bash
git push origin feature_nombre_modulo
```

### Paso 6. Crear Pull Request hacia main

## ✅ Reglas para los Pull Request

Todo Pull Request deberá incluir:

* Título descriptivo.
* Descripción de los cambios realizados.
* Archivos modificados.
* Evidencia visual cuando aplique.
* Validación de funcionamiento.

## 🚫 Acciones No Permitidas

* Trabajar directamente sobre la rama main.
* Eliminar trabajo de otros integrantes sin autorización.
* Realizar commits sin descripción.
* Subir cambios sin revisar.
* Aprobar sus propios Pull Requests.
* Fusionar cambios sin revisión previa.

## 📈 Bitácora de Actividades

| Fecha      | Integrante                   | Actividad realizada                 | Commit o PR |
| ---------- | ---------------------------- | ----------------------------------- | ----------- |
| 04/06/2026 | Mildred Mariana Banda López  | Configuración inicial del proyecto  | PR #1       |
| 04/06/2026 | Zayda Fernanda Vargas Vargas | Documentación del proyecto          | PR #2       |
| 04/06/2026 | Juan Diego Juárez Cruz       | Organización de ramas y repositorio | PR #3       |

## 🔍 Evidencias de Participación

### Evidencia 1 — Historial de Commits

```bash
git log --oneline
```

### Evidencia 2 — Commits por Autor

```bash
git shortlog -sn
```

### Evidencia 3 — Pull Requests

Cada integrante deberá generar al menos 2 Pull Requests.

## 🚀 Declaración de Compromiso

Todos los integrantes del equipo aceptan cumplir este reglamento.

**Fecha de elaboración:** 04 / 06 / 2026

**Integrantes:**

* ✍️ Mildred Mariana Banda López
* ✍️ Zayda Fernanda Vargas Vargas
* ✍️ Juan Diego Juárez Cruz
