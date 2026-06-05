# 📜 README_REGLAMENTO.md

# Reglamento de Trabajo Colaborativo con Git y GitHub

## 🎯 Objetivo

Establecer las normas, responsabilidades y procedimientos que seguirá el equipo para desarrollar el proyecto de manera organizada, transparente y profesional utilizando Git y GitHub como herramientas de control de versiones.

---

# 👥 Información del Equipo

**Nombre del equipo:**

> Migaco

**Repositorio del proyecto:**

> Frontend: https://github.com/gus-p3/MigaCO-FrontEnd.git
> Backend: https://github.com/gus-p3/MigaCO-BackEnd.git

**Líder del proyecto:**

> Padrón Martínez Karen Anahí

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

### Ejemplos

```text
feature_login
feature_catalogo
feature_carrito
feature_pedidos
feature_api_tenant
```

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
git commit -m "Implementa módulo de catálogo por tenant"
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

### Ejemplo

```text
[CARRITO] Implementación del hook useCart con estrategia LocalStorage
```

---

## Descripción mínima

```markdown
### Descripción
Explicación breve del cambio realizado.

### Archivos modificados
- index.html
- css/style.css
- js/modulo.js

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
* Se respetó la estructura del proyecto.

---

# 🚫 Acciones No Permitidas

Queda prohibido:

* Trabajar directamente sobre la rama main.
* Eliminar archivos de otros integrantes sin autorización.
* Realizar commits sin descripción.
* Subir código sin probar.
* Aprobar su propio Pull Request.
* Fusionar cambios sin revisión previa.

---

# 📈 Seguimiento de Avances

Cada integrante deberá registrar semanalmente sus actividades.

## Bitácora de actividades

| Fecha      | Integrante | Actividad realizada | Commit o PR |
| ---------- | ---------- | ------------------- | ----------- |
| DD/MM/AAAA | Nombre     | Descripción         | #PR o Hash  |

### Ejemplo

| Fecha      | Integrante                    | Actividad realizada                     | Commit o PR |
| ---------- | ----------------------------- | --------------------------------------- | ----------- |
| 04/06/2026 | Padrón Martínez Karen Anahí   | Implementación del contexto de tenant   | PR #1       |
| 04/06/2026 | Mendoza Amaro Brandon Gustavo | Configuración de rutas con Express.js   | PR #2       |
| 04/06/2026 | Ramírez Ramírez Lizeth        | Integración de autenticación JWT        | PR #3       |

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

Ejemplo:

```text
15 Padrón Martínez Karen Anahí
12 Mendoza Amaro Brandon Gustavo
10 Ramírez Ramírez Lizeth
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

Se deberá observar actividad de todos los integrantes.

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
| -------------------------------- | ----- |
| Uso correcto de ramas            | 20%   |
| Uso adecuado de Pull Requests    | 20%   |
| Participación individual         | 20%   |
| Evidencias de commits            | 15%   |
| Documentación y bitácora         | 15%   |
| Calidad del trabajo colaborativo | 10%   |

---

# 🏆 Meta del Equipo

Lograr una colaboración organizada y profesional aplicando buenas prácticas de desarrollo de software utilizadas en proyectos reales de la industria.

---

## 🚀 Declaración de Compromiso

Todos los integrantes del equipo aceptan cumplir este reglamento y seguir las buenas prácticas de desarrollo colaborativo establecidas para el proyecto.

**Fecha de elaboración:** 04 / 06 / 2026

**Integrantes:**

* Padrón Martínez Karen Anahí
* Mendoza Amaro Brandon Gustavo
* Ramírez Ramírez Lizeth

✍️ Firma de aceptación del equipo.