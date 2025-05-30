# Diferencias entre Subversion y Git

- **Estructura**:
  - **Subversion**: Es un sistema centralizado. Todo el historial está en un servidor central, y los usuarios trabajan con copias de ese servidor.
  - **Git**: Es distribuido. Cada usuario tiene una copia completa del repositorio con todo el historial en su máquina.

- **Gestión de cambios**:
  - **Subversion**: Los cambios se suben directamente al servidor central con cada commit, lo que requiere conexión constante.
  - **Git**: Los commits se hacen localmente, y luego se suben al servidor remoto con un push, permitiendo trabajar sin conexión.

- **Rendimiento**:
  - **Subversion**: Puede ser más lento con proyectos grandes porque depende del servidor para muchas operaciones.
  - **Git**: Es más rápido porque la mayoría de las operaciones (como commits o diffs) se hacen localmente.

- **Ramificación**:
  - **Subversion**: Crear ramas es más lento y pesado, ya que copia directorios en el servidor.
  - **Git**: Las ramas son ligeras y rápidas, ya que solo manejan referencias locales, ideales para flujos de trabajo colaborativos.