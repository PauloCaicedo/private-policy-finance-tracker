# Política de Privacidad — Gastos y Ahorro - Luxor

**Última actualización**: 16 de julio de 2026

**Desarrollador**: Luxor Services
**Contacto**: cuentas_desarrollo_939@proton.me
**Sitio web**: https://luxor-services.com

Esta política aplica a la aplicación **"Gastos y Ahorro - Luxor"** (también conocida
como Finance Tracker, paquete `com.luxorservices.financetracker`) en **Android
(Google Play)** y en **iOS (App Store)**.

## 1. Introducción

Luxor Services ("nosotros", "nuestro" o "nos") opera la aplicación móvil Gastos y
Ahorro - Luxor (en adelante, "la Aplicación").

Esta página le informa sobre nuestras políticas con respecto a la recopilación, uso y
divulgación de datos cuando utiliza nuestra Aplicación.

**Compromiso de Privacidad**: la Aplicación está diseñada con la privacidad como
prioridad. **Todos sus datos financieros se almacenan ÚNICAMENTE en su dispositivo.**
No recopilamos, transmitimos ni almacenamos ningún dato financiero en nuestros
servidores. Lo único que puede viajar a nuestro servidor es un contexto **anónimo y
opcional** que se describe en la sección 3.

## 2. Información que NUNCA sale de su dispositivo

La Aplicación NO recopila, NO almacena en servidores y NO transmite:

- ❌ Datos financieros (transacciones, montos, ingresos, gastos, presupuestos, metas, deudas)
- ❌ Información bancaria ni credenciales de bancos
- ❌ Números de tarjetas
- ❌ Información de identificación personal (nombre, correo, teléfono)
- ❌ Ubicación geográfica (no usamos GPS)
- ❌ Contactos
- ❌ Fotos o archivos multimedia
- ❌ Audio del micrófono (ver sección 6)
- ❌ Contenido de notificaciones (ver sección 7)
- ❌ Identificadores de publicidad (no usamos IDFA en iOS ni AAID en Android, y no hay rastreo entre apps)

## 3. Estadísticas anónimas (opcional, con interruptor)

Para saber cuántas personas usan la Aplicación y en qué versiones/idiomas mejorar,
la Aplicación puede enviar a nuestro propio servidor, **como máximo una vez al día**,
un contexto **anónimo**:

- Un **identificador de instalación aleatorio** generado por la propia Aplicación
  (no proviene de su identidad, de su cuenta de Google/Apple ni de identificadores
  de publicidad; no permite saber quién es usted).
- Plataforma (Android o iOS) y versión de la Aplicación.
- Idioma de la Aplicación.
- El **país que usted eligió** en Ajustes (nunca su ubicación real; si no elige
  país, no viaja ninguno).
- Si la instalación tiene la versión Premium.

Puntos importantes:

- ✅ **Es opcional**: la primera vez se le explica dentro de la Aplicación y puede
  apagarlo en cualquier momento en **Ajustes → "Compartir estadísticas anónimas"**.
  Apagarlo no cambia ninguna función.
- ✅ **No incluye ningún dato financiero ni personal.**
- ✅ Viaja **cifrado** (HTTPS) hacia nuestro propio servidor; no se comparte con
  terceros ni se vende.
- ✅ **Eliminación**: el identificador no está vinculado a su identidad. Si borra
  los datos de la Aplicación (o la reinstala), se genera un identificador nuevo y
  el anterior queda huérfano.

## 4. Funciones que usan nuestro servidor

Nuestro servidor (`api.luxor-services.com`, operado por Luxor Services) atiende
además estas funciones. La Aplicación funciona completa aunque el servidor no esté
disponible.

### 4.1 Avisos dentro de la app
La Aplicación consulta al abrir si hay avisos del desarrollador (novedades,
mantenimiento o avisos importantes de seguridad). Esta consulta entrega contenido a
la Aplicación; no publica datos suyos.

### 4.2 Soporte dentro de la app (tickets)
Si usted decide contactar soporte desde la Aplicación, se envía **únicamente lo que
usted escribe** (asunto y mensaje) junto con contexto técnico para poder ayudarle:
plataforma, versión de la Aplicación, idioma y el identificador anónimo de
instalación (para mostrarle las respuestas en su dispositivo). No se requiere correo
ni ningún dato personal. Los mensajes de soporte se conservan mientras el hilo esté
activo y puede dejar de usar esta función cuando quiera.

### 4.3 Encuestas
Ocasionalmente la Aplicación puede mostrar una encuesta breve y opcional. Solo se
envía lo que usted responda, de forma anónima.

Nuestra infraestructura usa **Cloudflare** como red intermediaria de tránsito
(protección y cifrado del tráfico). Cloudflare procesa el tráfico como proveedor de
infraestructura: https://www.cloudflare.com/privacypolicy/

## 5. Almacenamiento local

Todos los datos que usted ingresa se almacenan ÚNICAMENTE en su dispositivo:

- **Base de datos local** (Hive) para sus movimientos, cuentas, metas, etc.
- **Preferencias** del dispositivo para configuraciones de la Aplicación.
- **Archivos de backup**: se guardan en su dispositivo (en Android, típicamente en
  Descargas; en iOS, en el almacenamiento de la Aplicación o donde usted elija al
  compartir).

