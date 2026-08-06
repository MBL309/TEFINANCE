# Política de Privacidad — TEFI

**Última actualización:** 6 de agosto de 2026  
**Versión:** 1.0  
**Aplicación:** TEFI (Finanzas Personales)  
**Plataformas:** iOS (App Store) y Android (Google Play)

---

## 1. Información del responsable

| Campo | Detalle |
|-------|---------|
| **Propietario** | MBL Development (persona física) |
| **Nombre comercial** | TEFI |
| **País de constitución** | República Dominicana |
| **Correo de contacto** | soporte@tefiapp.com |
| **Correo de privacidad** | privacy@tefiapp.com |
| **Sitio web** | https://tefiapp.com |

---

## 2. Alcance de esta política

Esta Política de Privacidad describe cómo TEFI ("la App", "nosotros", "nuestro") recopila, utiliza, almacena, protege y comparte la información personal de los usuarios ("usted", "el usuario") que utilizan nuestra aplicación móvil disponible en Apple App Store y Google Play Store.

Al crear una cuenta o utilizar la App, usted acepta las prácticas descritas en esta política. Si no está de acuerdo, no utilice la App.

---

## 3. Descripción de la aplicación

TEFI es una aplicación de finanzas personales que permite a los usuarios:

- Registrar ingresos y gastos
- Crear y gestionar presupuestos
- Establecer metas de ahorro
- Administrar tarjetas de crédito y préstamos
- Hacer seguimiento de inversiones y fondos de emergencia
- Crear listas de compras
- Generar informes financieros con inteligencia artificial (solo usuarios Pro)

**Público objetivo:** Personas mayores de 13 años interesadas en gestionar sus finanzas personales.  
**Edad mínima:** 13 años. La App verifica la edad del usuario durante el registro.  
**Dirigida a niños:** No. La App no está dirigida a menores de 13 años ni recopila intencionalmente datos de menores de dicha edad.  
**Disponibilidad:** La App estará disponible a nivel mundial, con enfoque principal en República Dominicana, Estados Unidos, México, España y Latinoamérica.

---

## 4. Métodos de registro y autenticación

La App ofrece los siguientes métodos de autenticación:

| Método | Disponible | Datos obtenidos |
|--------|-----------|-----------------|
| Google (OAuth 2.0) | Sí | Email, tokens de sesión |
| Apple (Sign in with Apple) | Sí (solo iOS) | Email (posiblemente relay de Apple), nombre |
| Email / Contraseña | No | — |
| Facebook | No | — |
| Invitado | No | — |

**Eliminación de cuenta:**
- El usuario puede eliminar su cuenta directamente desde la App (Perfil → "Eliminar cuenta").
- La eliminación es inmediata y automatizada.
- Se eliminan permanentemente todos los datos del usuario de todas las tablas del sistema.
- Se elimina la cuenta de autenticación.
- Este proceso es irreversible.

---

## 5. Datos personales recopilados

### 5.1 Datos obligatorios (proporcionados por el usuario)

| Dato | Finalidad | Base legal |
|------|-----------|-----------|
| Correo electrónico | Identificación de cuenta, comunicaciones de servicio | Ejecución del contrato |
| Fecha de nacimiento | Verificación de edad mínima (≥13 años), perfil del usuario | Ejecución del contrato, obligación legal (COPPA) |

### 5.2 Datos opcionales (proporcionados por el usuario)

| Dato | Finalidad | Base legal |
|------|-----------|-----------|
| Personalidad financiera | Personalización de la experiencia | Consentimiento |
| Moneda preferida | Formato de cantidades monetarias | Ejecución del contrato |
| Días de interacción preferidos | Personalización de la experiencia | Consentimiento |

### 5.3 Datos financieros (proporcionados por el usuario)

| Dato | Finalidad | Base legal |
|------|-----------|-----------|
| Ingresos (monto, tipo, descripción, fecha) | Registro y gestión financiera | Ejecución del contrato |
| Presupuestos (categoría, montos, periodo) | Gestión de presupuestos | Ejecución del contrato |
| Metas de ahorro (título, monto objetivo, plazo) | Seguimiento de objetivos financieros | Ejecución del contrato |
| Tarjetas de crédito (nombre, límite, saldo, tasa) | Gestión de deuda | Ejecución del contrato |
| Préstamos (monto, tasa, cuota, plazo) | Gestión de deuda | Ejecución del contrato |
| Inversiones (tipo, monto, rendimiento) | Gestión de patrimonio | Ejecución del contrato |
| Fondos de emergencia (monto, meta) | Gestión de ahorro | Ejecución del contrato |
| Listas de compras (items) | Organización de gastos | Ejecución del contrato |

