# 🎮 Propuesta de Capacitación en Git y GitHub

## 📖 Contexto

La empresa se encuentra desarrollando el proyecto **"Sistema Web de Agendamiento de Citas Médicas mediante Arquitectura Monolítica Modular aplicado a una Clínica Privada"**.

Debido a la incorporación de un nuevo Programador Junior, se propone una capacitación práctica basada en situaciones reales del proyecto para que adquiera experiencia utilizando Git y GitHub como herramientas de control de versiones y colaboración.

---

# 🎯 Objetivo de Aprendizaje

Al finalizar la capacitación, el Programador Junior será capaz de:

* Clonar repositorios remotos.
* Comprender la estructura de un proyecto colaborativo.
* Crear y administrar ramas de trabajo.
* Registrar cambios mediante commits descriptivos.
* Sincronizar cambios con GitHub.
* Resolver conflictos básicos.
* Crear Pull Requests.
* Revisar contribuciones de otros desarrolladores.
* Aplicar buenas prácticas de desarrollo colaborativo.

---

# 📋 Descripción de la Dinámica

La actividad será colaborativa y estará basada en el sistema de agendamiento de citas médicas desarrollado por el equipo.

Cada participante asumirá el rol de desarrollador dentro del proyecto y deberá completar una serie de misiones progresivas relacionadas con funcionalidades reales del sistema.

Cada misión representará una tarea común dentro del desarrollo del proyecto, como modificar la gestión de pacientes, actualizar la documentación o mejorar el módulo de citas.

El progreso será evaluado mediante commits, ramas, Pull Requests y participación en revisiones de código.

---

# 🎮 Retos o Misiones

## Nivel 1: Explorador del Proyecto

### Objetivo

Conocer el repositorio y la estructura del sistema.

### Actividades

* Clonar el repositorio del proyecto.
* Identificar módulos principales.
* Ejecutar la aplicación localmente.
* Revisar la documentación existente.

### Comandos

```bash
git clone URL_DEL_REPOSITORIO
git status
```

---

## Nivel 2: Gestor de Pacientes

### Objetivo

Aprender a trabajar con ramas.

### Actividades

* Crear una rama llamada `feature_pacientes`.
* Modificar la documentación del módulo de pacientes.
* Registrar cambios mediante commits.

### Comandos

```bash
git checkout -b feature_pacientes
git add .
git commit -m "Actualiza documentación del módulo de pacientes"
```

---

## Nivel 3: Administrador de Citas

### Objetivo

Trabajar con repositorios remotos.

### Actividades

* Actualizar la rama local.
* Subir cambios al repositorio remoto.
* Sincronizar cambios con la rama principal.

### Comandos

```bash
git pull origin main
git push origin feature_pacientes
```

---

## Nivel 4: Especialista en Integración

### Objetivo

Aprender el flujo de Pull Requests.

### Actividades

* Crear un Pull Request.
* Documentar los cambios realizados.
* Adjuntar evidencia del funcionamiento.

### Evidencias

* Captura del Pull Request.
* Descripción de cambios.
* Historial de commits.

---

## Nivel 5: Revisor de Código

### Objetivo

Participar en revisiones colaborativas.

### Actividades

* Revisar el Pull Request de otro integrante.
* Identificar mejoras.
* Aprobar cambios o solicitar correcciones.

---

# 📸 Evidencias de Aprendizaje

Cada participante deberá entregar:

1. Captura del repositorio clonado.
2. Captura de la rama creada.
3. Resultado de:

```bash
git branch
```

4. Resultado de:

```bash
git log --oneline
```

5. Captura del Pull Request generado.
6. Evidencia de revisión de código.
7. README actualizado.

---

# 📊 Criterios de Evaluación

| Criterio                           | Valor |
| ---------------------------------- | ----: |
| Clonación correcta del repositorio |   10% |
| Uso adecuado de ramas              |   20% |
| Calidad de commits                 |   15% |
| Uso de GitHub                      |   15% |
| Creación de Pull Requests          |   20% |
| Revisión de código                 |   10% |
| Evidencias entregadas              |   10% |

**Total: 100%**

---

# 💡 Preguntas de Reflexión

## 1. ¿Qué ventajas ofrece Git frente a guardar múltiples versiones de un archivo manualmente?

Git permite mantener un historial organizado de cambios, recuperar versiones anteriores y facilitar el trabajo colaborativo sin duplicar archivos.

## 2. ¿Por qué es importante trabajar mediante ramas?

Porque permite desarrollar nuevas funcionalidades sin afectar la versión estable del proyecto y facilita el trabajo simultáneo de varios desarrolladores.

## 3. ¿Qué beneficios aportan los Pull Requests en un equipo de desarrollo?

Permiten revisar cambios antes de integrarlos, detectar errores, mejorar la calidad del código y fomentar la colaboración.

## 4. ¿Cómo puede un líder técnico verificar que todos los integrantes están contribuyendo al proyecto?

Mediante el historial de commits, Pull Requests, revisiones de código y estadísticas de contribución en GitHub.

## 5. ¿Qué habilidades técnicas y de colaboración desarrolla un programador al utilizar Git y GitHub?

Control de versiones, trabajo en equipo, comunicación técnica, resolución de conflictos, documentación y buenas prácticas de desarrollo.

---

# 🏆 Desafío Extra

## GitHub Projects

Permite organizar tareas mediante tableros Kanban.

## GitHub Issues

Facilita el seguimiento de errores y mejoras.

## GitHub Actions

Automatiza pruebas y despliegues.

## GitLab

Plataforma alternativa para control de versiones y DevOps.

## Jira

Herramienta para la gestión de proyectos ágiles.

## Azure DevOps

Conjunto de herramientas para desarrollo, pruebas y despliegue de software.

Estas herramientas mejoran la organización, comunicación y productividad de los equipos de desarrollo.
