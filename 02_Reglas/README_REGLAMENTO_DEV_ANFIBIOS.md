<div align="center">

<br>

<h1>📜 Reglamento de Trabajo Colaborativo</h1>
<h3>Git y GitHub — Equipo dev-anfibios</h3>

<br>

<img src="https://img.shields.io/badge/Equipo-dev--anfibios-1a1a2e?style=for-the-badge&labelColor=16213e&color=0f3460" alt="dev-anfibios"/>
<img src="https://img.shields.io/badge/Herramienta-Git%20%2B%20GitHub-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/Estado-Vigente-2ea44f?style=for-the-badge" alt="Estado"/>

</div>

---

## 🎯 Objetivo

Establecer las normas, responsabilidades y procedimientos que seguirá el equipo para desarrollar el proyecto de manera organizada, transparente y profesional, utilizando **Git** y **GitHub** como herramientas de control de versiones.

---

## 👥 Información del Equipo

<br>

<div align="center">

<table>
  <tbody>
    <tr>
      <td><b>🐸 Nombre del equipo</b></td>
      <td>dev-anfibios</td>
    </tr>
    <tr>
      <td><b>🔗 Repositorio del proyecto</b></td>
      <td><a href="https://github.com/Desarrollo-Web-Profesional-Garay/tu_selva_urbana">https://github.com/Desarrollo-Web-Profesional-Garay/tu_selva_urbana.git</a></td>
    </tr>
    <tr>
      <td><b>👑 Líder del proyecto</b></td>
      <td>Cesar Enrique Garay Garcia</td>
    </tr>
  </tbody>
</table>

</div>

<br>

<div align="center">

### Integrantes del Equipo

<table>
  <thead>
    <tr>
      <th align="center">No.</th>
      <th align="center">Nombre Completo</th>
      <th align="center">GitHub</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td align="center">Cesar Enrique Garay Garcia</td>
      <td align="center">
        <a href="https://github.com/Desarrollo-Web-Profesional-Garay">
          <img src="https://img.shields.io/badge/GitHub-CesarGaray-181717?style=flat&logo=github" alt="Cesar"/>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td align="center">Zahir Andres Rodriguez Mora</td>
      <td align="center">
        <a href="https://github.com/ZahirAndres">
          <img src="https://img.shields.io/badge/GitHub-ZahirAndres-181717?style=flat&logo=github" alt="Zahir"/>
        </a>
      </td>
    </tr>
  </tbody>
</table>

</div>

<br>

---

## 🤝 Principios de Trabajo en Equipo

Todos los integrantes se comprometen a:

- ✅ Mantener una comunicación respetuosa y profesional.
- ✅ Cumplir con las tareas asignadas en los tiempos acordados.
- ✅ Documentar adecuadamente sus cambios en cada commit.
- ✅ Utilizar Git y GitHub siguiendo los lineamientos establecidos en este reglamento.
- ✅ Participar activamente en las revisiones de código (Code Review).
- ✅ Informar oportunamente cualquier problema o retraso al líder del equipo.

---

## 📂 Estructura de Ramas

<br>

```
main                      ← Versiones estables y aprobadas únicamente
│
├── feature_login         ← Módulo de autenticación
├── feature_catalogo      ← Módulo del catálogo de plantas
├── feature_feed          ← Módulo del feed social
├── feature_checkout      ← Módulo de pago y carrito
├── feature_admin         ← Panel de administración
└── feature_perfil        ← Módulo de perfil de usuario
```

<br>

<div align="center">

| Tipo de Rama | Formato | Ejemplo |
|---|---|---|
| Rama principal | `main` | `main` |
| Módulo de trabajo | `feature_nombre_modulo` | `feature_login` |

</div>

<br>

> **Regla:** Queda **estrictamente prohibido** trabajar directamente sobre la rama `main`.

---

## 🔄 Flujo de Trabajo Obligatorio

<br>

### Paso 1 — Actualizar repositorio local

> Antes de comenzar cualquier actividad, sincronizar el repositorio local:

```bash
git checkout main
git pull origin main
```

### Paso 2 — Crear o actualizar rama de trabajo

```bash
# Crear nueva rama
git checkout -b feature_nombre_modulo

# O actualizar rama existente
git checkout feature_nombre_modulo
git pull origin main
```

### Paso 3 — Realizar cambios

> Desarrollar **únicamente** las funcionalidades asignadas a tu módulo. No modificar archivos de otros integrantes sin autorización previa.

### Paso 4 — Registrar cambios

```bash
git add .
git commit -m "Implementa módulo de contacto"
```

### Paso 5 — Subir cambios al repositorio remoto

```bash
git push origin feature_nombre_modulo
```

