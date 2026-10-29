# Product brief

## Description
Gestor en Salud es el panel de una comercializadora de planes de salud prepagos. Entran consultas, el asistente de WhatsApp las califica y se las pasa a un asesor. El equipo ve la cola, los chats, el pipeline y el reporte en https://panel.gestorensalud.com. La ayuda pública vive en docs.gestorensalud.com.

## Primary audience
Quien usa el panel todos los días: asesor comercial, supervisor de equipo, gerencia comercial y administrador. Llega a la ayuda para saber qué botón tocar, qué significa un estado o quién puede cambiar algo.

## Jobs to be done
- Entrar, terminar los primeros pasos y conectar WhatsApp.
- Atender un lead que el asistente ya derivó.
- Mover una consulta en el pipeline y marcarla afiliada o perdida.
- Entender qué mira Pulso y qué aviso le llega.
- Invitar al equipo y elegir un plan, si es administrador.

## Motivation
La comercializadora necesita un solo lugar para los leads que entran (Zoho, anuncios, WhatsApp) y para el trabajo del asesor. La ayuda no es técnica: nombra las pantallas como se ven.

## Assumptions
- No hay cuentas de prueba para capturas. Si no hay imagen, la página marca el lugar con un comentario MDX. Una captura con datos ficticios puede ir en `images/` cuando el equipo la pasa.
- El color primario de la ayuda es el acento del panel (`#D9503F`). No hay archivo de logo; el isotipo de `src/app/icon.svg` se usa como favicon.
- Zoho entra leads, pero en el menú actual no hay una pantalla para conectarlo.
- La agenda y las campañas no están en el menú, aunque algunas tarjetas de plan y grupos de plantillas todavía nombran llamadas.
