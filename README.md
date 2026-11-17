# Blackjack Americano — Mesa Royale

Aplicación web de **Blackjack Americano** lista para alojar gratis en **GitHub Pages**, con mesa circular y turnos en sentido horario, temporizador por turno con plantado automático, pausa de resumen de ganancias tras cada ronda, animaciones, efectos de sonido sintetizados, dividir pareja (**Split**), **Doblar tras dividir (DAS)** y **salas multijugador P2P de 9 huecos**.

## Novedades incluidas

- **Mesa circular en sentido horario**: Las cartas del crupier se sitúan en el centro de la mesa y los puestos de los jugadores (3 en solitario o 9 en sala online) se distribuyen alrededor avanzando en **sentido horario**.
- **Temporizador por turno (`10s / 15s / 20s / 30s`)**: Cuenta atrás visual en cada turno; si el tiempo se agota, la mano se planta automáticamente.
- **Pausa de resumen post-ronda (~5 segundos)**: Al terminar cada ronda se muestra un panel con el balance neto ganado/perdido, total apostado, cobrado y el desglose por mano (con opción de saltar a la siguiente ronda al instante).
- **Animaciones y sonidos**: Reparto secuencial de cartas, volteo 3D de la carta oculta del crupier, fichas animadas y efectos de sonido mediante Web Audio API (con botón para activar/silenciar).

## Cómo subirlo a GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo, `blackjack`).
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. Ve a **Settings → Pages**, selecciona **Deploy from a branch**, elige `main` y `/ (root)` y pulsa **Save**.
