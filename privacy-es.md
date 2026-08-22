# Política de privacidad — JacArrow

**Última actualización:** 2026-08-22
**Responsable del tratamiento:** Morten Jacobsen, Noruega
**Contacto:** galge.vender.0a@icloud.com

---

## Versión corta

JacArrow almacena **todos tus datos localmente en tu dispositivo**. No tenemos
servidores que reciban tus tiros, sesiones u objetivos. Cuando desinstalas
la aplicación, todos los datos desaparecen.

Los únicos terceros que reciben información son:
- **Apple** (si usas la app en iPhone) — gestiona las compras de App Store
- **Google** (si usas la app en Android) — gestiona las compras de Google Play
- **RevenueCat** (después de comprar Pro) — verifica tu compra
- **Sentry** (solo si activas los informes de fallos) — recibe datos anónimos de fallos para ayudarnos a corregir errores

Cuál de los dos —Apple o Google— está implicado depende de la tienda desde la
que descargaste la app. Ninguno de los dos participa en tus datos de tiro.

Tienes todos los derechos RGPD de acceso, supresión y portabilidad de los datos.

---

## Qué almacenamos

### En tu dispositivo (localmente, nunca sale del teléfono)
- **Datos de tiro:** sesiones, rondas, posiciones de flechas, puntuaciones, etiquetas, objetivos, arcos y juegos de flechas
- **Ajustes:** idioma seleccionado, tema, mano dominante, categoría de competición, opciones de notificación
- **Historial de la app:** estado de los coach-marks (qué consejos has visto), indicadores de tutoriales completados

Todos estos datos se almacenan en una base de datos SQLite y en AsyncStorage en
tu teléfono. Ni JacArrow ni ningún tercero tiene acceso a estos datos. No hay
cuenta de usuario, ni almacenamiento en la nube, ni sincronización entre
dispositivos: tus datos se quedan en el dispositivo donde los registraste.

### Notificaciones (programadas localmente en el dispositivo)
JacArrow puede enviarte notificaciones: que has logrado un récord personal, que
tu período de prueba está a punto de terminar, o recordatorios de tus objetivos.

Todas se **programan localmente en tu dispositivo** y se calculan a partir de
datos que nunca salen de él. No tenemos ningún servidor que envíe
notificaciones, y nunca recibimos un token de notificación, un acuse de entrega
ni ninguna información sobre qué hiciste con una notificación. La entrega en sí
la gestiona el sistema operativo del teléfono (iOS o Android), igual que una
alarma que hayas puesto tú.

Puedes desactivar las notificaciones en cualquier momento: en JacArrow desde
**Ajustes → Notificaciones**, y en los ajustes del propio teléfono.

---

## Terceros

