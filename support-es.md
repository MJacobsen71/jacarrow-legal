# Soporte — JacArrow

**Última actualización:** 2026-08-22
**Versión cubierta:** v1.0+
**Contacto:** galge.vender.0a@icloud.com

---

## Ayuda rápida

### ¿Cómo registro una tanda?

1. Abre JacArrow → toca **Nueva sesión** en la pestaña Inicio
2. Elige campo, diana y formato de ronda → toca **Iniciar sesión**
3. **Toca sobre la diana** para colocar cada flecha — usa pinch-zoom y la lupa de precisión para mayor exactitud
4. Toca **Guardar tanda** cuando todas las flechas estén colocadas
5. Repite para cada tanda hasta completar la ronda

### ¿Cuál es la diferencia entre X y 10?

El anillo X es el anillo más interior y vale 10 puntos — igual que el 10. JacArrow registra la X por separado porque la X se usa como desempate en competición. Toca el botón «X» cuando una flecha impacte en el anillo X en modo score-pad.

### ¿Cómo corrijo una flecha mal colocada?

1. Mantén pulsada la flecha sobre la diana → se activa la lupa de precisión
2. Arrastra la flecha a la nueva posición → suelta
3. O toca la flecha para seleccionarla → toca **Eliminar** para quitarla

En modo score-pad: toca la insignia de la flecha en el score-pad y elige un nuevo valor.

### ¿Qué es el post-registro (el icono 📋)?

El icono 📋 marca las sesiones introducidas manualmente con el score-pad, no registradas sobre la diana con coordenadas. El mapa de impactos, la constelación y el análisis de dispersión no están disponibles para sesiones post-registradas — solo los totales de puntuación.

### ¿Cómo compro Pro?

1. Toca cualquier función bloqueada con Pro (p. ej. un tema con la insignia Pro)
2. Aparece el paywall con el botón **Comprar Pro (299 NOK)**
3. Aparece la ventana de compra de la tienda → confirma (Face ID / código en iPhone, cuenta de Google en Android)
4. Pro se activa de inmediato — todas las funciones se desbloquean

**Precio:** 299 NOK pago único, de por vida. Sin suscripción, sin cobros recurrentes.

### ¿Cómo restauro las compras en un teléfono nuevo?

1. Descarga JacArrow en el teléfono nuevo (versión gratuita)
2. Inicia sesión con la misma cuenta con la que compraste Pro — ID de Apple en iPhone, cuenta de Google en Android
3. Abre JacArrow → **Ajustes → Licencia → Restaurar compras**
4. Pro se reactiva automáticamente

Una compra no puede pasar de una plataforma a otra: si compraste Pro en iPhone no vale en un teléfono Android, y al contrario. Las tiendas no lo permiten. Si has cambiado de ID de Apple o de cuenta de Google: contacta galge.vender.0a@icloud.com y te ayudaremos.

### ¿Cómo exporto mis datos?

**Ajustes → Sobre la app → Exportar mis datos** → aparece el menú de compartir del teléfono. Elige AirDrop, Mail, Archivos, Google Drive o donde quieras enviar el archivo JSON.

El JSON contiene todas las sesiones, rondas, flechas, objetivos, configuraciones de arco y ajustes — portabilidad completa según el art. 20 del RGPD.

### ¿Cómo elimino todos mis datos?

Desinstala JacArrow → tanto iOS como Android eliminan automáticamente toda la base de datos SQLite y todos los ajustes. No queda ningún dato residual en el dispositivo.

Si has comprado Pro: el recibo se mantiene con la tienda donde compraste — Apple o Google (para fines de reembolso y soporte). Desinstalar no afecta a reinstalaciones futuras — Pro se reactiva automáticamente vía Restaurar compras.

### ¿Qué formatos de ronda son compatibles?

- **WA 720** (aire libre, 6 tandas × 12 flechas = 72 flechas)
- **WA 18 m en sala** (10 tandas × 3 flechas)
- **WA 1440** (4 distancias sucesivas)
- **Vegas Shoot** (10 tandas × 3 flechas en sala 18 m)
- **AGB Portsmouth** (10 tandas × 3 flechas en sala 20 yd)
- **NFAA Indoor** (12 tandas × 5 flechas en sala 20 yd)
- **Entrenamiento libre** (sin límites de formato)

Todos los formatos cumplen oficialmente el WA Book 3: línea cortada al alza, registro separado de X, radios de anillos correctos.

### ¿Qué dianas son compatibles?

- **Diana WA 122 cm 10 anillos** (estándar aire libre)
- **Diana WA 80 cm 10 anillos** (aire libre larga distancia)
- **Diana WA 40 cm 10 anillos** (en sala, único spot)
- **Diana WA 40 cm Vegas 3-spot triangular** (competición en sala)
- **Diana WA 40 cm Vegas 3-spot vertical** (alternativa en sala)
- **Diana AGB Portsmouth 60 cm 10 anillos** (en sala UK)
- **Diana NFAA en sala spot único azul 40 cm** (USA)
- **Diana NFAA en sala 5-spot azul 40 cm** (competición USA)

