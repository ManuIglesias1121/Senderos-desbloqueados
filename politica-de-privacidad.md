# Política de Privacidad

**Aplicación:** Senderos Desbloqueados
**Última actualización:** 18 de mayo de 2026
**Versión:** 1.4

---

## 1. Quiénes somos

**Senderos Desbloqueados** es una aplicación móvil de motivación para caminantes y trekkers, que registra logros, valida recorridos por GPS y permite llevar un seguimiento del progreso del usuario en distintos senderos de Argentina.

El **Responsable del Tratamiento** de los datos personales recogidos a través de la aplicación es:

| | |
|---|---|
| **Nombre** | Juan Manuel Iglesias |
| **CUIT** | 20-26670296-6 |
| **Domicilio** | Av. de la Virreina 794, Barrio Lomas del Cauquén, San Carlos de Bariloche, Río Negro (CP 8400), Argentina |
| **Correo electrónico (legal / Responsable Persona Física)** | juan_manuel_iglesias@hotmail.com |
| **Correo de contacto general / soporte** | senderosdesbloqueados@gmail.com |
| **Teléfono** | (2944) 41-2637 |

El Responsable se encuentra **inscripto ante el Registro Nacional de Bases de Datos Personales** de la Agencia de Acceso a la Información Pública (AAIP) bajo el legajo:

> **RL-2026-49237420-APN-DNPDP#AAIP**

---

## 2. Información de la base de datos

La base de datos personales utilizada por la aplicación se encuentra registrada ante la AAIP bajo el expediente:

> **EX-2026-49272464-APN-DNPDP#AAIP**

**Denominación:** Senderos Desbloqueados — Usuarios.
**Carácter:** Privado.
**Marco normativo aplicable:** Ley 25.326 de Protección de Datos Personales (Argentina) y su Decreto Reglamentario 1558/2001.

---

## 3. Qué datos recopilamos

Solo recopilamos los datos estrictamente necesarios para que la aplicación funcione. Concretamente:

### 3.1. Datos identificatorios
- Dirección de correo electrónico (al crear la cuenta).
- Contraseña, almacenada siempre **cifrada con bcrypt** — nunca tenemos acceso a tu contraseña en texto plano.

### 3.2. Datos de geolocalización
- Coordenadas GPS (latitud, longitud, altitud, velocidad, timestamp) **capturadas exclusivamente durante el recorrido activo de un sendero**, con el fin de validar su cumplimiento.
- En el **Plan Free**, la captura ocurre únicamente mientras la app está abierta y en primer plano (la pantalla encendida y la app visible). Si el usuario bloquea la pantalla o minimiza la app, el tracking se pausa.
- En el **Plan Premium**, la captura **puede continuar en segundo plano** (con la pantalla apagada o la app minimizada) para no perder tramos del trayecto en senderos largos. Esto se hace mediante un *servicio en primer plano* (foreground service) que **muestra una notificación persistente** en tu dispositivo mientras la grabación está en curso, de manera que siempre sabés cuándo está activo el GPS.
- **Apenas finalizás, cancelás o pausás el recorrido, el tracking se detiene completamente** y la notificación desaparece.
- **No** rastreamos tu ubicación cuando no hay un recorrido activo iniciado por vos.

### 3.3. Datos de actividad de uso
- Senderos completados y logros desbloqueados (incluidos los "desafíos" conquistados).
- Progreso acumulado (kilómetros, ascenso, recorridos válidos, listas completadas).
- Fecha y hora de las actividades realizadas.
- Fotos opcionales que el usuario decida tomar durante un recorrido (waypoints).
- Si te postulás al **directorio de guías habilitados**, los datos profesionales que vos mismo cargás en tu ficha pública (nombre, número de matrícula, zonas de trabajo, contacto, etc.).

### 3.4. Datos transaccionales
- Si adquirís funciones premium, registramos únicamente un indicador del estado de tu suscripción (activa/inactiva, fecha de vencimiento).
- **Nunca** almacenamos datos de tarjetas de crédito, débito ni información financiera. Todas las compras se procesan a través de **Apple App Store** o **Google Play**, quienes manejan los datos de pago bajo sus propias políticas de privacidad.