**Nota importante:** TEFI no solicita ni almacena números de cuenta bancaria, números de tarjeta completos, CVV, contraseñas bancarias ni credenciales de acceso a instituciones financieras.

### 5.4 Datos recopilados automáticamente

| Dato | Finalidad | Base legal |
|------|-----------|-----------|
| Token JWT / sesión | Autenticación persistente | Ejecución del contrato |
| ID de publicidad (IDFA/GAID) | Publicidad no personalizada (solo usuarios Free) | Consentimiento (ATT en iOS) |
| Información del dispositivo (modelo, OS) | Funcionamiento del SDK de publicidad | Interés legítimo |
| Dirección IP | Comunicación de red, seguridad | Interés legítimo |
| Datos de transacciones de compra | Gestión de suscripción Pro | Ejecución del contrato |

### 5.5 Datos que NO recopilamos

- Ubicación / GPS
- Contactos
- Fotos / Cámara / Micrófono
- Datos de salud
- Información biométrica
- Número de teléfono
- Dirección postal
- Datos de otras aplicaciones
- Historial de navegación

---

## 6. Permisos del dispositivo

| Permiso | Plataforma | Uso | Obligatorio |
|---------|-----------|-----|-------------|
| Internet | Ambas | Comunicación con servidores (Supabase, AdMob, OAuth) | Sí |
| App Tracking Transparency (ATT) | iOS | Solicitar consentimiento para usar identificador de publicidad | Sí (para publicidad) |
| Ad ID (GAID) | Android | Identificador de publicidad para mostrar anuncios | Automático |

**Permisos que NO utilizamos:**
- Cámara
- Micrófono
- Ubicación / GPS
- Bluetooth / NFC
- Contactos
- Calendario
- Fotos / Galería
- Archivos / Almacenamiento (excepto almacenamiento interno de la app)
- Notificaciones Push

---

## 7. Finalidad del tratamiento de datos

Utilizamos sus datos personales para los siguientes fines:

| Finalidad | Datos utilizados | Base legal |
|-----------|------------------|-----------|
| Crear y mantener su cuenta | Email, fecha de nacimiento | Ejecución del contrato |
| Autenticación e inicio de sesión | Email, tokens OAuth | Ejecución del contrato |
| Proporcionar el servicio de gestión financiera | Todos los datos financieros | Ejecución del contrato |
| Personalizar la experiencia | Personalidad financiera, moneda, preferencias | Consentimiento |
| Generar informes con IA (solo Pro) | Datos financieros completos | Consentimiento (acción del usuario) |
| Gestionar suscripciones | ID de usuario, datos de transacción | Ejecución del contrato |
| Mostrar publicidad no personalizada (solo Free) | ID de publicidad, info del dispositivo | Consentimiento (ATT) / Interés legítimo |
| Verificar la edad del usuario | Fecha de nacimiento | Obligación legal |
| Proteger la seguridad del servicio | IP, tokens, logs de errores | Interés legítimo |
| Mejorar la aplicación | Datos agregados y anónimos de uso | Interés legítimo |

---

## 8. Compartición de datos con terceros

### 8.1 Proveedores de servicios

| Tercero | Datos que recibe | Para qué los usa | Ubicación |
|---------|------------------|------------------|-----------|
| **Supabase** (backend) | Email, fecha de nacimiento, datos financieros, tokens | Almacenamiento de datos, autenticación, ejecución de funciones | Estados Unidos (AWS) |
| **Google AdMob** | ID de publicidad, info del dispositivo, interacciones con anuncios | Mostrar anuncios no personalizados a usuarios Free | Estados Unidos |
| **Google** (OAuth) | Credenciales OAuth | Autenticación del usuario | Estados Unidos |
| **Apple** (Sign in with Apple) | Identity token | Autenticación del usuario | Estados Unidos |
| **RevenueCat** | ID de usuario (UUID), historial de compras, estado de suscripción | Gestión de suscripciones in-app | Estados Unidos |
| **Proveedor de IA** (Google Gemini / OpenAI / Groq / DeepSeek — configurable) | Datos financieros del usuario (en formato JSON, sin email ni identificadores personales) | Generación de informes financieros con IA | Estados Unidos |

