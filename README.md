# LMU - Rear Slip Pro

[English](#english) | [Español](#español)

---

## English

A **SimHub plugin for Le Mans Ultimate** that drives your bass shakers when the rear wheels lose
grip (rear-end slides). It works together with **ShakeIt Bass Shakers**.

> **Trial version.** This build (0.1.0) works until **16/11/2026** (16 November 2026). After that
> the effect switches off. Feedback and bug reports are welcome in the *Issues* tab.

### What it does

- Detects slip on both rear wheels, with anticipation and a wheelspin filter.
- Limits the effect by throttle and boosts it with suspension bounce.
- Settings tab with a **Simple** mode (Slip Start and Slip Max) and a **Pro** mode
  (anticipation, suspension influence and smoothing).
- **Named setups**: save one set of settings per car and load it with one click.
- Creates the **LMU - Rear Slip Pro** effect in ShakeIt for you (50 Hz base, 60 Hz high, high priority).

### Requirements

- Windows 10 or 11.
- SimHub with ShakeIt Bass Shakers already set up (sound card and shakers).
- Le Mans Ultimate.

### Installation

1. Download `RearSlipPro-Setup.exe` from the [latest release](../../releases/latest).
2. **Close SimHub** and run the installer (it asks for administrator rights).
3. Leave the ShakeIt effect option ticked and choose your SimHub folder
   (the one that contains `SimHubWPF.exe`).
4. Open SimHub and enable the **LMU - Rear Slip Pro** plugin when it asks.
5. In ShakeIt you will find the **LMU - Rear Slip Pro** effect. Check that the rear channels
   (Rear Left and Rear Right) are assigned to your shakers.

If you have never opened ShakeIt, open it once and run the installer again so it can create the effect.

Windows may show "Windows protected your PC" because the installer is not code-signed.
Click *More info* and then *Run anyway*.

### Settings guide

Open it from the **Guide** button in the plugin tab.

- **Live view** – a top-down car that swings toward the side the rear is sliding, with the output of each
  rear wheel in %. Use it to see what your settings do while you drive.
- **Slip Start (°)** – how much the rear tyres must slide sideways before the effect starts.
  Lower = it reacts earlier.
- **Slip Max (°)** – the slip at which the effect reaches 100%. Higher = a longer, more gradual build-up.
- **Progression curve** *(Pro)* – the shape between Slip Start and Slip Max. 1 = straight line.
  Below 1 the effect rises fast at first and flattens; above 1 it rises gently first and strongly at the end.
- **Anticipation** *(Pro)* – a small amount of vibration (as % of the maximum) when slip grows quickly,
  just before the effect officially starts. A "heads-up" that the rear is about to go.
- **Suspension influence** *(Pro)* – extra boost from suspension bounce, up to the percentage you set.
  0 = no boost.
- **Throttle limit** *(Pro)* – above this throttle the effect switches off (with a short fade).
  100% = never. Handy if you don't want it during power oversteer.
- **Smoothing** *(Pro)* – how fast the vibration rises and falls. **Fast** is instant and sharper,
  **Normal** is balanced, **Soft** is slower and rounder.
- **Setups** – save one set of settings per car. Type a name and press **Save**: if the name doesn't exist
  it is created, if it exists it is overwritten. Click a setup to load it (it turns blue; the last one used
  goes to the top). **Rename** edits the name in place and **Delete** asks you to press twice.
  **Default** holds the recommended values and can't be edited.
- **ES / EN** – language of the tab. It follows Windows by default.
- **ShakeIt frequencies** – the effect created for you uses 50 Hz base and 60 Hz high. The tone moves toward the
  high frequency as the effect gets stronger. If you want the build-up to be more audible, try a higher
  "High effect frequency" in ShakeIt (for example 70 Hz). Below 50 Hz the slide is hard to read on most body shakers.
### Uninstall

Use *Settings > Apps* in Windows. The ShakeIt effect is not removed automatically:
delete it from ShakeIt if you no longer want it.

### License

Copyright (c) 2026 Huriz. All rights reserved. You may use the trial version for personal use.
Redistribution and modification are not allowed.

---

## Español

Plugin de SimHub para **Le Mans Ultimate** que genera vibración en los bass shakers cuando
las ruedas traseras pierden agarre (derrape de la zaga). Funciona junto a **ShakeIt Bass Shakers**.

> **Versión de prueba.** Esta versión (0.1.0) funciona hasta el **16/11/2026**. Después el efecto
> se desactiva. Los comentarios y fallos son bienvenidos en la pestaña *Issues*.

### Qué hace

- Detecta el deslizamiento de las dos ruedas traseras, con anticipación y filtro de wheelspin.
- Limita la vibración según el gas y la refuerza con el bote de la suspensión.
- Pestaña de ajustes con modo **Simple** (Slip Start y Slip Max) y modo **Pro**
  (anticipación, influencia de la suspensión y suavizado).
- **Setups con nombre** para guardar un ajuste por coche y cargarlo con un clic.
- Crea solo el efecto **LMU - Rear Slip Pro** en ShakeIt (50 Hz base, 60 Hz alta, prioridad alta).

### Requisitos

- Windows 10 u 11.
- SimHub con ShakeIt Bass Shakers configurado (tarjeta de sonido y shakers).
- Le Mans Ultimate.

### Instalación

1. Descarga `RearSlipPro-Setup.exe` desde la [última release](../../releases/latest).
2. **Cierra SimHub** y ejecuta el instalador (pide permisos de administrador).
3. Deja marcada la casilla de crear el efecto en ShakeIt y elige la carpeta de SimHub
   (la que contiene `SimHubWPF.exe`).
4. Abre SimHub y activa el plugin **LMU - Rear Slip Pro** cuando lo pida.
5. En ShakeIt aparecerá el efecto **LMU - Rear Slip Pro**. Comprueba que los canales traseros
   (Rear Left y Rear Right) están asignados a tus shakers.

Si nunca has abierto ShakeIt, ábrelo una vez y vuelve a ejecutar el instalador para que cree el efecto.

Windows puede mostrar el aviso "Windows protegió su PC", porque el instalador no está firmado.
Pulsa *Más información* y luego *Ejecutar de todas formas*.

### Guía de ajustes

Ábrela desde el botón **Guía** de la pestaña del plugin.

- **Vista en vivo** – un coche visto desde arriba que se mueve hacia el lado al que se te va la zaga, con la
  intensidad de cada rueda trasera en %. Sirve para ver qué hacen tus ajustes mientras conduces.
- **Slip Start (°)** – cuánto tienen que deslizar de lado las ruedas traseras para que empiece el efecto.
  Más bajo = reacciona antes.
- **Slip Max (°)** – el slip con el que el efecto llega al 100%. Más alto = una subida más larga y gradual.
- **Curva de progresión** *(Pro)* – la forma entre Slip Start y Slip Max. 1 = línea recta.
  Menos de 1: sube rápido al principio y se aplana. Más de 1: sube suave al principio y fuerte al final.
- **Anticipación** *(Pro)* – una pequeña vibración (en % del máximo) cuando el slip crece rápido, justo antes de
  que empiece el efecto. Es un aviso de que la zaga está a punto de irse.
- **Influencia de suspensión** *(Pro)* – refuerzo extra por el bote de la suspensión, hasta el porcentaje que
  pongas. 0 = sin refuerzo.
- **Límite de gas** *(Pro)* – con más gas que este valor el efecto se apaga (con una transición corta).
  100% = nunca. Útil si no lo quieres durante el sobreviraje por potencia.
- **Suavizado** *(Pro)* – con qué rapidez sube y baja la vibración. **Rápido** es instantáneo y más seco,
  **Normal** es equilibrado y **Suave** es más lento y redondo.
- **Setups** – guarda un ajuste por coche. Escribe un nombre y pulsa **Guardar**: si no existe se crea y si
  existe se sobrescribe. Haz clic en un setup para cargarlo (se pone en azul y el último usado sube arriba).
  **Renombrar** edita el nombre en la misma línea y **Borrar** pide pulsar dos veces.
  **Default** tiene los valores recomendados y no se puede editar.
- **ES / EN** – idioma de la pestaña. Por defecto sigue el de Windows.
- **Frecuencias en ShakeIt** – el efecto que se crea usa 50 Hz base y 60 Hz alta. El tono se acerca a la
  frecuencia alta cuando el efecto se hace más fuerte. Si quieres que la subida se note más, prueba una
  "High effect frequency" mayor en ShakeIt (por ejemplo 70 Hz). Por debajo de 50 Hz el derrape se nota poco
  en la mayoría de body shakers.
### Desinstalar

Desde *Configuración > Aplicaciones* de Windows. El efecto de ShakeIt no se borra solo:
elimínalo desde ShakeIt si no lo quieres.

### Licencia

Copyright (c) 2026 Huriz. Todos los derechos reservados. Puedes usar la versión de prueba para
uso personal. No se permite redistribuirla ni modificarla.
