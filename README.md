# Nexo · tu agenda conectada

App para iPhone que junta en una sola agenda tus entregas, exámenes y tareas
(Aules, Gmail, Outlook, Google Tasks, Calendar y Drive), con avisos en el móvil.

## Qué funciona ya
- Agenda de **Inicio** (lo más urgente, hoy y próximos días) y vista **Semana**.
- Botón **+** para apuntar tus propias entregas, exámenes, tareas y eventos (se guardan en el móvil).
- Marcar cosas como hechas, borrar las tuyas y apagar los datos de ejemplo (Cuentas › Datos).
- **Avisos**: con la app instalada, Cuentas › Activar avisos. Te avisa de lo que vence pronto al abrir Nexo.
- Funciona sin conexión.

Las pestañas Correo, Aules y Drive muestran **datos de ejemplo**: todavía no están conectadas a tus cuentas.

## Cómo instalarla en el iPhone
La app tiene que estar publicada en una web (https). Dos opciones gratis:

**Opción A · GitHub Pages** (este mismo repositorio)
1. GitHub Pages gratis solo funciona con repositorios públicos: Settings › General › Danger Zone › Change visibility › Public.
2. Settings › Pages › Source: *Deploy from a branch* › Branch: `main` / `(root)` › Save.
3. Al cabo de 1-2 minutos tendrás la dirección `https://guillemmut.github.io/nexo-agenda/`.

**Opción B · Netlify Drop** (el repositorio puede seguir privado)
1. Code › Download ZIP y descomprímelo en un ordenador.
2. Arrastra la carpeta a https://app.netlify.com/drop y copia la dirección que te da.

Después, en el iPhone:
1. Abre la dirección en **Safari**.
2. Compartir › **Añadir a pantalla de inicio**.
3. Abre Nexo desde el icono › Cuentas › **Activar avisos**.

## Archivos
- `index.html` · la app entera
- `manifest.webmanifest` · nombre, colores e icono de la app
- `sw.js` · modo sin conexión y avisos
- `icons/` · iconos de la pantalla de inicio