### 8.2 Principios de compartición

- **No vendemos datos personales** a terceros bajo ninguna circunstancia.
- **No compartimos datos para publicidad personalizada.** Los anuncios son configurados como no personalizados (`requestNonPersonalizedAdsOnly: true`).
- Los datos solo se comparten con terceros cuando es estrictamente necesario para proporcionar el servicio.
- Cada proveedor está sujeto a sus propias políticas de privacidad y términos de servicio.

### 8.3 Datos enviados a la IA

Cuando el usuario (solo suscriptores Pro) solicita activamente generar un informe financiero:

- **Qué se envía:** Datos financieros del usuario (ingresos, presupuestos, tarjetas, préstamos, metas, inversiones, fondos) en formato JSON. **No se envían** email, nombre, fecha de nacimiento ni identificadores personales.
- **Cómo se envía:** Server-side desde una Edge Function segura (no directamente desde el dispositivo).
- **Almacenamiento:** Los proveedores de IA pueden almacenar temporalmente los datos según sus propias políticas. Consulte las políticas de privacidad del proveedor específico.
- **Entrenamiento:** No autorizamos a ningún proveedor a usar los datos de nuestros usuarios para entrenar modelos de IA.
- **Control del usuario:** El usuario inicia activamente cada generación de informe. No se envían datos automáticamente.

---

## 9. Publicidad

### 9.1 Proveedor publicitario

| Campo | Detalle |
|-------|---------|
| Proveedor | Google AdMob |
| Tipo de anuncios | Banners (adaptativo anclado, banner estándar, rectángulo mediano) |
| Personalización | **No personalizada** — `requestNonPersonalizedAdsOnly: true` |
| Quién ve anuncios | Solo usuarios del plan Free |
| Usuarios Pro | No ven publicidad |

### 9.2 Datos utilizados para publicidad

- ID de publicidad (IDFA en iOS / GAID en Android)
- Información del dispositivo (modelo, sistema operativo)
- Dirección IP
- Datos de interacción con anuncios (impresiones, clics)

### 9.3 Consentimiento publicitario

- **iOS:** Se solicita consentimiento mediante App Tracking Transparency (ATT) antes de inicializar el SDK de publicidad. Si el usuario rechaza, no se accede al IDFA.
- **Android:** El usuario puede resetear o desactivar su ID de publicidad desde la configuración del dispositivo.
- No utilizamos cookies publicitarias ni publicidad personalizada.
- No utilizamos redes publicitarias adicionales (Meta, Unity Ads, AppLovin, etc.).

---

## 10. Compras y suscripciones

### 10.1 Modelo de monetización

| Plan | Precio | Características |
|------|--------|-----------------|
| Free | Gratis | Funciones básicas + publicidad |
| Pro | Suscripción de pago | Todas las funciones + informes IA + sin publicidad |

### 10.2 Procesamiento de pagos

| Campo | Detalle |
|-------|---------|
| Gestor de suscripciones | RevenueCat |
| Procesador iOS | Apple In-App Purchases (App Store) |
| Procesador Android | Google Play Billing |
| Datos de pago | Procesados exclusivamente por Apple/Google — TEFI no almacena datos de tarjeta ni información de pago |
| Renovación | Automática según el periodo seleccionado |
| Cancelación | Desde la configuración de suscripciones de App Store / Google Play |
| Reembolsos | Gestionados por Apple / Google según sus políticas |

### 10.3 Datos de suscripción que almacenamos

- Estado de suscripción (activa/inactiva)
- Tipo de plan
- Fecha de inicio/expiración del periodo
- ID de transacción (proporcionado por RevenueCat)

No almacenamos datos de tarjeta de crédito, número de cuenta ni información de pago del usuario.

---

## 11. Seguridad

Implementamos las siguientes medidas de seguridad para proteger sus datos:

### 11.1 Encriptación y comunicaciones

