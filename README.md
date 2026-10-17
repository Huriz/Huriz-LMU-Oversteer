# LMU - Rear Slip Pro

Plugin de SimHub para **Le Mans Ultimate** que genera vibración en los bass shakers cuando
las ruedas traseras pierden agarre (derrape de la zaga). Funciona junto a **ShakeIt Bass Shakers**.

> **Versión de prueba.** Esta versión (0.1.0) funciona hasta el **16/11/2026**. Después el efecto
> se desactiva. Los comentarios y fallos son bienvenidos en la pestaña *Issues*.

## Qué hace

- Detecta el deslizamiento de las dos ruedas traseras, con anticipación y filtro de wheelspin.
- Limita la vibración según el gas y la refuerza con el bote de la suspensión.
- Pestaña de ajustes con modo **Simple** (Slip Start y Slip Max) y modo **Pro**
  (anticipación, influencia de la suspensión y suavizado).
- **Setups con nombre** para guardar un ajuste por coche y cargarlo con un clic.
- Crea solo el efecto **LMU - Rear Slip Pro** en ShakeIt (50 Hz base, 60 Hz alta, prioridad alta).

## Requisitos

- Windows 10 u 11.
- SimHub con ShakeIt Bass Shakers configurado (tarjeta de sonido y shakers).
- Le Mans Ultimate.

## Instalación

1. Descarga `RearSlipPro-Setup.exe` desde [Releases](../../releases/latest).
2. **Cierra SimHub** y ejecuta el instalador (pide permisos de administrador).
3. Deja marcada la casilla de crear el efecto en ShakeIt y elige la carpeta de SimHub
   (la que contiene `SimHubWPF.exe`).
4. Abre SimHub y activa el plugin **LMU - Rear Slip Pro** cuando lo pida.
5. En ShakeIt aparecerá el efecto **LMU - Rear Slip Pro**. Comprueba que los canales traseros
   (Rear Left y Rear Right) están asignados a tus shakers.

Si nunca has abierto ShakeIt, ábrelo una vez y vuelve a ejecutar el instalador para que cree el efecto.

Windows puede mostrar el aviso "Windows protegió su PC", porque el instalador no está firmado.
Pulsa *Más información* y luego *Ejecutar de todas formas*.

## Desinstalar

Desde *Configuración > Aplicaciones* de Windows. El efecto de ShakeIt no se borra solo:
elimínalo desde ShakeIt si no lo quieres.

## Licencia

Copyright (c) 2026 Huriz. Todos los derechos reservados. Puedes usar la versión de prueba para
uso personal. No se permite redistribuirla ni modificarla.