### Paso 6 — Crear Pull Request

Cada integrante deberá crear un **Pull Request** desde su rama hacia `main` en GitHub.

---

## ✅ Reglas para los Pull Requests

Todo Pull Request deberá incluir la siguiente estructura:

### Título
```
[MÓDULO] Descripción breve del cambio
```
**Ejemplo:** `[CATÁLOGO] Implementación de filtros por categoría`

### Descripción mínima

```markdown
### Descripción
Explicación breve del cambio realizado.

### Archivos modificados
- src/pages/Catalog.jsx
- src/components/FilterBar.jsx

### Evidencia
Adjuntar captura de pantalla o GIF del resultado.

### Pruebas realizadas
Describir las pruebas ejecutadas antes del PR.
```

---

## 👀 Revisión de Código

Antes de aprobar un Pull Request se deberá verificar:

- [ ] El proyecto sigue funcionando correctamente tras los cambios.
- [ ] No existen errores visibles en consola o interfaz.
- [ ] El código está ordenado, comentado y legible.
- [ ] No se eliminaron archivos de otros módulos.
- [ ] Se respetó la estructura de carpetas del proyecto.
- [ ] Los estilos son consistentes con el diseño general.

---

## 🚫 Acciones No Permitidas

<div align="center">

| ❌ Prohibido |
|---|
| Trabajar directamente sobre la rama `main` |
| Eliminar archivos de otros integrantes sin autorización |
| Realizar commits sin descripción o con mensajes vacíos |
| Subir código sin haber probado su funcionamiento |
| Aprobar tu propio Pull Request |
| Fusionar cambios sin revisión previa del equipo |

</div>

---

## 📈 Seguimiento de Avances — Bitácora

<div align="center">

| Fecha | Integrante | Actividad realizada | Commit o PR |
|-------|-----------|---------------------|-------------|
| 04/06/2026 | Cesar Enrique Garay Garcia | Configuración inicial del proyecto y estructura base | `a17cf8e` |
| 04/06/2026 | Cesar Enrique Garay Garcia | Mejora de documentación del README | PR #1 |
| 04/06/2026 | Zahir Andres Rodriguez Mora | Desarrollo de interfaz frontend | `Front-ZahirAndres` |
| DD/MM/AAAA | — | — | — |

</div>

---

## 🔍 Auditoría y Evidencia de Participación

### Evidencia 1 — Historial de Commits
```bash
git log --oneline
```

### Evidencia 2 — Commits por Autor
```bash
git shortlog -sn
```
Resultado esperado:
```
15  Cesar Enrique Garay Garcia
12  Zahir Andres Rodriguez Mora
```

### Evidencia 3 — Pull Requests Realizados
> Cada integrante deberá generar **al menos 2 Pull Requests** durante el desarrollo del proyecto.

### Evidencia 4 — Contribuciones en GitHub
> Verificar en: `Insights → Contributors`
> Se deberá observar actividad de **todos** los integrantes.

### Evidencia 5 — Historial de Cambios
> Verificar: Pull Requests · Commits · Issues · Projects

---

## 📊 Criterios de Evaluación del Trabajo Colaborativo

<div align="center">

| Criterio | Valor |
|---|:---:|
| Uso correcto de ramas | 20% |
| Uso adecuado de Pull Requests | 20% |
| Participación individual | 20% |
| Evidencias de commits | 15% |
| Documentación y bitácora | 15% |
| Calidad del trabajo colaborativo | 10% |
| **Total** | **100%** |

</div>

---

## 🏆 Meta del Equipo

> Lograr una colaboración organizada y profesional aplicando buenas prácticas de desarrollo de software utilizadas en proyectos reales de la industria tecnológica.

---

## 🚀 Declaración de Compromiso

Todos los integrantes del equipo **dev-anfibios** aceptan cumplir este reglamento y seguir las buenas prácticas de desarrollo colaborativo establecidas para el proyecto.

<br>

<div align="center">

**Fecha de elaboración:** &nbsp; 04 &nbsp;/&nbsp; 06 &nbsp;/&nbsp; 2026

<br>

<table>
  <thead>
    <tr>
      <th align="center">✍️ Integrante</th>
      <th align="center">Firma de Aceptación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Cesar Enrique Garay Garcia</td>
      <td align="center"><i>— Acepto los términos del reglamento —</i></td>
    </tr>
    <tr>
      <td align="center">Zahir Andres Rodriguez Mora</td>
      <td align="center"><i>— Acepto los términos del reglamento —</i></td>
    </tr>
  </tbody>
</table>

<br>

<sub>📅 Documento generado por el equipo <b>dev-anfibios</b> · Desarrollo Web Profesional Garay · 2026</sub>

</div>