| Medida | Descripción |
|--------|-------------|
| HTTPS / TLS | Toda la comunicación entre la app y los servidores está encriptada en tránsito |
| JWT (JSON Web Tokens) | Autenticación segura con tokens firmados |
| OAuth 2.0 | Protocolo estándar de autenticación delegada (Google, Apple) |
| Auto-refresh de tokens | Renovación automática de sesiones sin intervención del usuario |

### 11.2 Protección de datos

| Medida | Descripción |
|--------|-------------|
| Row Level Security (RLS) | Cada usuario solo puede acceder a sus propios datos en la base de datos |
| Validación de entrada (Zod) | Todos los datos son validados antes de ser almacenados |
| Queries parametrizadas | Protección automática contra inyección SQL |
| Verificación server-side | Las Edge Functions verifican autenticación antes de procesar solicitudes |

### 11.3 Control de acceso

| Medida | Descripción |
|--------|-------------|
| Autenticación obligatoria | No se puede acceder a datos sin estar autenticado |
| Sesiones seguras | Tokens con expiración y renovación automática |
| Rate limiting | Limitación de solicitudes por defecto de Supabase |
| Service Role protegido | Claves administrativas solo accesibles en funciones server-side |

### 11.4 Medidas NO implementadas actualmente

- MFA (autenticación multifactor): No disponible
- Almacenamiento encriptado en dispositivo: Los tokens se almacenan en AsyncStorage (protección del OS pero sin encriptación adicional)

---

## 12. Conservación de datos

| Tipo de dato | Periodo de conservación | Qué ocurre después |
|--------------|------------------------|---------------------|
| Datos de cuenta (email, perfil) | Mientras la cuenta esté activa | Eliminados al eliminar la cuenta |
| Datos financieros | Mientras la cuenta esté activa | Eliminados al eliminar la cuenta |
| Tokens de sesión | Hasta cierre de sesión o expiración | Eliminados automáticamente |
| Logs de errores (server-side) | Máximo 90 días | Eliminados automáticamente |
| Datos de suscripción | Mientras la cuenta esté activa + periodo requerido por ley fiscal | Eliminados tras periodo legal |
| Informes de IA generados | Mientras la cuenta esté activa | Eliminados al eliminar la cuenta |
| Copias de seguridad del servidor | Máximo 30 días | Rotación automática |

**Eliminación de cuenta:** Al eliminar su cuenta, todos sus datos personales son eliminados de forma inmediata y permanente de nuestros sistemas activos. Las copias de seguridad automáticas del servidor se eliminan dentro de los 30 días siguientes a su rotación natural.

---

## 13. Derechos del usuario

Independientemente de su ubicación, usted tiene los siguientes derechos sobre sus datos personales:

| Derecho | Descripción | Cómo ejercerlo |
|---------|-------------|----------------|
| **Acceso** | Conocer qué datos personales tenemos sobre usted | Enviar solicitud a privacy@tefiapp.com |
| **Rectificación** | Corregir datos inexactos o incompletos | Directamente desde la App (Perfil) o por email |
| **Eliminación** | Eliminar todos sus datos | Botón "Eliminar cuenta" en la App (inmediato y automatizado) |
| **Portabilidad** | Recibir una copia de sus datos en formato legible | Enviar solicitud a privacy@tefiapp.com |
| **Oposición** | Oponerse al tratamiento de sus datos | Enviar solicitud a privacy@tefiapp.com |
| **Limitación** | Solicitar que limitemos el uso de sus datos | Enviar solicitud a privacy@tefiapp.com |
| **Retirar consentimiento** | Retirar el consentimiento otorgado en cualquier momento | Desactivar ATT en ajustes del dispositivo; eliminar cuenta |
| **No discriminación** | No ser discriminado por ejercer sus derechos | Garantizado |

**Plazo de respuesta:** Responderemos a cualquier solicitud dentro de los 30 días naturales siguientes a su recepción. En casos complejos, este plazo puede extenderse hasta 60 días, notificándole previamente.

**Cómo ejercer sus derechos:** Envíe un correo a **privacy@tefiapp.com** indicando:
- Su dirección de email asociada a la cuenta
- El derecho que desea ejercer
- Cualquier información adicional relevante

---

