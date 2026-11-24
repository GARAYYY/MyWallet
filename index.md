# Política de privacidad de MyWallet

**Última actualización:** 24 de noviembre de 2026

MyWallet es una aplicación para iOS para gestionar tus finanzas personales de forma manual: movimientos, cuentas, presupuestos, objetivos de ahorro, suscripciones y calendario financiero. Esta política explica qué datos trata la aplicación, para qué, con quién se comparten y cuáles son tus derechos.

## 1. Responsable del tratamiento

- **Responsable:** [JON GARAY CUADRADO]
- **Ubicación:** [VITORIA, ESPAÑA]
- **Contacto de privacidad:** [mywallet.esp@gmail.com]

## 2. Qué datos tratamos

### Datos de tu cuenta
- Dirección de correo electrónico.
- Contraseña. Se gestiona mediante el servicio de autenticación de Supabase, que la almacena cifrada. No tenemos acceso a tu contraseña en claro.
- Nombre (opcional).

### Datos financieros que introduces tú
- **Movimientos:** importe, comercio, nota, categoría, fecha, cuenta y origen del registro (manual, suscripción, objetivo, transferencia, Apple Pay, etc.).
- **Cuentas:** nombre, tipo, entidad (texto libre), icono, color, saldo inicial y límite de crédito.
- **Presupuestos, objetivos de ahorro y aportaciones.**
- **Suscripciones y elementos programados** (nóminas, recibos, cuotas de préstamo): nombre, importe, periodicidad, fechas, estado y, si lo eliges, un logotipo o emoji.
- **Categorías** personalizadas.

MyWallet **no se conecta a tu banco** y no accede a números de tarjeta, claves bancarias ni saldos reales de tus entidades. Los datos son los que tú introduces.

### Atajo de pagos con Apple Pay (opcional)
Si configuras el atajo en la app Atajos, este envía a MyWallet el importe, el comercio y el nombre de la tarjeta tal como lo indica Wallet (no el número). Con ellos se crea un movimiento en tu cuenta. Si no tienes conexión, el pago queda en una cola en tu dispositivo hasta que se pueda enviar.

### Suscripción MyWallet Premium
- Las compras se realizan a través de Apple (App Store). **No recibimos ni almacenamos tus datos de pago.**
- Para asociar tu compra a tu cuenta, usamos un identificador de usuario (el identificador interno de tu cuenta) como referencia de la transacción de Apple.
- Guardamos el estado de tu plan (gratuito o Premium) en nuestra base de datos.

### Notificaciones
- **Avisos locales** (recordatorios de cobros y avisos de pagos registrados): se programan en tu dispositivo.
- **Notificaciones push** (si las activas): guardamos el token de notificaciones de tu dispositivo, la plataforma y el entorno, para poder enviártelas.

### Datos técnicos
Nuestro proveedor de infraestructura puede registrar datos técnicos de conexión (por ejemplo, la dirección IP o el tipo de dispositivo) con fines de seguridad y funcionamiento del servicio.

### Datos que se quedan solo en tu dispositivo
- Preferencias de tema, idioma, notificaciones y privacidad.
- Configuración del bloqueo de la app. **El desbloqueo con Face ID, Touch ID o código lo gestiona iOS;** MyWallet solo recibe el resultado (correcto o no) y nunca accede a tus datos biométricos.
- Una instantánea de tus cifras (balance, saldo, presupuestos) compartida entre la app y sus widgets mediante un contenedor seguro de la app (App Group).
- Cola de pagos pendientes, vínculo entre tarjetas y cuentas, y caché de cuentas para el atajo.

## 3. Para qué usamos tus datos y base legal

| Finalidad | Base legal (RGPD) |
|---|---|
| Crear y mantener tu cuenta, y prestar las funciones de la app | Ejecución del contrato (art. 6.1.b) |
| Sincronizar tus datos entre dispositivos y ofrecer copias de seguridad | Ejecución del contrato (art. 6.1.b) |
| Gestionar tu plan Premium y sus límites | Ejecución del contrato (art. 6.1.b) |
| Enviarte notificaciones push | Consentimiento (art. 6.1.a), que puedes retirar en los ajustes de iOS |
| Seguridad, prevención de abusos y mantenimiento del servicio | Interés legítimo (art. 6.1.f) |
| Cumplir obligaciones legales aplicables | Obligación legal (art. 6.1.c) |

