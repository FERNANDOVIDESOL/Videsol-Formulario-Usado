# Videsol — Formulario de Revisión de Vehículo en Permuta

Herramienta interna para vendedores de Videsol Automotora. Permite registrar el estado de un vehículo recibido en permuta y generar un documento imprimible en una sola hoja A4.

## Cómo usar

1. Abrir `revision VERSION 2.html` en el navegador
2. Completar los datos del vehículo
3. Seleccionar piezas con daño en el diagrama interactivo de carrocería
4. Registrar el estado de cada neumático
5. Completar el estado técnico (prueba de manejo, prueba estática, interior, capot)
6. Hacer clic en **Imprimir / Guardar PDF** para obtener el documento en una hoja A4

## Archivos

| Archivo | Descripción |
|---|---|
| `revision VERSION 2.html` | Aplicación principal |
| `1.jpg` | Vista lateral izquierda del vehículo |
| `2.jpg` | Vista superior del vehículo |
| `3.jpg` | Vista lateral derecha del vehículo |
| `4.jpg` | Vista frontal del vehículo |
| `5.jpg` | Vista trasera del vehículo |

## Funcionalidades

- Diagrama interactivo de carrocería con 5 vistas y 17 piezas seleccionables
- Neumáticos con 3 estados visuales: sano (negro), medio uso (marrón), cambiar (rojo)
- Impresión compacta: solo muestra los ítems marcados, todo en una hoja A4
- Exportación a Word (.docx) sin dependencias externas
- Campos de valor de permuta y gasto previsto de preparación