## 14. Cookies y tecnologías similares

### 14.1 En la aplicación móvil

La App **no utiliza cookies**. Como aplicación nativa, utiliza:

| Tecnología | Uso | Datos almacenados |
|-----------|-----|-------------------|
| AsyncStorage | Persistencia de sesión | Token JWT, preferencias locales |
| SDK de AdMob | Publicidad | ID de publicidad, métricas de anuncios |
| SDK de RevenueCat | Suscripciones | Estado de compra, customer info |

### 14.2 En el sitio web (tefiapp.com)

El sitio web puede utilizar cookies esenciales para su funcionamiento. No utiliza cookies de seguimiento ni analíticas de terceros.

---

## 15. Transferencias internacionales de datos

Sus datos pueden ser transferidos y almacenados en servidores ubicados fuera de su país de residencia:
Servicio	Ubicación de datos	Salvaguardas
Supabase	Estados Unidos (AWS us-east-1)	Cláusulas contractuales estándar, certificación SOC 2
Google (AdMob, OAuth)	Estados Unidos	Certificado bajo el EU-U.S. Data Privacy Framework (DPF), cláusulas contractuales estándar
Apple (Auth)	Estados Unidos	Cláusulas contractuales estándar
RevenueCat	Estados Unidos	Cláusulas contractuales estándar
Proveedor de IA	Estados Unidos (proveedor actual, sujeto a cambio)	Cláusulas contractuales estándar

No aseguramos de que todas las transferencias internacionales se realicen con salvaguardas adecuadas conforme a la legislación aplicable.

---

## 16. Legislación aplicable

Esta política se rige por y cumple con:

| Legislación | Jurisdicción | Aplicación |
|-------------|-------------|------------|
| Ley 172-13 | República Dominicana | Protección integral de datos personales |
| COPPA | Estados Unidos | Protección de menores de 13 años |
| CCPA / CPRA | California, EE.UU. | Derechos de privacidad del consumidor |
| GDPR | Unión Europea / EEE | Reglamento general de protección de datos |
| LFPDPPP | México | Ley de protección de datos personales |
| LOPDGDD | España | Ley orgánica de protección de datos |

### 16.1 Información específica para residentes de la UE/EEE (GDPR)

- **Base legal del tratamiento:** Las bases legales para el tratamiento de sus datos se especifican en la Sección 5 de esta política.
- **Responsable del tratamiento:** MBL Development, República Dominicana.
- **Derecho a reclamar:** Puede presentar una reclamación ante la autoridad de protección de datos de su país.
- **Transferencias fuera del EEE:** Se realizan con base en cláusulas contractuales estándar aprobadas por la Comisión Europea.

### 16.2 Información específica para residentes de California (CCPA/CPRA)

- **Venta de datos:** No vendemos información personal de los usuarios.
- **Derecho a saber:** Puede solicitar información sobre los datos recopilados en los últimos 12 meses.
- **Derecho a eliminar:** Puede eliminar su cuenta directamente desde la App.
- **Derecho a optar por no participar:** No aplica (no vendemos datos).
- **No discriminación:** No discriminamos a usuarios que ejercen sus derechos.

---

## 17. Menores de edad

- La App requiere una edad mínima de **13 años**.
- La verificación se realiza durante el registro mediante la fecha de nacimiento proporcionada.
- **No recopilamos intencionalmente datos de menores de 13 años.**
- Si un padre o tutor descubre que su hijo menor de 13 años ha creado una cuenta, puede contactarnos a privacy@tefiapp.com y eliminaremos la cuenta y todos los datos asociados.
- La App **no está dirigida a niños** según la definición de COPPA.
- No mostramos publicidad dirigida a menores.

---

## 18. Inteligencia artificial

### 18.1 Uso de IA en la App

| Campo | Detalle |
|-------|---------|
| Función | Generación de informes financieros personalizados |
| Disponibilidad | Solo para usuarios con suscripción Pro |
| Proveedores posibles | Google Gemini, OpenAI, Groq, DeepSeek (configurable) |
| Activación | Solo cuando el usuario solicita activamente generar un informe |

### 18.2 Datos enviados a la IA

