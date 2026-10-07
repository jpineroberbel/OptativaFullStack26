# Práctica Final: "DevDex — El Portal de Developers del Curso"

## 📄 Enunciado General y Contexto del Proyecto

En el ámbito del desarrollo de software profesional, trabajar en un proyecto no se reduce a escribir código individualmente, sino a coordinarse en equipo mediante un sistema de control de versiones.

Durante los próximos **90 - 120 minutos**, tu equipo se convertirá en una célula de desarrollo de una consultora tecnológica. El cliente ha encargado la creación de **DevDex**, un portal web corporativo interno donde se centralizarán las fichas técnicas, redes y habilidades de todo el equipo de ingenieros del proyecto.

El proyecto se construirá exclusivamente con HTML y CSS. El reto principal no es la complejidad del código web, sino el **cumplimiento riguroso del flujo de trabajo colaborativo mediante Git y GitHub**: creación de ramas por funcionalidad (*Feature Branch Workflow*), solicitudes de incorporación de código (*Pull Requests*), revisión entre pares (*Code Reviews*) y la resolución correcta de conflictos de fusión (*Merge Conflicts*).

---

## 👥 Roles y Asignación del Equipo

Los grupos estarán integrados por **3 o 4 alumnos**. Antes de tocar la terminal, debéis designar los siguientes roles dentro del grupo:

* **Líder de Integración / Mantenedor (1 alumno):**
  * Responsable de inicializar el repositorio local y el repositorio remoto oficial en GitHub.
  * Gestiona las invitaciones de los colaboradores.
  * Supervisa la rama principal (`main`) y actúa como último filtro de calidad.
  * Configura el despliegue final en producción mediante GitHub Pages.
* **Desarrolladores Web (Todos los integrantes, incluido el Líder):**
  * Todos los miembros del equipo —sin excepción— programarán sus componentes en sus propias ramas, abrirán sus Pull Requests y revisarán las entregas de sus compañeros.

---

## 📦 Estructura Base del Proyecto

El repositorio inicial del equipo deberá mantener estrictamente la siguiente organización modular de archivos:

```text
devdex-project/
├── index.html            <-- Dashboard principal (directorio con tarjetas de perfiles)
├── css/
│   ├── main.css          <-- Estilos globales y grid corporativo
│   └── components.css    <-- Estilos compartidos (botones, badges, tarjetas)
├── profiles/             <-- Fichas de cada desarrollador
│   ├── template.html     <-- Plantilla base a duplicar
│   └── [tu-nombre].html  <-- Tu perfil individual (creado en la Fase 2)
└── styles/               <-- Hojas de estilo individuales
    └── [tu-nombre].css   <-- Tus estilos personalizados (creados en la Fase 4)
