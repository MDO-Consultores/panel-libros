# Panel de Libros Societarios — MDO Consultores

**Este repositorio contiene solo la vista del panel: ningún dato de clientes.**

Los datos viven en el repositorio privado `mdo-libros-societarios` y cada usuario
los lee con su propia sesión de GitHub al abrir el panel. Quien no tiene acceso de
lectura a ese repositorio no ve nada.

- La página se publica con GitHub Pages (workflow `pages.yml`).
- `index.html` se genera en el repositorio privado (`herramientas/generar_panel.py`,
  salida `app/publico/index.html`) y se copia acá cuando cambia la vista.
- No editar a mano.