### 3.5. Datos que NO recopilamos
- Datos sensibles (salud, religión, ideología política, orientación sexual, origen racial, etc.).
- Datos de antecedentes penales o contravencionales.
- Información de tus contactos, mensajes ni otras apps de tu dispositivo.
- Tu ubicación cuando la app está cerrada.

---

## 4. Para qué usamos tus datos

Los datos personales se tratan exclusivamente con las siguientes finalidades:

1. **Gestión de tu cuenta de usuario** (registro, autenticación, recuperación de contraseña).
2. **Validación del cumplimiento de senderos** mediante comparación de tu recorrido GPS contra el trazado oficial del sendero (GPX).
3. **Registro de tu progreso y logros**, para que puedas visualizar tu historial y desbloquear insignias.
4. **Procesamiento de suscripciones premium**, a través de las plataformas de pago in-app de Apple y Google.
5. **Comunicaciones operativas esenciales** vinculadas al uso del servicio (avisos legales, cambios en esta política, soporte).

**No utilizamos tus datos para:**
- Publicidad dirigida.
- Venta de información a terceros.
- Perfilado con fines comerciales.
- Comunicaciones promocionales no solicitadas.

---

## 5. Cómo recopilamos los datos

Todos los datos son recolectados **directamente del titular** a través de la aplicación móvil, previo consentimiento informado al momento del registro y la aceptación de esta Política de Privacidad. No obtenemos datos por cesión de terceros (ni privados ni públicos).

---

## 6. Sobre el GPS y tu ubicación

Esta sección merece una explicación detallada porque entendemos la sensibilidad del dato.

### 6.1. Cuándo se activa el GPS

- La app **solicita permisos de ubicación** la primera vez que iniciás un recorrido. En Android, se solicitan dos permisos separados: ubicación **mientras se usa la app** y ubicación **en segundo plano**. El segundo es opcional y solo necesario si querés que el tracking siga con la pantalla apagada.
- El GPS se activa **únicamente** cuando vos presionás "Iniciar recorrido" (o "Grabar salida libre" / "Grabar sendero" en modo administrador) y se detiene en el momento que lo finalizás, cancelás o pausás.

### 6.2. Tracking en segundo plano

- Para recorridos largos (varias horas), una vez iniciado el recorrido la captura de GPS **continúa aunque bloquees la pantalla o minimices la app**, para evitar perder tramos del trayecto.
- Mientras esto sucede, tu dispositivo muestra una **notificación persistente** ("Senderos está registrando tu trayecto por GPS") que no podés deslizar para descartar — su única función es transparentarte que el GPS está en uso. Apenas finalizás o cancelás el recorrido, esa notificación desaparece automáticamente.
- **Nunca** rastreamos tu ubicación si no hay un recorrido activo iniciado por vos. No hay "tracking pasivo", ni análisis de patrones de movimiento, ni publicidad basada en ubicación.

### 6.3. Qué hacemos con esas coordenadas

- Las coordenadas se almacenan asociadas a tu cuenta para validar el cumplimiento del sendero (comparándolas contra el GPX oficial), mostrarte tu historial y calcular tus estadísticas acumuladas.
- Cuando descargás un **mapa offline** (función premium), las coordenadas del área del mapa elegido se envían a **Mapbox** solo para que te devuelva los *tiles* cartográficos correspondientes. Mapbox no recibe tu identidad ni asocia esa consulta a tu cuenta.

### 6.4. Cómo revocar el acceso

- Podés **revocar el permiso de ubicación** (foreground y/o background) en cualquier momento desde la configuración del sistema operativo de tu dispositivo.
- Si revocás el permiso de ubicación, no vas a poder validar nuevos recorridos, pero seguirás teniendo acceso al resto de las funciones de la app (catálogo de senderos, directorio de guías, perfil, currículum).
- Si revocás solo el permiso de background, los recorridos van a funcionar pero el GPS se va a pausar cada vez que bloquees la pantalla, lo que probablemente invalide los recorridos largos.

---

## 7. Con quién compartimos tus datos

**No vendemos, alquilamos ni cedemos tus datos a terceros con fines comerciales.**

Para que la aplicación funcione, contratamos a proveedores tecnológicos que actúan como **encargados del tratamiento** (no como cesionarios). Esto significa que procesan datos exclusivamente por cuenta nuestra y siguiendo nuestras instrucciones, sin destinarlos a fines propios. Los proveedores son:

| Proveedor | Para qué | Datos a los que accede |
|---|---|---|
| **Supabase Inc.** | Alojamiento de la base de datos y autenticación | Email, contraseña hasheada, datos de actividad, geolocalización y, si te postulás, ficha de guía habilitado |
| **Mapbox Inc.** | Provisión de mapas, tiles cartográficos y descarga de mapas offline | Coordenadas del área del mapa que se carga en pantalla o se descarga (no recibe tu identidad ni tu cuenta) |
| **Apple Inc.** | Procesamiento de pagos in-app en iOS | Datos financieros del usuario (no nos son transmitidos) |
| **Google LLC** | Procesamiento de pagos in-app en Android | Datos financieros del usuario (no nos son transmitidos) |

Cada uno de estos proveedores cuenta con sus propias políticas de seguridad y privacidad, que pueden consultarse en sus respectivos sitios web.

### 7.1. Directorio público de guías habilitados

Si te postulás al directorio de guías, los datos que cargás en tu ficha (nombre, matrícula, zonas, contacto que vos elegís exponer) se hacen **públicos dentro de la aplicación** y pueden ser visualizados por cualquier usuario. Esto no es una cesión de datos a terceros: es una publicación voluntaria con tu consentimiento explícito al postularte, equivalente a publicar tu información profesional en una guía telefónica o un directorio. Podés solicitar baja del directorio en cualquier momento desde tu perfil o por los canales de la sección 11.

---

## 8. Transferencia internacional de datos

Tus datos personales son procesados parcialmente fuera del territorio argentino:

- **Supabase Inc.** (con sede en San Francisco, California, EEUU) almacena la base de datos en la región AWS **us-west-2 (Oregon, EEUU)**. Recibe email, contraseña hasheada, datos de actividad y geolocalización.
- **Mapbox Inc.** (con sede en Washington, D.C., EEUU) procesa solicitudes de tiles cartográficos. Recibe únicamente las coordenadas del área del mapa que se está visualizando, sin asociarlas a tu identidad de usuario.

Esto implica una **transferencia internacional de datos** a un país (Estados Unidos) que no posee declaración formal de adecuación por parte de la AAIP. Las transferencias se realizan al amparo de las garantías contractuales y técnicas estándar que ofrecen estos proveedores, conforme a lo previsto por los artículos 11 y 12 de la Ley 25.326.

Al aceptar esta Política de Privacidad, prestás tu consentimiento informado a estas transferencias internacionales.

---

## 9. Cuánto tiempo conservamos tus datos

Conservamos tus datos personales mientras:

- Tu cuenta de usuario esté **activa**, y
- Durante un período adicional de **12 meses posteriores a la baja** de la cuenta, con el fin de atender eventuales reclamos o requerimientos legales.

Pasado ese plazo, los datos personales identificables son **eliminados** o **anonimizados** de forma irreversible. Los datos anonimizados (sin posibilidad de re-identificación) pueden conservarse con fines estadísticos.

Si querés dar de baja tu cuenta antes, podés solicitarlo en cualquier momento (ver sección 11).

---

## 10. Cómo protegemos tus datos

Aplicamos medidas técnicas y organizativas razonables para proteger la información:

- **Cifrado en tránsito** mediante TLS 1.2 o superior (HTTPS) en todas las comunicaciones entre la aplicación y los servidores.
- **Cifrado en reposo** a nivel de base de datos.
- **Contraseñas hasheadas** con algoritmo bcrypt (no almacenamos contraseñas en texto plano).
- **Row Level Security (RLS)**: control de acceso a nivel de fila que impide que un usuario acceda a los datos de otro.
- **Acceso administrativo restringido** únicamente al Responsable del Tratamiento.
- **Registro de accesos** administrativos al sistema.

Ningún sistema es 100% invulnerable. Si se detecta un incidente de seguridad que afecte tus datos, te notificaremos sin demoras injustificadas conforme a la normativa aplicable.

---

## 11. Tus derechos como titular

Como titular de los datos, la Ley 25.326 te reconoce los siguientes derechos:

