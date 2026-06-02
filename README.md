# 🚀 Práctica 03: Contribución a un Proyecto Open Source mediante Fork y Pull Request

## 🎯 Objetivo

Aplicar un flujo de trabajo profesional utilizando Git y GitHub mediante la creación de un Fork de un repositorio Open Source, la clonación del repositorio personal, la creación de una rama de desarrollo, la modificación de documentación técnica y la generación de un Pull Request.

---

# 📚 Competencias a desarrollar

Al finalizar la práctica el estudiante será capaz de:

* Realizar Forks de proyectos Open Source.
* Clonar repositorios remotos.
* Crear y administrar ramas.
* Modificar documentación en Markdown.
* Registrar cambios mediante commits.
* Sincronizar repositorios locales y remotos.
* Crear Pull Requests.
* Aplicar flujos de colaboración profesional.

---

# 🌐 Repositorios sugeridos

Seleccione uno de los siguientes proyectos:

| Proyecto            | URL                                             |
| ------------------- | ----------------------------------------------- |
| Next.js             | https://github.com/vercel/next.js               |
| Gatsby              | https://github.com/gatsbyjs/gatsby              |
| Refine              | https://github.com/refinedev/refine             |
| WebArena            | https://github.com/Anadee11/WebArena            |
| Simple WebApp Flask | https://github.com/mmumshad/simple-webapp-flask |

---

# 🏢 Escenario

Has sido invitado a colaborar en un proyecto Open Source.

El equipo de desarrollo solicita mejorar la documentación para facilitar la incorporación de nuevos desarrolladores.

Las modificaciones se realizarán exclusivamente sobre el archivo:

```text
README.md
```

---

# 🔀 Parte 1. Realizar Fork

1. Ingresar al repositorio seleccionado.
2. Presionar el botón:

```text
Fork
```

3. Crear una copia en su cuenta personal de GitHub.

Resultado esperado:

```text
Repositorio Original
        ↓
      Fork
        ↓
Repositorio Personal
```

Ejemplo:

```text
vercel/next.js
        ↓
usuario/next.js
```
<img width="1913" height="1032" alt="image" src="https://github.com/user-attachments/assets/01e2ed4c-ecce-415d-aa0f-bdf169b9905b" />
<img width="1913" height="1026" alt="image" src="https://github.com/user-attachments/assets/b1a551ba-0179-4f09-9e65-4a5f8d0905b9" />

---

# 📥 Parte 2. Clonar el Fork

Clonar el repositorio que se encuentra en su cuenta personal.

```bash
git clone https://github.com/USUARIO/REPOSITORIO.git
```

Ejemplo:

```bash
git clone https://github.com/jose/next.js.git
```

Ingresar al proyecto:

```bash
cd REPOSITORIO
```

Verificar:

```bash
git status
```
<img width="1447" height="657" alt="image" src="https://github.com/user-attachments/assets/32529a7c-357b-4e2a-b6a1-f047c3082e8e" />

---


# 🌿 Parte 3. Crear rama de desarrollo

Crear una rama llamada:

```text
dev
```

```bash
git checkout -b dev
```

Verificar:

```bash
git branch
```

Resultado esperado:

```text
* dev
  main
```

<img width="1431" height="242" alt="image" src="https://github.com/user-attachments/assets/8eb448ea-0580-4882-966d-cfff6f840041" />


---

# 🔗 Parte 4. Configurar repositorio original (upstream)

Agregar referencia al proyecto original.

```bash
git remote add upstream URL_REPOSITORIO_ORIGINAL
```

Ejemplo:

```bash
git remote add upstream https://github.com/vercel/next.js.git
```

Verificar:

```bash
git remote -v
```

Resultado esperado:

```text
origin    https://github.com/usuario/next.js.git
upstream  https://github.com/vercel/next.js.git
```

<img width="1471" height="210" alt="image" src="https://github.com/user-attachments/assets/80784db1-5a59-4412-849f-33eb646bf743" />

---

# 📝 Parte 5. Modificar README.md

Agregar la siguiente sección:

```markdown
# Student Contribution

## Developer Information

- Name:
- University:
- Date:

## Proposed Improvements

1.
2.
3.

## Observations

Lorem ipsum...
```
<img width="843" height="741" alt="image" src="https://github.com/user-attachments/assets/9aa74ddd-62e1-45fd-abe7-ed67af5a1f4b" />

---

# 🎯 Parte 6. Actividades obligatorias

*Estas son sobre el Proyecto a realizar en equipo*

## 🏆 Actividad A. Fortalezas del proyecto