- Datos financieros del usuario en formato JSON (ingresos, presupuestos, tarjetas, préstamos, metas, inversiones, fondos)
- **No se envían:** email, nombre, fecha de nacimiento, ni identificadores personales
- Los datos se envían desde el servidor (Edge Function), no directamente desde el dispositivo

### 18.3 Almacenamiento y entrenamiento

- Los informes generados se almacenan en nuestra base de datos mientras la cuenta esté activa
- **No autorizamos** a los proveedores de IA a usar los datos de nuestros usuarios para entrenar sus modelos
- La retención de datos por parte del proveedor de IA está sujeta a sus propias políticas (generalmente temporal para procesamiento)

### 18.4 Disclaimer

Los informes generados con IA son orientativos y no constituyen asesoría financiera profesional. No deben tomarse como un informe financiero oficial.

---

## 19. Notificaciones push

La App actualmente **no utiliza notificaciones push**. Si en el futuro se implementan, se solicitará el consentimiento del usuario y se actualizará esta política.

---

## 20. Información específica para App Store y Google Play

### 20.1 Resumen de recopilación de datos

| Pregunta | Respuesta |
|----------|-----------|
| ¿Qué datos recopila la app? | Email, fecha de nacimiento, datos financieros ingresados por el usuario, ID de publicidad, datos de transacción de suscripción |
| ¿Por qué los recopila? | Para proporcionar el servicio de gestión financiera, autenticación, publicidad (Free), y suscripciones |
| ¿Cómo se protegen? | HTTPS/TLS, JWT, OAuth, RLS, validación Zod, queries parametrizadas |
| ¿Con quién se comparten? | Supabase (backend), Google AdMob (publicidad), RevenueCat (suscripciones), proveedor de IA (solo Pro, solo datos financieros) |
| ¿Se usan para publicidad? | Solo ID de publicidad para anuncios NO personalizados (usuarios Free) |
| ¿Se venden datos? | **No, nunca** |
| ¿Cómo eliminar la cuenta? | Perfil → "Eliminar cuenta" (inmediato y automatizado) |
| ¿Cómo eliminar los datos? | Se eliminan automáticamente al eliminar la cuenta |
| ¿Qué permisos solicita? | Internet, ATT (iOS). No solicita cámara, ubicación, contactos, etc. |
| ¿Verifica la edad del usuario? | Sí, requiere fecha de nacimiento y valida ≥13 años |
| ¿Utiliza inteligencia artificial? | Sí, para generar informes financieros (solo Pro, activado por el usuario) |
| ¿Utiliza servicios de terceros? | Sí: Supabase, Google AdMob, Google/Apple OAuth, RevenueCat, proveedor IA |
| ¿Usa notificaciones push? | No |
| ¿Realiza pagos o suscripciones? | Sí, via Apple IAP / Google Play Billing (gestionado por RevenueCat) |

---

## 21. Contacto de privacidad

Para cualquier consulta, solicitud o queja relacionada con la privacidad de sus datos:

| Canal | Detalle |
|-------|---------|
| **Email de privacidad** | privacy@tefiapp.com |
| **Email de soporte** | soporte@tefiapp.com |
| **Sitio web** | https://tefiapp.com |
| **Plazo de respuesta** | Máximo 30 días naturales |

---

## 22. Cambios a esta política

Nos reservamos el derecho de actualizar esta Política de Privacidad en cualquier momento. Cuando realicemos cambios materiales:

1. **Notificación dentro de la App** — se mostrará un aviso al usuario al iniciar sesión.
2. **Actualización en el sitio web** — la versión más reciente siempre estará disponible en https://tefiapp.com/politica-de-privacidad.
3. **Cambio de fecha** — la fecha de "Última actualización" al inicio de este documento se actualizará.

Para cambios sustanciales que afecten cómo utilizamos sus datos, solicitaremos su consentimiento nuevamente si es requerido por la legislación aplicable.

Le recomendamos revisar esta política periódicamente.

---

## 23. Consentimiento

Al crear una cuenta en TEFI, usted declara que:

- Ha leído y comprendido esta Política de Privacidad.
- Acepta el tratamiento de sus datos personales conforme a lo descrito.
- Es mayor de 13 años.
- Proporciona sus datos de forma voluntaria y veraz.

---

*Si tiene preguntas sobre esta política, contáctenos en privacy@tefiapp.com.*
