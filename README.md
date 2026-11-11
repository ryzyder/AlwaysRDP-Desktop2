# AlwaysRDP Desktop 2

Complemento para la edición de AlwaysRDP de Microsoft Store. Coloca cada ventana RDP nueva de AlwaysRDP en el Escritorio 2, incluidas las que se abren al reconectar. Crea el segundo escritorio si hace falta.

1. Extrae el ZIP completo en una carpeta.
2. Abre `AlwaysRDP.Desktop2.exe` y luego conecta desde AlwaysRDP.
3. En el área de notificación de Windows, el menú del complemento permite mover la sesión actual, ir a Escritorio 2, pausar el movimiento automático o salir.

Requiere Windows 11 x64 24H2 (compilación 26100.2605 o posterior) o 25H2. La compatibilidad con escritorios virtuales depende de la versión de Windows y de VirtualDesktopAccessor. Se verificó el movimiento de una ventana de prueba en Windows 11 25H2. La integración con la app instalada desde Microsoft Store está pendiente de su publicación.

El complemento se ejecuta en la sesión de Windows del usuario. Identifica la sesión RDP a partir del proceso que la abrió y solo actúa sobre las ventanas del cliente de Windows iniciadas por el paquete de AlwaysRDP. El menú permanece disponible mientras el complemento está abierto.

Copyright © 2026 ryzyder. El archivo `LICENSE-VirtualDesktopAccessor.txt` contiene el aviso MIT de [VirtualDesktopAccessor](https://github.com/Ciantic/VirtualDesktopAccessor).

[Versiones y descargas](https://github.com/ryzyder/AlwaysRDP-Desktop2/releases)
