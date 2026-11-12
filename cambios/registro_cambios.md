Registro de cambios

# Registro de cambios

## Solicitudes
- **INC-001**: El total no considera la cantidad. Criterio: Precio 50 x cantidad 3 = S/ 150.
- **CR-002**: Aplicar descuento de 10% desde S/ 200. Criterio: Subtotal 200 -> S/ 180; subtotal 150 -> S/ 150.

## Matriz de Impacto
| Criterio | INC-001 | CR-002 |
|---|---|---|
| Requisito | RF-001 | RF-002 (nuevo) |
| Archivo | src/ventas.py | src/ventas.py; docs/requisitos.md |
| Riesgo | Total incorrecto | Descuento incorrecto en umbral |
| Prueba | 50 x 3 = 150 | Subtotales 150, 200 y 300 |
| Decisión | Aprobada | Aprobada |

INC: Implementada y verificada