**No vendemos tus datos, no hacemos publicidad, no usamos analítica ni herramientas de seguimiento, y no tomamos decisiones automatizadas que te afecten.** Los análisis y previsiones que ves en la app se calculan en tu dispositivo.

## 4. Con quién compartimos tus datos

Para funcionar, MyWallet se apoya en estos proveedores, que actúan como encargados del tratamiento:

- **Supabase:** autenticación, base de datos, funciones de servidor y envío de los correos de confirmación y recuperación de contraseña. [REGIÓN DEL PROYECTO DE SUPABASE, por ejemplo: «Frankfurt, Unión Europea»].
- **Apple:** App Store y compras de suscripciones (StoreKit), notificaciones push (APNs) y la app Atajos. Al buscar el logotipo de una suscripción, el texto que escribes como nombre se envía a la API de búsqueda de iTunes de Apple.
- **Google:** al buscar el logotipo de una suscripción por su sitio web, puede consultarse el servicio público de iconos de Google, al que se envía únicamente el dominio.

No compartimos tus datos con ningún otro tercero, salvo obligación legal.

## 5. Transferencias internacionales

Si alguno de los proveedores anteriores trata datos fuera del Espacio Económico Europeo, lo hace con garantías adecuadas, como las cláusulas contractuales tipo de la Comisión Europea o el Marco de Privacidad de Datos UE-EE. UU. cuando proceda.

## 6. Cuánto tiempo conservamos tus datos

- Mientras tengas una cuenta activa.
- Puedes **eliminar tu cuenta** en cualquier momento desde *Ajustes → Perfil → Eliminar cuenta*. Se borran tu cuenta y todos los datos asociados de nuestros sistemas.
- También puedes usar *Ajustes → Datos y copias de seguridad → Eliminar todos mis datos* para borrar tus datos manteniendo la cuenta.
- Las copias de seguridad de la infraestructura pueden conservar los datos de forma residual durante un máximo de [PLAZO, por ejemplo: «30 días»] hasta su eliminación automática.
- Al cerrar sesión se borran de tu dispositivo la instantánea de los widgets, la cola de pagos pendientes y los vínculos de tarjetas.
- **Eliminar la cuenta no cancela la suscripción Premium.** Debes cancelarla desde los ajustes de suscripciones de tu Apple ID. Apple conserva sus propios registros de compra según su política.
- Las copias de seguridad en JSON y las exportaciones CSV que generes y guardes fuera de la app quedan bajo tu responsabilidad. Contienen tus datos financieros sin cifrar.

## 7. Tus derechos

Puedes ejercer en cualquier momento los derechos de acceso, rectificación, supresión, limitación del tratamiento, oposición y portabilidad, y retirar tu consentimiento cuando el tratamiento se base en él:

- **Acceso, rectificación y supresión:** directamente desde la app (editar tus datos, eliminar datos o eliminar la cuenta).
- **Portabilidad:** desde *Ajustes → Datos y copias de seguridad* puedes exportar tus datos en JSON y CSV.
- **Cualquier otra solicitud:** escribe a [EMAIL DE CONTACTO]. Responderemos en el plazo máximo de un mes.

Si consideras que no hemos tratado tus datos correctamente, puedes presentar una reclamación ante la **Agencia Española de Protección de Datos** (<https://www.aepd.es>).

## 8. Seguridad

- Las comunicaciones entre la app y el servidor se realizan cifradas (HTTPS/TLS).
- Cada usuario solo puede acceder a sus propios datos, gracias a las políticas de seguridad a nivel de fila de la base de datos.
- Las contraseñas se almacenan cifradas.
- Puedes activar el bloqueo de la app con Face ID, Touch ID o código, y ocultar los importes en los widgets.

Ningún sistema es infalible, pero aplicamos medidas razonables para proteger tu información.

## 9. Menores

MyWallet no está dirigida a menores de [EDAD MÍNIMA, por ejemplo: «16»] años y no recopilamos datos de menores de forma consciente. Si crees que un menor nos ha facilitado datos, escríbenos y los eliminaremos.

## 10. Cambios en esta política

Podemos actualizar esta política, por ejemplo si añadimos nuevas funciones como la conexión con entidades bancarias. Publicaremos la versión vigente en esta misma página con su fecha de actualización y, si el cambio es relevante, te lo comunicaremos en la app.

## 11. Contacto

Para cualquier duda sobre privacidad: [EMAIL DE CONTACTO]
