## Decisiones de diseño

Se separaron responsabilidades en gestores (GestorReservas, GestorPagos) para centralizar la lógica y evitar duplicación.

Se utilizó una PasarelaPago para abstraer el procesamiento y permitir integrar distintos métodos (tarjeta, transferencia).

El uso de actividades UML permitió modelar claramente los flujos de reserva y pago, facilitando su validación posterior.

## Estrategia de validación

Se diseñaron casos de prueba funcionales para validar los flujos críticos: registro, disponibilidad, reserva y pago.

Se consideraron escenarios de éxito y error para verificar el comportamiento del sistema frente a condiciones reales.
