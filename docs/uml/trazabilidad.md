## Trazabilidad del sistema

Se establece la relación entre requerimientos, diseño y validación:

| HU | Caso de uso / Actividad | Clase / Método | Caso de prueba |
|----|-------------------------|----------------|----------------|
| HU1 Registro | Caso de uso: Registrarse | Usuario.registrar() | TC01, TC02 |
| HU3 Disponibilidad | Actividad: Buscar habitación | CatalogoHabitaciones.buscarHabitacion() | TC05, TC06 |
| HU4 Reserva | Actividad: Confirmar reserva | GestorReservas.confirmarReserva() | TC07, TC08 |
| HU6 Pago | Actividad: Procesar pago | GestorPagos.procesarTransaccion() / PasarelaPago.procesarPago() | TC11, TC12 |