- **Acceso**: solicitar información sobre qué datos tuyos tenemos y cómo los tratamos.
- **Rectificación**: pedir que corrijamos datos inexactos.
- **Actualización**: pedir que actualicemos datos desactualizados.
- **Supresión** (derecho al olvido): pedir que eliminemos tus datos.
- **Confidencialidad** y **oposición** al tratamiento en determinados casos.

### Cómo ejercer estos derechos

Podés ejercer cualquiera de estos derechos enviando una solicitud a cualquiera de estos correos:

📧 **juan_manuel_iglesias@hotmail.com** (Responsable Persona Física registrado ante AAIP)
📧 **senderosdesbloqueados@gmail.com** (canal de contacto general de la app)

O por carta documento al domicilio:
✉️ **Av. de la Virreina 794, Barrio Lomas del Cauquén, San Carlos de Bariloche, Río Negro (CP 8400)**

En tu solicitud incluí:
1. Nombre completo y DNI.
2. El derecho que querés ejercer y los datos sobre los que recae.
3. Una forma de contacto para responderte.

Para acreditar tu identidad podemos requerir copia del frente del DNI, **anonimizando** el número de trámite, código de barras y demás datos que no sean necesarios.

### Plazos de respuesta (Ley 25.326)
- **Derecho de acceso**: 10 días corridos.
- **Rectificación, actualización o supresión**: 5 días hábiles.

El ejercicio de estos derechos es **gratuito** y a intervalos no inferiores a 6 meses, salvo que acredites un interés legítimo.

---

## 12. Menores de edad

Senderos Desbloqueados está dirigida a personas mayores de **13 años**. Las personas menores de 13 años no pueden crear cuentas sin el consentimiento expreso de su madre, padre o representante legal.

Si tomamos conocimiento de que recolectamos datos de una persona menor de 13 años sin el consentimiento parental correspondiente, eliminaremos esos datos a la brevedad. Si sos madre, padre o tutor y detectás esta situación, escribinos al correo de contacto.

---

## 13. Compras dentro de la aplicación

La app ofrece funcionalidades premium mediante suscripción o pago único, procesadas exclusivamente a través de **Apple App Store** (iOS) o **Google Play** (Android).

- **No** recibimos ni almacenamos tus datos financieros (número de tarjeta, CVV, etc.).
- Solo recibimos confirmación del estado de la compra (activa/inactiva) para habilitar las funciones premium en tu cuenta.
- Las políticas de privacidad de las pasarelas de pago de Apple y Google se aplican adicionalmente a estos pagos y pueden consultarse en sus respectivos sitios.

---

## 14. Cambios en esta Política

Podemos actualizar esta Política de Privacidad para reflejar cambios en la aplicación, en la normativa aplicable o en nuestras prácticas. Cuando hagamos cambios:

- Modificaremos la fecha de "Última actualización" al inicio del documento.
- Si los cambios son **sustanciales**, te notificaremos por correo electrónico o mediante un aviso destacado dentro de la aplicación antes de que entren en vigencia.

El uso continuado de la app después de la entrada en vigencia de los cambios implica tu aceptación de los términos actualizados.

---

## 15. Cómo contactarnos

Si tenés dudas, consultas o reclamos relacionados con esta Política de Privacidad o el tratamiento de tus datos personales:

📧 **senderosdesbloqueados@gmail.com** (canal principal de contacto)
📧 **juan_manuel_iglesias@hotmail.com** (Responsable Persona Física — para ejercicio formal de derechos)
✉️ Av. de la Virreina 794, Barrio Lomas del Cauquén, San Carlos de Bariloche, Río Negro (CP 8400), Argentina
📞 (2944) 41-2637

---

## 16. Autoridad de control

Si considerás que el tratamiento de tus datos personales no se ajusta a la normativa vigente, tenés derecho a presentar una denuncia ante la autoridad de control:

**Agencia de Acceso a la Información Pública (AAIP)**
Dirección Nacional de Protección de Datos Personales
Av. Pte. Julio A. Roca 710, Piso 2, CABA, Argentina
🌐 https://www.argentina.gob.ar/aaip
📧 datospersonales@aaip.gob.ar

---

*Esta Política de Privacidad es de cumplimiento obligatorio en el marco de la Ley 25.326 de Protección de Datos Personales de la República Argentina y su Decreto Reglamentario 1558/2001.*
