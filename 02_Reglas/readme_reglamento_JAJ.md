# 📜 Reglamento de Trabajo Colaborativo con Git y GitHub

## 🎯 Objetivo

Establecer las normas, responsabilidades y procedimientos que seguirá el equipo para desarrollar el proyecto de manera organizada, transparente y profesional utilizando Git y GitHub como herramientas de control de versiones.

---

# 👥 Información del Equipo

**Nombre del equipo:**

> Equipo_JAJ

**Repositorio del proyecto:**

> https://github.com/SekiroK5/AgendaCultural

**Líder del proyecto:**

> Chavero Martínez Noé

---

# 🤝 Principios de Trabajo en Equipo

Todos los integrantes se comprometen a:

* Mantener una comunicación respetuosa y profesional.
* Cumplir con las tareas asignadas.
* Documentar adecuadamente sus cambios.
* Utilizar Git y GitHub siguiendo los lineamientos establecidos.
* Participar activamente en las revisiones de código.
* Informar oportunamente cualquier problema o retraso.

---

# 📂 Estructura de Ramas

Para evitar conflictos, cada integrante trabajará en una rama independiente.

## Rama principal

```text
main
```

Contendrá únicamente versiones estables y aprobadas del proyecto.

---

## Ramas de trabajo

Cada integrante deberá crear una rama con el siguiente formato:

```text
feature_nombre_modulo
```

### Ramas asignadas por integrante

| Integrante                      | Rama asignada              | Módulo                          |
|---------------------------------|----------------------------|---------------------------------|
| Chavero Martínez Noé            | `feature_autenticacion`    | HU-01 — Registro y autenticación JWT |
| Cruz Méndez Juan Gustavo Ángel  | `feature_boletos`          | HU-02 — Compra de boletos y QR  |
| Salinas Salinas Omar            | `feature_streaming`        | HU-04 — Transmisión en vivo HLS |

---

# 🔄 Flujo de Trabajo Obligatorio

## Paso 1. Actualizar repositorio local

Antes de comenzar cualquier actividad:

```bash
git checkout main
git pull origin main
```

---

## Paso 2. Crear o actualizar rama de trabajo

```bash
git checkout -b feature_nombre_modulo
```

o

```bash
git checkout feature_nombre_modulo
git pull origin main
```

---

## Paso 3. Realizar cambios

Desarrollar únicamente las funcionalidades asignadas.

---

## Paso 4. Registrar cambios

```bash
git add .
git commit -m "feat: implementa módulo de autenticación JWT"
```

---

## Paso 5. Subir cambios al repositorio remoto

```bash
git push origin feature_nombre_modulo
```

---

## Paso 6. Crear Pull Request (PR)

Cada integrante deberá crear un Pull Request hacia la rama:

```text
main
```

---

# ✅ Reglas para los Pull Request

Todo Pull Request deberá incluir:

## Título

```text
[MÓDULO] Descripción breve del cambio
```

### Ejemplos del proyecto

```text
[AUTENTICACION] Implementación de registro y login con JWT
[BOLETOS] Generación de código QR al completar compra
[STREAMING] Integración de ExoPlayer con protocolo HLS
```

---

## Descripción mínima

```markdown
### Descripción
Explicación breve del cambio realizado.

### Archivos modificados
- MainActivity.kt
- AuthRepository.kt
- network/NetworkModule.kt

### Evidencia
Adjuntar captura de pantalla.

### Pruebas realizadas
Describir pruebas ejecutadas.
```

---

# 👀 Revisión de Código

Antes de aprobar un Pull Request se deberá verificar:

* El proyecto sigue funcionando correctamente.
* No existen errores visibles.
* El código está ordenado y documentado.
* No se eliminaron archivos importantes.
* Se respetó la arquitectura MVVM del proyecto.
* Los interceptores JWT están correctamente configurados en `NetworkModule`.

---

# 🚫 Acciones No Permitidas

Queda prohibido:

* Trabajar directamente sobre la rama `main`.
* Eliminar archivos de otros integrantes sin autorización.
* Realizar commits sin descripción.
* Subir código sin probar.
* Aprobar su propio Pull Request.
* Fusionar cambios sin revisión previa.

---

# 📈 Seguimiento de Avances

Cada integrante deberá registrar semanalmente sus actividades.

## Bitácora de actividades

| Fecha      | Integrante                      | Actividad realizada | Commit o PR |
|------------|---------------------------------|---------------------|-------------|
| DD/MM/AAAA | Chavero Martínez Noé            | Descripción         | #PR o Hash  |
| DD/MM/AAAA | Cruz Méndez Juan Gustavo Ángel  | Descripción         | #PR o Hash  |
| DD/MM/AAAA | Salinas Salinas Omar            | Descripción         | #PR o Hash  |

### Ejemplo

| Fecha      | Integrante           | Actividad realizada                        | Commit o PR |
|------------|----------------------|--------------------------------------------|-------------|
| 21/05/2026 | Chavero Martínez Noé | Configuración de OkHttp JWT Interceptor    | PR #1       |
| 21/05/2026 | Salinas Salinas Omar | Integración de ExoPlayer con ViewModel     | PR #2       |

---

# 🔍 Auditoría y Evidencia de Participación

El equipo deberá demostrar la participación de todos los integrantes mediante:

## Evidencia 1. Historial de Commits

Revisar:

```bash
git log --oneline
```

---

## Evidencia 2. Commits por Autor

Revisar:

```bash
git shortlog -sn
```

Ejemplo esperado:

```text
15  Chavero Martinez Noe
12  Cruz Mendez Juan Gustavo Angel
10  Salinas Salinas Omar
```

---

## Evidencia 3. Pull Requests Realizados

Cada integrante deberá generar al menos:

* 2 Pull Requests durante el desarrollo.

---

## Evidencia 4. Contribuciones en GitHub

Verificar en:

```text
Insights → Contributors
```

Se deberá observar actividad de los tres integrantes.

---

## Evidencia 5. Historial de Cambios

Verificar:

```text
Pull Requests
Commits
Issues
Projects
```

---

# 📊 Criterios de Evaluación del Trabajo Colaborativo

| Criterio                         | Valor |
|----------------------------------|-------|
| Uso correcto de ramas            | 20%   |
| Uso adecuado de Pull Requests    | 20%   |
| Participación individual         | 20%   |
| Evidencias de commits            | 15%   |
| Documentación y bitácora         | 15%   |
| Calidad del trabajo colaborativo | 10%   |

---

# 🏆 Meta del Equipo

Lograr una colaboración organizada y profesional en el desarrollo de **FestivalTrack**, aplicando buenas prácticas de desarrollo de software utilizadas en proyectos reales de la industria, siguiendo la arquitectura **MVVM** con el stack **Retrofit 2 + Kotlin Coroutines + Jetpack**.

---

## 🚀 Declaración de Compromiso

Todos los integrantes del equipo aceptan cumplir este reglamento y seguir las buenas prácticas de desarrollo colaborativo establecidas para el proyecto.

**Fecha de elaboración:** 21 / 05 / 2026

**Integrantes:**

* Chavero Martínez Noé — `1223100837`
* Cruz Méndez Juan Gustavo Ángel — `1223100406`
* Salinas Salinas Omar — `1223100433`

✍️ Firma de aceptación del equipo.