Agregar:

```markdown
## Project Strengths
```

Describir al menos 5 fortalezas.

---

## 🔧 Actividad B. Oportunidades de mejora

Agregar:

```markdown
## Improvement Opportunities
```

Describir al menos 5 oportunidades de mejora.

---

## 📊 Actividad C. Tabla Markdown

Agregar una tabla de tecnologías utilizadas.

---

## 🗺️ Actividad D. Diagrama Mermaid

Agregar un diagrama de arquitectura.

Ejemplo:

````markdown
```mermaid
graph LR
A[Cliente] --> B[Aplicación Web]
B --> C[Base de Datos]
```
````

---

## 📋 Actividad E. Requerimientos funcionales

Definir al menos 10 requerimientos funcionales.

Ejemplo:

```text
RF-01 El sistema deberá permitir el registro de usuarios.
RF-02 El sistema deberá permitir la autenticación de usuarios.
```


<img width="1131" height="1002" alt="image" src="https://github.com/user-attachments/assets/6b82f1e1-a3c1-45cb-81dd-b0e624b32855" />

<img width="1478" height="1036" alt="image" src="https://github.com/user-attachments/assets/841a6148-940a-40f8-9fd1-b86ba2c74e49" />

---

# 💾 Parte 7. Registrar cambios

Agregar cambios:

```bash
git add README.md
```

Crear commit:

```bash
git commit -m "docs: improve project documentation"
```

Verificar:

```bash
git log --oneline
```
<img width="1892" height="1052" alt="image" src="https://github.com/user-attachments/assets/cca71179-cb77-4736-92ad-3b4b75773432" />

---

# ☁️ Parte 8. Publicar cambios

Enviar la rama al Fork personal.

```bash
git push origin dev
```
<img width="955" height="380" alt="image" src="https://github.com/user-attachments/assets/cc967416-914c-4beb-85de-351e9bcc8135" />

---

# 🔄 Parte 9. Sincronizar con proyecto original

Actualizar desde el repositorio principal.

```bash
git checkout main

git fetch upstream

git merge upstream/main
```

Regresar a la rama de trabajo:

```bash
git checkout dev
```

---

<img width="927" height="392" alt="image" src="https://github.com/user-attachments/assets/16d50ed7-46dd-45ec-8263-45c1848d855e" />


# 🔀 Parte 10. Crear Pull Request

Ingresar a GitHub.

Seleccionar:

```text
Compare & Pull Request
```

Configuración:

```text
Base Repository:
Repositorio Original

Base Branch:
main

Head Repository:
Fork Personal

Compare Branch:
dev
```

Título:

```text
Improve README documentation
```

Descripción:

```markdown
## Changes

- Added contributor information
- Added strengths analysis
- Added improvement opportunities
- Added Mermaid diagram
- Added functional requirements

## Evidence

README updated successfully.
```

Enviar Pull Request.

<img width="1895" height="813" alt="image" src="https://github.com/user-attachments/assets/233a1bf9-d456-44e5-9aed-3d8d45517af4" />

<img width="1918" height="955" alt="image" src="https://github.com/user-attachments/assets/027f1b29-88dd-4953-8601-e1c9554278e1" />

https://github.com/mmumshad/simple-webapp-flask/pull/78

# https://github.com/mmumshad/simple-webapp-flask/pull/78


---


# 🏅 Reto adicional

Crear una segunda rama:

```bash
git checkout -b feature/profile
```

Agregar una nueva sección:

```markdown
## Team Members
```

Realizar:

```bash
git add .
git commit -m "feat: add team members section"
git push origin feature/profile
```

Generar Pull Request:

```text
feature/profile → dev
```

<img width="1872" height="878" alt="image" src="https://github.com/user-attachments/assets/4a6c3ac3-283f-496d-8305-5a5d8a4ea8f0" />
<img width="610" height="76" alt="image" src="https://github.com/user-attachments/assets/025879c7-997c-4ab6-b5c7-cbd052727e04" />


---

# 📖 Comandos utilizados

```bash
git clone
git remote
git remote add
git fetch
git branch
git checkout
git status
git add
git commit
git push
git merge
git log
```

---

# 📊 Criterios de evaluación

| Criterio                  | Valor |
| ------------------------- | ----: |
| Fork del repositorio      |   15% |
| Configuración de upstream |   10% |
| Uso de rama dev           |   15% |
| Modificaciones al README  |   30% |
| Pull Request              |   20% |
| Evidencias                |   10% |

## 🎯 Calificación Total

**100 puntos**

