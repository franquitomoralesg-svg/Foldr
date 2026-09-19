# Foldr
It´s an app that replicates the folders of xiaomi hyperos but in Windows
Foldr
Launcher de escritorio para Windows: carpetas flotantes estilo HyperOS / iOS, iconos reales, arrastrar apps, y el `.exe` queda en segundo plano (bandeja del sistema).
⬇️ Descargar
👉 Foldr Setup 1.0.0.exe
Ejecuta el instalador y sigue los pasos. No se necesita nada más.
---
Cómo usarlo
Abre Foldr. Sale el panel del launcher.
Cierra el panel o pulsa Dejar en segundo plano: el programa sigue vivo en la bandeja (junto al reloj).
Clic derecho en el icono de la bandeja: abrir panel, nueva carpeta o salir.
Si vuelves a abrir el `.exe` y ya está corriendo, se abre el panel otra vez (no se duplica el proceso).
Agregar más carpetas
En el panel: Nueva carpeta. Cada carpeta es un widget en el escritorio (180 px de lado por defecto). No quedan siempre encima: otras ventanas las tapan. La posición se guarda.
Personalizar cada carpeta
En el panel están todas las carpetas; haz clic en una para desplegarla y ver sus ajustes y sus apps.
Nombre y emoji (el emoji sale junto al nombrecito de abajo).
Color del cristal (paleta de 9 tonos).
Tamaño del widget, de 120 a 280 px.
Opacidad del cristal, de 0 a 100 %.
Iconos: chicos, normales o grandes.
Nombres debajo de cada icono (sí/no) y recuadro detrás del icono (sí/no).
También puedes hacer clic derecho sobre la carpeta en el escritorio: ahí tienes tamaño, iconos, nombres, recuadro, opacidad y un atajo para abrir el panel.
Arrastrar apps al widget
Desde el Escritorio, el Explorador o el menú Inicio:
Arrastra un `.exe`, un acceso directo (`.lnk`) o un `.url`.
Suéltalo encima de la carpeta (cerrada o abierta).
Aparece el icono real de Windows.
También puedes usar Agregar apps en el panel (selector de archivos) o arrastrar al listado de cada carpeta. Desde el launcher puedes Quitar apps una a una.
Clic derecho en un icono dentro de la carpeta abierta abre un panel de opciones (Abrir, Renombrar, Ubicación, Propiedades, Quitar).
Para cambiar el orden, arrastra un icono dentro de la carpeta abierta: se va colocando en el hueco donde lo sueltes y el orden queda guardado.
Los iconos reales se extraen del `.exe` / acceso directo. En la carpeta cerrada se ven los primeros en grande y el resto en la mini-grilla; al abrirla aparecen todos con scroll.
Comportamiento
Arrastra la carpeta por el escritorio para colocarla.
Debajo de la carpeta se ve su nombre en pequeño (12 px, como las etiquetas de Windows), con el emoji delante si lo tiene.
Solo se pincha lo que se ve: la carpeta y su nombre. El hueco alrededor deja pasar los clics al escritorio.
Clic para abrirla (cristal + scroll nativo). Se abre en un panel más grande, centrado.
Clic fuera o Escape para cerrarla.
Al abrir una app, la carpeta se pliega sola y se queda por debajo: la ventana que acaba de abrirse nunca aparece detrás del widget.
Marca Abrir al iniciar Windows si quieres que el launcher arranque solo.
Solo puede haber una instancia del programa: si lo abres otra vez, no se duplican las carpetas, se abre el panel del que ya está corriendo.
Los datos se guardan en `%APPDATA%\carpetas-hyperos\folders.json`.
---
Desarrollo
```powershell
npm install
npm start
```
Compilar el `.exe`
```powershell
npm install
npm run build
```
Genera el instalador NSIS en `dist\`. Con `npm run build:portable` se genera además un `.exe` portable de un solo archivo.
---
Licencia
MIT — Blazepro7989
