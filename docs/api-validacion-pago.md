# Especificación de API: Validación de Pago (PSWPB-5)

## Descripción
Endpoint para validar transacciones de pago entrantes en el sistema.

## Endpoint
`POST /api/v1/payments/validate`

## Parámetros de Entrada
* `transaction_id` (String): Identificador único de la transacción.
* `amount` (Number): Monto del pago.
* `status` (String): Estado retornado por la pasarela (`APPROVED`, `REJECTED`).