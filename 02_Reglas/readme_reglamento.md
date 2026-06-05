# 📜 Reglamento de Trabajo Colaborativo con Git y GitHub

## 🎯 Objetivo
Establecer las normas, responsabilidades y procedimientos que seguirá el equipo para desarrollar el proyecto de manera organizada, transparente y profesional utilizando Git y GitHub como herramientas de control de versiones.

## 👥 Información del Equipo

**Nombre del equipo:** MarketPlaze

**Repositorio del proyecto:** https://github.com/MiguelAlvarezIbarra/TraffiCandy

**Líder del proyecto:** Miguel Angel Alvares Ibarra

## 🤝 Principios de Trabajo en Equipo
Todos los integrantes se comprometen a:

- Mantener una comunicación respetuosa y profesional.
- Cumplir con las tareas asignadas.
- Documentar adecuadamente sus cambios.
- Utilizar Git y GitHub siguiendo los lineamientos establecidos.
- Participar activamente en las revisiones de código.
- Informar oportunamente cualquier problema o retraso.

## 📂 Estructura de Ramas

**Rama principal:** `main`
Contendrá únicamente versiones estables y aprobadas del proyecto.

**Ramas de trabajo:**
- `feature_inicio`
- `feature_productos`
- `feature_contacto`
- `feature_galeria`

## 🔄 Flujo de Trabajo Obligatorio

**Paso 1. Actualizar repositorio local**
```bash
git checkout main
git pull origin main
```

**Paso 2. Crear o actualizar rama de trabajo**
```bash
git checkout -b feature_nombre_modulo
```

**Paso 3. Realizar cambios**
Desarrollar únicamente las funcionalidades asignadas.

**Paso 4. Registrar cambios**
```bash
git add .
git commit -m "Implementa módulo correspondiente"
```

**Paso 5. Subir cambios**
```bash
git push origin feature_nombre_modulo
```

**Paso 6. Crear Pull Request hacia `main`**

## ✅ Reglas para los Pull Request
Todo Pull Request deberá incluir:

- **Título:** `[MÓDULO] Descripción breve del cambio`
- **Descripción** del cambio realizado
- **Archivos modificados**
- **Evidencia** (captura de pantalla)
- **Pruebas realizadas**

## 🚫 Acciones No Permitidas
- Trabajar directamente sobre la rama `main`
- Eliminar archivos de otros integrantes sin autorización
- Realizar commits sin descripción
- Subir código sin probar
- Aprobar su propio Pull Request
- Fusionar cambios sin revisión previa

## 📈 Bitácora de Actividades

| Fecha | Integrante | Actividad realizada | Commit o PR |
|-------|-----------|---------------------|-------------|
| 01/06/2026 | Miguel Angel Alvares Ibarra | Configuración inicial del proyecto | PR #1 |
| 01/06/2026 | Pedro Uriel Perez Monzon | Agrega información del equipo | PR #3 |
| 01/06/2026 | Claudio Angel Huerta Ducoing | Configuración de ramas | PR #2 |

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

## 📊 Criterios de Evaluación

| Criterio | Valor |
|----------|-------|
| Uso correcto de ramas | 20% |
| Uso adecuado de Pull Requests | 20% |
| Participación individual | 20% |
| Evidencias de commits | 15% |
| Documentación y bitácora | 15% |
| Calidad del trabajo colaborativo | 10% |

## 🚀 Declaración de Compromiso
Todos los integrantes del equipo aceptan cumplir este reglamento.

**Fecha de elaboración:** 01 / 06 / 2026

**Integrantes:**
- ✍️ Miguel Angel Alvares Ibarra
- ✍️ Pedro Uriel Perez Monzon
- ✍️ Claudio Angel Huerta Ducoing