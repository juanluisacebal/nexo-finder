# Soporte de Nexo

Nexo conecta tu Mac con servidores remotos y los muestra en Finder.

## Contacto

Escríbenos a **soporte@juanluisacebal.com**. Indica tu versión de macOS, la versión de Nexo (menú Nexo → Acerca de Nexo), el tipo de conexión (SFTP, WebDAV, S3…) y el mensaje de error, si lo hay. **No envíes nunca contraseñas ni claves.**

## Primeros pasos

1. Abre Nexo y pulsa **+** para crear una conexión.
2. Elige el tipo, escribe el servidor, el usuario y la contraseña (o importa tu clave SSH).
3. Pulsa **Probar conexión**.
4. Pulsa **Añadir a Finder**. La conexión aparecerá en la barra lateral de Finder, en **Ubicaciones**.

## Preguntas frecuentes

**La conexión no aparece en Finder.**
Abre **Ajustes del Sistema → General → Inicio y extensiones** y comprueba que la extensión de proveedor de archivos de Nexo está activada.

**macOS pide permiso para acceder a la red local.**
Acéptalo si tu servidor está en tu red (un NAS u otro ordenador). Puedes cambiarlo en **Ajustes del Sistema → Privacidad y seguridad → Red local**.

**«La huella del servidor ha cambiado».**
Nexo recuerda la identidad de cada servidor SSH. Si cambia, puede deberse a una reinstalación del servidor o a un ataque. Si estás seguro de que el cambio es legítimo, borra la conexión y créala de nuevo.

**No veo los cambios hechos en el servidor desde otro sitio.**
Nexo comprueba los cambios cada 2 minutos. Para verlos al momento, pulsa **Actualizar** en la app.

**¿Cómo se monta una carpeta SMB, AFP o NFS?**
Nexo se la pasa a macOS, que la monta con su soporte nativo y te pide la contraseña.

**¿Cómo abro el escritorio remoto?**
VNC se abre con **Compartir pantalla** de macOS. RDP necesita un cliente, por ejemplo *Windows App* de Microsoft. Si un servidor de archivos tiene escritorio remoto configurado, verás **Abrir escritorio remoto** en el menú contextual de Finder.

**¿Dónde están mis contraseñas?**
En el Llavero de macOS. Nexo no las envía a ningún sitio. Consulta la [política de privacidad](privacidad.md).

## Limitaciones conocidas

- FTP con TLS (FTPS) no está soportado todavía. Usa SFTP si tu servidor lo permite.
- Amazon S3 y Cloudflare R2: máximo 5 GB por archivo.

---

# Nexo Support

Contact: **soporte@juanluisacebal.com**. Please include your macOS version, the Nexo version, the connection type and any error message. **Never send passwords or keys.**

- **The connection doesn't show up in Finder:** enable Nexo's File Provider extension in System Settings → General → Login Items & Extensions.
- **Changes made elsewhere don't appear:** Nexo checks for changes every 2 minutes; press Refresh in the app to check now.
- **SMB/AFP/NFS** shares are mounted natively by macOS. **VNC** opens in Screen Sharing; **RDP** needs an RDP client such as Microsoft's Windows App.
- **Known limitations:** no FTPS yet; S3/R2 uploads are limited to 5 GB per file.