---

## Problemas técnicos

### La app se cierra al iniciar

1. Apaga y enciende el teléfono
2. Si persiste: desinstala y reinstala JacArrow (los datos de compra NO se pierden — el recibo permanece en la tienda)
3. Envíanos una descripción a galge.vender.0a@icloud.com — qué estabas haciendo justo antes del cierre y qué teléfono tienes

**iPhone:** puedes encontrar el log de cierre tú mismo y adjuntarlo: **Ajustes → Privacidad y seguridad → Análisis y mejoras → Datos de análisis** → busca el log de JacArrow → compártelo con nosotros. Si tienes «Compartir análisis de la app» activado, recibimos los logs automáticamente.

**Android:** los cierres se nos informan automáticamente si tienes «Uso y diagnóstico» activado en los ajustes del teléfono. No necesitas hacer nada más que describir qué ocurrió.

### Los datos de puntuación desaparecieron tras una actualización

JacArrow almacena todo localmente en SQLite. Las actualizaciones migran la base de datos solo hacia adelante — los datos antiguos se convierten al nuevo formato, nunca se eliminan.

Si experimentas pérdida de datos:
1. Verifica que estés conectado con la misma cuenta que antes (ID de Apple o cuenta de Google)
2. Comprueba **Ajustes → Sobre la app → Número de versión** — ¿está actualizada?
3. Envíanos una descripción a galge.vender.0a@icloud.com

Tenemos una regla estricta de que las migraciones publicadas son inmutables — la pérdida de datos por actualizaciones nunca debería ocurrir. Si ocurre, tenemos un bug y queremos enterarnos.

### El pinch-zoom no funciona en la diana

1. Prueba con dos dedos, no uno
2. Comprueba que la reducción de movimiento no esté activada — **iPhone: Ajustes → Accesibilidad → Movimiento**, **Android: Ajustes → Accesibilidad → Quitar animaciones** — puede limitar gestos en algunas apps
3. Cierra la app por completo (desliza hacia arriba desde abajo, desliza JacArrow hacia arriba) y reábrela

### La constelación vibra al arrastrar

Fue un bug en v0.28.2 y anteriores — corregido en v0.28.3. Actualiza la app a la última versión en App Store o Google Play.

---

## Comentarios y solicitudes

### Sugerir una nueva función

Envía un correo a galge.vender.0a@icloud.com con:
- **Qué** quieres (breve descripción)
- **Por qué** (¿qué mejoraría en tu entrenamiento?)
- **Con qué frecuencia** la usarías (diario / por sesión / menos frecuente)

Leemos cada solicitud y publicamos las funciones priorizadas en el flujo «Novedades» de la app.

### Reportar un bug

Envía un correo a galge.vender.0a@icloud.com con:
- **Qué falló** (con todo el detalle que puedas)
- **Qué esperabas que ocurriera**
- **Paso a paso** para reproducirlo
- **Versión del sistema operativo y modelo de teléfono** (iPhone: Ajustes → General → Información · Android: Ajustes → Acerca del teléfono)
- **Versión de JacArrow** (Ajustes → Sobre la app)
- Captura si es relevante

### General
Respondemos a todas las consultas en un plazo de 3 días laborables. Los problemas urgentes (cierres que te impidan tirar) tienen prioridad mayor.

---

## RGPD y privacidad

Para la política de privacidad completa: [Privacidad](https://mjacobsen71.github.io/jacarrow-legal/privacy-es)

Para exportar tus datos, eliminar una sesión o ejercer otros derechos RGPD: consulta la Política de privacidad.

Reclamaciones de privacidad: contáctanos **primero** en galge.vender.0a@icloud.com. Si no podemos resolver el asunto, puedes reclamar ante tu autoridad nacional de protección de datos. Para España: [AEPD](https://www.aepd.es/).

---

## Sobre JacArrow

**Desarrollador:** Morten Jacobsen, Noruega
**Página web:** [mjacobsen71.github.io/jacarrow-legal](https://mjacobsen71.github.io/jacarrow-legal)
**Política de privacidad:** [Privacidad](https://mjacobsen71.github.io/jacarrow-legal/privacy-es)
**Licencias (open source):** consulta Ajustes → Sobre la app → Licencias en la app

JacArrow es un proyecto de un solo desarrollador, hecho para arqueros de todos los niveles — desde tu primera flecha hasta tu centésima competición. La puntuación conforme al WA Book 3 está ahí desde el primer día, lista cuando la quieras. Construido con React Native + Expo + TypeScript + SQLite. Sin backend, sin nube, sin tracking.

Gracias por usar la app. 🏹
