# Política de privacidad de Nexo Finder

*Última actualización: 20 de noviembre de 2026*

Nexo Finder es una app para macOS que conecta tu Mac con servidores que tú configuras (SFTP, FTP, WebDAV, Amazon S3 o compatibles, Cloudflare R2, SMB, AFP, NFS, VNC y RDP) y los muestra en Finder.

## Resumen

**Nexo Finder no recoge, no envía y no vende ningún dato tuyo.** No tiene cuentas de usuario, ni analítica, ni publicidad, ni rastreo, ni servidores propios. Todo lo que configuras se queda en tu Mac.

## Qué guarda Nexo Finder y dónde

Todo se guarda **solo en tu Mac**, dentro del contenedor protegido de la app:

| Dato | Dónde | Para qué |
|---|---|---|
| Lista de conexiones (nombre, tipo, servidor, puerto, usuario, ruta) | Contenedor de la app | Recordar tus conexiones |
| Contraseñas, claves privadas SSH y claves secretas de S3/R2 | **Llavero de macOS**, cifrado por el sistema | Conectarte sin pedirte la contraseña cada vez |
| Huellas de los servidores SSH | Contenedor de la app | Avisarte si un servidor cambia de identidad |
| Copias locales de los archivos que abres | Carpeta que gestiona macOS para Finder | Que puedas abrirlos y editarlos |

Puedes borrar una conexión desde la app en cualquier momento, y con ella se borran sus secretos del Llavero. Si desinstalas Nexo Finder, macOS elimina su contenedor.

## Con quién se conecta Nexo Finder

Nexo Finder **solo** se conecta a los servidores que tú añades, y solo para listar, descargar, subir, mover o borrar archivos cuando tú (o Finder en tu nombre) lo pides. Esos servidores son tuyos o de los proveedores que tú eliges, y se rigen por sus propias políticas de privacidad.

Nexo Finder no se conecta a ningún servidor del desarrollador ni de terceros. La compra «Nexo Finder completo» la gestiona la App Store de Apple: Nexo Finder solo pregunta a macOS si este Apple ID la tiene, y el desarrollador no recibe tus datos de pago ni tu identidad (solo las cifras agregadas de ventas que Apple da a todos los desarrolladores). Para el escritorio remoto, Nexo Finder abre las apps de macOS (Compartir pantalla) o el cliente RDP que tengas instalado, que se rigen por sus propias políticas.

## Red local

macOS puede pedirte permiso para que Nexo Finder acceda a la red local. Solo se usa para conectar con los servidores de tu red (NAS, otros ordenadores) que tú configuras.

## Menores

Nexo Finder no está dirigida a menores y no recoge datos de nadie.

## Cambios

Si esta política cambia, se publicará aquí con una nueva fecha de actualización.

## Contacto

Para cualquier duda sobre privacidad: soporte@juanluisacebal.com.

---

# Nexo Finder Privacy Policy

*Last updated: November 20, 2026*

**Nexo Finder does not collect, transmit or sell any of your data.** It has no user accounts, analytics, advertising, tracking or servers of its own.

- **Stored only on your Mac:** your list of connections (inside the app's protected container), your passwords, SSH keys and S3/R2 secret keys (in the macOS Keychain), SSH server fingerprints, and local copies of the files you open (managed by macOS for Finder).
- **Network:** Nexo Finder connects only to the servers you add, and only to carry out the file operations you request. It never contacts any server run by the developer or by third parties. Remote desktop sessions are opened with macOS Screen Sharing or with the RDP client you have installed.
- **Deletion:** deleting a connection also removes its secrets from the Keychain. Uninstalling Nexo Finder removes its container.
- **Children:** Nexo Finder is not directed at children and collects no data from anyone.
- **Contact:** soporte@juanluisacebal.com.
