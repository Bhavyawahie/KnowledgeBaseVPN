---
title: Errores comunes del instalador
sidebar_position: 2
---

Este artículo contiene algunos de los errores más comunes que puedes encontrar durante la instalación de AdGuard VPN para Windows y las posibles formas de solucionarlos.

### Error 5: Acceso denegado {#error-5}

Este error ocurre cuando hay algún problema con los permisos. Puede haber varias razones diferentes por las que el instalador de AdGuard VPN no tiene los permisos necesarios para finalizar correctamente el proceso de instalación. Puedes intentar los siguientes pasos:

- Desactiva temporalmente tu antivirus. Algunos de ellos pueden interferir con la instalación, dependiendo de su configuración.

- Elige otra carpeta de instalación. Es posible que la carpeta de instalación actual tenga algunas restricciones de acceso. También asegúrate de no seleccionar una unidad externa, una unidad virtual, etc.

- Reinicia tu computadora. A veces, los problemas de permisos son temporales y se pueden resolver reiniciando la PC.

### Error 112: El disco está lleno, Error 1632: Carpeta temporal llena o inaccesible {#error-112}

Estos son dos errores diferentes con soluciones muy similares. Como sugieren sus nombres, el instalador de AdGuard VPN no encontró suficiente espacio en el disco para completar la instalación. Hay varias cosas que puedes intentar para solucionar el problema:

- Desinstala algunos programas o elimina archivos innecesarios de la unidad en la que intentabas instalar AdGuard VPN.

- Descarga, instala y ejecuta [AdwCleaner](http://www.bleepingcomputer.com/download/adwcleaner/), un software gratuito de Malwarebytes. Entre otras cosas, él limpiará tu sistema de todo tipo de archivos "sobrantes" que quedan después de programas desinstalados incorrectamente. Ayudará a limpiar algo de espacio en disco.

- Reinicia tu computadora. A veces, los archivos temporales pueden ocupar una cantidad considerable de espacio en disco, y reiniciar tu PC es la forma más confiable de deshacerse de ellos.

### Error 1601: no se puede acceder al instalador de Windows {#error-1601}

Se puede decir que este es un subtipo particular del Error 1603. Las posibles soluciones son similares:

- Inicia y vuelve a registrar el servicio Microsoft Installer. Esto puede resultar laborioso.

    1) Presiona *Win + R* e ingresa **services.msc**. 2) Búscalo en la lista y haz doble clic en *Windows Installer*. 3) Presiona el botón *Iniciar* debajo de *Estado del servicio* y presiona *Aceptar*. Si el estado del servicio es **ejecutando**, debes hacer clic en *Detener* primero y luego presionar *Iniciar*. 4) Presiona *Win + R*, ingresa ***msiexec /unregister*** y presiona *Enter*. 5) Presiona *Win + R* nuevamente, ingresa ***msiexec /regserver*** y presiona *Enter*

- Reinicia la PC y comienza la instalación nuevamente. A veces eso es suficiente para solucionar el problema.

### Error 1602: Cancelado por el usuario {#error-1602}

Si recibiste este código de error, es probable que hayas interrumpido el proceso de instalación manualmente de una forma u otra. Lo que puedes hacer es:

- No cierres la ventana del instalador. Cuando se complete la instalación, será cerrarado automáticamente.

- Si aparece una ventana de diálogo durante la instalación, presiona "Sí" para otorgar al instalador los permisos necesarios. Al hacer clic en "No", la instalación será cancelada.

- No inicies otros procesos mientras la instalación está en curso.

### Error 1603: error fatal durante la instalación {#error-1603}

El error suena más aterrador de lo que realmente es. En realidad, este es un error bastante genérico que puede tener muchas causas diferentes, y algunas de ellas se solucionan fácilmente. Prueba las siguientes soluciones:

- Presiona la tecla *Win*, busca *Comando prompt* y ejecútalo. Allí, escribe `sfc /scannow` y presiona *Enter*.

- Elige otra carpeta de instalación. Es posible que la carpeta de instalación actual tenga algunas restricciones de acceso. También asegúrate de no seleccionar una unidad externa, una unidad virtual, etc.

