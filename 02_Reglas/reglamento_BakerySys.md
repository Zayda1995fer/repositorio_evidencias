# Reglamento de Trabajo Colaborativo con Git y GitHub

---

## Objetivo

Establecer las normas, responsabilidades y procedimientos que seguirá el equipo de desarrollo de BakerySys para garantizar un flujo de trabajo ordenado, eficiente y profesional utilizando Git y GitHub como plataformas de control de versiones y colaboración.

---

## Información del Equipo

* **Nombre del equipo:** BakerySys
* **Repositorio del proyecto:** https://github.com/PaolaLpez/Panader-a.git
* **Líder del proyecto:** Paola Jaqueline López Mata

---

## Principios de Trabajo en Equipo

Todos los integrantes del equipo se comprometen a:

* Mantener una comunicación respetuosa, clara y orientada a soluciones.
* Cumplir con las tareas y funcionalidades asignadas dentro de los plazos acordados.
* Documentar adecuadamente cada cambio realizado en el código.
* Seguir estrictamente los lineamientos de uso de Git y GitHub.
* Participar activamente en las revisiones de código (Pull Requests).
* Reportar oportunamente cualquier bloqueo, error o retraso al líder del proyecto.

---

## Estructura de Ramas

### Rama Principal

`main`

Contendrá únicamente versiones estables, probadas y aprobadas del proyecto.

### Ramas de Trabajo por Funcionalidad

* `feature/registro-productos`
* `feature/registro-ventas`
* `feature/gestion-materias-primas`
* `feature/reportes-ventas`
* `feature/control-accesos`
* `feature/frontend-bakery`

Cada nueva funcionalidad o corrección deberá desarrollarse en una rama específica derivada de `main`.

---

## Flujo de Trabajo Obligatorio

### Paso 1. Actualizar la Rama Principal Localmente

```bash
git checkout main
git pull origin main
```

### Paso 2. Crear una Nueva Rama para la Funcionalidad

```bash
git checkout -b feature/nombre-funcionalidad
```

### Paso 3. Desarrollar Únicamente la Tarea Asignada

Realizar los cambios necesarios sin afectar otras partes del sistema.

### Paso 4. Registrar los Cambios Realizados

```bash
git add .
git commit -m "Descripción clara y concisa del cambio"
```

### Paso 5. Subir la Rama al Repositorio Remoto

```bash
git push origin feature/nombre-funcionalidad
```

### Paso 6. Crear un Pull Request hacia la Rama Main

* Solicitar revisión de al menos un integrante antes de fusionar.

---

## Reglas para los Pull Requests

Todo Pull Request deberá incluir obligatoriamente:

### Título

```text
[Módulo] Breve descripción del cambio
```

### Contenido Requerido

* Descripción detallada del cambio realizado.
* Archivos modificados (lista o rutas).
* Evidencia visual (captura de pantalla del funcionamiento).
* Pruebas realizadas (entornos, casos de prueba y resultados).

**No se aprobará ningún Pull Request que no cumpla con estos requisitos.**

---

## Acciones No Permitidas

Queda estrictamente prohibido:

* Trabajar o realizar commits directamente sobre la rama `main`.
* Eliminar o sobrescribir archivos de otros integrantes sin autorización expresa.
* Realizar commits sin un mensaje descriptivo y significativo.
* Subir código que no haya sido probado localmente.
* Aprobar su propio Pull Request.
* Fusionar cambios sin al menos una revisión aprobada por otro integrante.

---

## Bitácora de Actividades

| Fecha      | Integrante                      | Actividad realizada                                         | Commit o PR |
| ---------- | ------------------------------- | ----------------------------------------------------------- | ----------- |
| 04/06/2026 | Paola Jaqueline López Mata      | Configuración inicial del repositorio y estructura de ramas | PR #1       |
| 04/06/2026 | Gerardo Manzano Villafaña       | Creación del módulo de registro de productos                | PR #2       |
| 04/06/2026 | Jennifer Ailin Medina Hernández | Implementación de gestión de materias primas                | PR #3       |
| 04/06/2026 | Mildred Mariana Banda López     | Desarrollo del módulo de ventas y descuento de inventario   | PR #4       |

---

## Evidencias de Participación

### Evidencia 1 — Historial de Commits del Equipo

```bash
git log --oneline --graph --all
```

### Evidencia 2 — Conteo de Commits por Integrante

```bash
git shortlog -sn
```

### Evidencia 3 — Pull Requests Realizados

Cada integrante deberá generar al menos **2 Pull Requests** durante el desarrollo del proyecto.

---

## Criterios de Evaluación

| Criterio                                | Valor |
| --------------------------------------- | ----- |
| Uso correcto del modelo de ramas        | 20%   |
| Calidad y cumplimiento de Pull Requests | 20%   |
| Participación activa individual         | 20%   |
| Evidencias de commits y actividad       | 15%   |
| Bitácora actualizada y documentación    | 15%   |
| Trabajo colaborativo y respeto a normas | 10%   |

---

## Declaración de Compromiso

Los integrantes del equipo BakerySys aceptan cumplir con cada uno de los puntos establecidos en el presente reglamento.

### Fecha de Elaboración

**04 de junio de 2026**

### Integrantes

* Paola Jaqueline López Mata
* Gerardo Manzano Villafaña
* Jennifer Ailin Medina Hernández
* Mildred Mariana Banda López
