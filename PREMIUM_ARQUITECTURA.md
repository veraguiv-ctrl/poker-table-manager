# Preparación para funciones Premium (sin activar)

## Separación recomendada
- Núcleo gratuito local: reparto, ciegas, temporizador, manos, idiomas y estilos.
- Módulos Premium futuros: asientos, historial de victorias, cuentas y sincronización.
- API remota privada: identificación, pagos y validación de licencias.

## Límites de seguridad
La interfaz pública nunca almacenará claves secretas, datos de pago ni credenciales de servidor.
Un control local en JavaScript no sirve para proteger prestaciones de pago.
Al diseñar el funcionamiento Premium sin conexión habrá que definir una política de comprobantes firmados y vencimiento, o exigir una validación online. No está implementado en esta versión.

## Estado actual
No existe todavía código Premium, cuentas, licencias, pagos ni backend. La arquitectura descrita es una guía para la próxima fase; el programa v1.3.4 sigue siendo gratuito y offline.