### Apple App Store (en iPhone)
Si descargaste JacArrow desde la App Store, todas las compras dentro de la app
las gestiona Apple. Nunca recibimos información de tarjeta, direcciones u otros
detalles de pago. La
[política de privacidad de Apple](https://www.apple.com/es/legal/privacy/) se aplica al
proceso de compra.

### Google Play (en Android)
Si descargaste JacArrow desde Google Play, todas las compras dentro de la app
las gestiona Google a través de Google Play Billing. Nunca recibimos información
de tarjeta, direcciones u otros detalles de pago: solo se nos comunica que una
compra se ha completado y es válida. La
[política de privacidad de Google](https://policies.google.com/privacy?hl=es)
se aplica al proceso de compra.

Ten en cuenta que Google Play, a diferencia de la App Store, **no** comparte una
compra dentro de la app con un grupo familiar. Es una diferencia entre tiendas,
no algo que podamos controlar.

### RevenueCat (solo después de comprar Pro)
Cuando compras JacArrow Pro, RevenueCat registra tu recibo y un
`appUserId` anónimo (UUID generado en tu dispositivo). Esto es necesario
para que la app pueda verificar tu compra en usos posteriores y durante «Restaurar
compras». El recibo procede de la App Store o de Google Play, según dónde hayas
comprado. La
[política de privacidad de RevenueCat](https://www.revenuecat.com/privacy) se aplica. Nunca enviamos
tu nombre, correo electrónico u otros datos personales.

### Análisis y datos de fallos del sistema operativo
Tanto Apple como Google pueden enviar a los desarrolladores cifras anónimas y
agregadas sobre uso y fallos, pero solo si **tú** lo has activado en los ajustes
de tu teléfono. Es una función de la tienda, no nuestra: solo vemos totales,
nunca nada que pueda rastrearse hasta ti. Lo usamos para corrección de errores y
optimización de rendimiento.

- **iPhone:** se controla con «Compartir análisis de la app». Desactívalo en
  **Ajustes → Privacidad y seguridad → Análisis y mejoras**.
- **Android:** se controla con «Uso y diagnóstico». Desactívalo en
  **Ajustes → Google → Uso y diagnóstico** (el nombre exacto varía ligeramente
  según el fabricante).

### Sentry (solo si has activado los informes de fallos)
Sentry es un servicio de monitorización de errores que nos ayuda a identificar y
corregir errores en JacArrow. Sentry solo recibe datos si has dado tu
**consentimiento explícito** a través de **Ajustes → Privacidad → Informes de fallos**
(el interruptor está desactivado por defecto).

Cuando se activa, se envía lo siguiente a los servidores europeos de Sentry (Alemania):
- Trazas de pila de fallos (nombres de archivos, números de línea, tipos de excepción)
- Modelo de dispositivo y versión del sistema operativo (iOS o Android)
- Versión de la app y número de build

**No** enviamos:
- Información personal (sin nombre, sin correo electrónico, sin ID de usuario vinculado a la identidad)
- Trazas de rendimiento ni transacciones (`tracesSampleRate: 0`)
- Direcciones IP (`sendDefaultPii: false`)

Puedes desactivar los informes de fallos en cualquier momento con el mismo interruptor. Cuando
está desactivado, Sentry **no se inicializa** y no se realiza ninguna solicitud de red.
La [política de privacidad de Sentry](https://sentry.io/privacy/) se aplica a los datos recibidos.

---

## Lo que NO recopilamos

- Ninguna cuenta de usuario, correo electrónico ni contraseña
- Ningún almacenamiento en la nube, ninguna copia de seguridad en nuestros servidores, ninguna sincronización entre dispositivos
- Ningún dato de GPS ni de ubicación
- Ningún acceso a contactos, calendario, cámara o micrófono
- Ningún rastreador de terceros (Firebase Analytics, Google Analytics, Facebook Pixel, etc.)
- Ningún identificador publicitario (IDFA en iOS, ID de publicidad en Android)
- Ningún seguimiento de vídeo ni huella digital del dispositivo

---

## Tus derechos (RGPD)

Tienes los siguientes derechos en virtud del Reglamento General de Protección de Datos:

**Derecho de acceso (Art. 15):** Todos tus datos están almacenados localmente en tu dispositivo.
Tienes visibilidad completa a través de:
- Ajustes → Mis sesiones (todas las rondas históricas)
- Ajustes → Mis objetivos (todos los objetivos activos y archivados)
- Ajustes → Arcos / Juegos de flechas / Campos (gestión del equipamiento)

**Derecho a la portabilidad de los datos (Art. 20):** Usa
**Ajustes → Exportar mis datos** para descargar todos tus datos como archivo JSON.
El archivo se puede compartir a través del menú de compartir del teléfono por
correo, AirDrop, Archivos, Google Drive, etc. Esta es tu historia de tiro
completa en formato estándar.

**Derecho de supresión (Art. 17):**
- *Eliminar una sesión individual:* desliza la sesión en la pantalla principal → Eliminar
- *Eliminar todos los datos:* desinstala JacArrow — tanto iOS como Android
  eliminan automáticamente toda la base de datos SQLite y AsyncStorage. El
  recibo de una compra Pro lo conserva la tienda donde compraste (Apple o
  Google) y RevenueCat para fines de reembolso y soporte.

**Derecho de limitación y oposición (Art. 18–21):** JacArrow no toma
ninguna decisión automatizada sobre ti. El motor Smart Insights solo analiza
tus propios datos de entrenamiento localmente en tu dispositivo y presenta
observaciones — no toma decisiones en tu nombre.

**Derecho a retirar el consentimiento (Art. 7):** El consentimiento de análisis
de Apple y Google se controla en los ajustes de tu teléfono (véase «Análisis y
datos de fallos del sistema operativo» más arriba). Los informes de fallos a
Sentry se desactivan en JacArrow desde **Ajustes → Privacidad**. Los datos de
RevenueCat se eliminan cuando eliminas el ID de Apple o la cuenta de Google con
la que se realizó la compra.

---

## Cambios

Actualizaremos esta política cuando se produzcan cambios significativos en cómo procesamos
los datos. Los cambios se comunican mediante:
1. Fecha «Última actualización» en la parte superior de esta página
2. Banner in-app en el primer arranque después de la actualización si el cambio es sustancial
   (p. ej. nuevos terceros, nueva recopilación de datos)

---

## Reclamaciones

Si crees que estamos tratando tus datos personales en violación del RGPD,
tienes derecho a presentar una reclamación ante tu autoridad nacional de protección de datos:

- **España:** [Agencia Española de Protección de Datos (AEPD)](https://www.aepd.es/)
- **UE/EEE:** encuentra tu autoridad en
  [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)

Te animamos a contactarnos primero en galge.vender.0a@icloud.com — nos tomamos
todas las consultas de privacidad en serio.