**Importante**: si desinstala la Aplicación, sus datos locales se eliminan del
dispositivo. Le recomendamos exportar un backup antes de cambiar de teléfono.

## 6. Micrófono y dictado por voz (opcional)

La Aplicación permite **dictar** un movimiento por voz. Si usted usa esta función:

- El reconocimiento de voz lo realiza el **servicio del sistema** de su teléfono
  (Google en Android, Apple en iOS), conforme a sus políticas. Según el dispositivo,
  ese procesamiento puede ocurrir en el propio teléfono o en los servidores de
  Google/Apple.
- Nosotros **no grabamos ni almacenamos audio**; la Aplicación solo recibe el texto
  reconocido, que queda guardado localmente como cualquier otro movimiento.
- El acceso al micrófono (y en iOS al reconocimiento de voz) se solicita con permiso
  explícito y solo se usa mientras usted dicta.

## 7. Captura de notificaciones bancarias (solo Android, beta, opt-in)

En Android existe una función **experimental y desactivada por defecto** que, SOLO si
usted la activa en Ajustes, lee las notificaciones de las apps de bancos que usted
autorice para sugerirle movimientos ya escritos.

- Requiere que usted conceda explícitamente el **acceso a notificaciones** del
  sistema y puede revocarlo cuando quiera.
- Todo el procesamiento ocurre **en su dispositivo**. El contenido de las
  notificaciones **jamás se transmite** a nuestros servidores ni a terceros.
- Esta función no existe en iOS (el sistema no lo permite).

## 8. Compras dentro de la app (Premium)

La versión Premium es un **pago único** (no vendemos suscripciones).

- **Android**: la compra la procesa **Google Play Billing**.
  Política: https://policies.google.com/privacy
- **iOS**: la compra la procesa el sistema de compras de **Apple (App Store)**.
  Política: https://www.apple.com/legal/privacy/
- Nosotros **no vemos ni almacenamos** su información de pago. La Aplicación solo
  recibe de la tienda la confirmación de la compra para desbloquear Premium.

## 9. Permisos de la Aplicación

- **Notificaciones**: recordatorios locales (vencimientos, recurrentes). Opcional.
- **Micrófono** (y **Reconocimiento de voz** en iOS): solo para el dictado por voz,
  cuando usted lo usa (sección 6).
- **Face ID / huella digital**: para desbloquear la Aplicación si usted activa el
  bloqueo. La verificación biométrica la hace el sistema; nosotros nunca vemos ni
  almacenamos sus datos biométricos.
- **Almacenamiento / documentos**: para guardar y leer sus backups y exportaciones.
- **Acceso a notificaciones** (solo Android, opcional): únicamente si activa la
  función de la sección 7.

Todos los permisos se usan en su dispositivo. Puede revocarlos en los ajustes del
sistema (Android o iOS) cuando quiera.

## 10. Seguridad

- ✅ Datos financieros solo en su dispositivo, con almacenamiento local cifrado.
- ✅ Bloqueo opcional con PIN y biometría (Face ID / huella).
- ✅ Comunicación con nuestro servidor exclusivamente por **HTTPS**.
- ✅ Sin cuentas: no hay registro ni inicio de sesión, y por tanto no existen
  contraseñas suyas que proteger o filtrar.

## 11. Datos de menores de edad

La Aplicación no está dirigida a menores de 13 años y no recopilamos
intencionalmente información personal de menores. Si cree que un menor nos ha
proporcionado información, contáctenos para eliminarla.

## 12. Sus derechos

- ✅ **Acceder a sus datos**: están en su dispositivo, visibles en la Aplicación.
- ✅ **Exportarlos**: a CSV o backup completo, cuando quiera.
- ✅ **Eliminarlos**: desde la propia Aplicación o desinstalándola.
- ✅ **Apagar las estadísticas anónimas**: Ajustes → "Compartir estadísticas
  anónimas".
- ✅ **Revocar permisos**: desde los ajustes de Android o iOS.

Para cualquier solicitud adicional de privacidad, escríbanos al correo de contacto.

## 13. Cambios a esta política

Podemos actualizar esta Política de Privacidad ocasionalmente. Publicaremos la nueva
versión en esta página actualizando la fecha de "Última actualización". Le
recomendamos revisarla periódicamente.

## 14. Contacto

- **Email**: cuentas_desarrollo_939@proton.me
- **Sitio web**: https://luxor-services.com
- **Desarrollador**: Luxor Services

## 15. Resumen ejecutivo

**En pocas palabras:**

✅ Sus datos financieros NUNCA salen de su teléfono
✅ No hay cuentas, ni rastreo, ni publicidad, ni venta de datos
✅ Lo único que puede viajar es una estadística anónima opcional (con interruptor)
✅ Los avisos, encuestas y el soporte usan nuestro propio servidor, cifrado y sin datos personales
✅ Las compras las procesan Google Play / App Store; no vemos su información de pago
✅ Usted tiene control total: exportar, borrar y apagar todo cuando quiera

**Su privacidad es nuestra prioridad.**

---

**Versión**: 2.0
**Fecha de vigencia**: 16 de julio de 2026
**Idioma**: Español
**Plataformas**: Android (Google Play) e iOS (App Store)

---

## Consentimiento

Al usar la Aplicación, usted acepta esta Política de Privacidad. Si no está de
acuerdo, por favor no use la Aplicación.