- Desinstala AdGuard VPN usando nuestra herramienta especial de desinstalación [](../../installation#advanced) y luego repite la instalación.

- Inicia y vuelve a registrar el servicio Microsoft Installer. Esto puede resultar laborioso.

    1) Presiona *Win + R* e ingresa ***services.msc***. 2) Búscalo en la lista y haz doble clic en *Windows Installer*. 3) Presiona el botón *Iniciar* debajo de *Estado del servicio* y presiona *Aceptar*. Si el estado del servicio es **ejecutando**, debes hacer clic en *Detener* primero y luego presionar *Iniciar*. 4) Presiona *Win + R*, ingresa ***msiexec /unregister*** y presiona *Enter*. 5) Presiona *Win + R* nuevamente, ingresa ***msiexec /regserver*** y presiona *Enter*

- Adquiere permisos completos en la unidad para la instalación. Es posible que se produzca el error 1603 porque no tienes permisos completos en la ubicación del archivo. Esto tampoco es tan fácil como algunas de las otras soluciones:

    1) Abre *Explorador de archivos*, haz clic con el botón derecho en la unidad que contiene la ubicación de instalación y selecciona *Propiedades*. 2) Ve a la pestaña *Seguridad* y haz clic en *Editar*. 3) Haz clic en *SISTEMA* y asegúrate de que la casilla *Permitir* de cada elemento en *Permisos para SISTEMA* esté marcada (si es posible). Haz la misma verificación para *Administradores*. 4) Haz clic en *Aceptar* para volver al cuadro de diálogo *Propiedades*. Luego haz clic en *Avanzado*. 5) Haz clic en *Cambiar permisos*. 6) En la pestaña *Permisos*, haz doble clic en *Administradores*. 7) Selecciona *Esta carpeta, subcarpetas y archivos* para el campo *Se aplica a* y marca todos los *Permisos básicos* disponibles. Luego, presiona *OK*. 8) Haz la misma operación del punto 7 para *SISTEMA*. 9) Haz clic en *OK* hasta el final. Intenta instalar AdGuard de nuevo.

### Error 1618: ya hay otra instalación en curso {#error-1618}

Este error ocurre cuando hay varias instancias del instalador de AdGuard VPN iniciadas al mismo tiempo. Qué hacer si recibes este error:

- Reinicia tu PC y vuelve a iniciar el instalador. Al reiniciar el ordenador, se detendrán todos los procesos en curso, incluidas todas las copias del instalador.

- No hagas varios clics en el instalador incluso si no se inicia de inmediato. A veces, la interfaz de usuario del instalador puede tardar unos segundos en mostrarse.

### Error 1638: Ya está instalada otra versión de este producto {#error-1638}

Es muy probable que ya hayas instalado AdGuard VPN.

- Verifica si AdGuard VPN ya está instalado en su ordenador. Puedes hacerlo presionando la tecla *Win* y escribiendo ***AdGuard VPN***.

- Tal vez haya algunos archivos sobrantes de una instalación anterior de AdGuard VPN. Desinstala AdGuard usando nuestra herramienta especial de desinstalación [](../../installation#advanced) y luego repite la instalación.

### Otros errores {#other}

Si has encontrado un error que no se encuentra en la lista anterior, es posible que podamos resolverlo nosotros mismos. Pero para hacerlo, necesitamos tus archivos de registro. Realiza los siguientes pasos:

- Encuentra y archiva los **Registros de instalación de AdGuard VPN** como se describe en [este artículo](https://adguard.com/kb/adguard-for-windows/solving-problems/installation-logs/).

- Busca y guarda en el disco los registros del **Event Viewer**. [Este artículo](https://adguard.com/kb/adguard-for-windows/solving-problems/system-logs/) explica cómo hacerlo.

Envía por correo electrónico todos estos archivos de los dos pasos anteriores a **support@adguard.com** y describe el problema en el cuerpo del mensaje. Nuestro equipo de soporte te responderá lo antes posible.
