# Notas de Análisis – Enc_SS.xlsx

## Hallazgos principales
La base contiene 600 encuestas con información demográfica, de caracterización y percepción del servicio. La distribución por sexo es equilibrada entre hombres y mujeres. El grupo de edad predominante corresponde a personas entre 41 y 59 años. La mayoría de los encuestados residen en zonas urbanas y en general el lugar de residencia coincide con el lugar de atención. Los estados civiles más frecuentes son casado/a y soltero/a. El nivel educativo con mayor presencia es básica secundaria, seguido por estudios superiores. En cuanto a ocupación, destacan trabajadores independientes, cuidadores del hogar y pensionados.

Respecto a la atención, la dirección de residencia coincide con la de la factura en la mayoría de los casos. Los puntos de atención más frecuentes son los SuperCade (Américas y Kennedy en primer lugar). En relación con las empresas, sobresalen Acueducto, Vanti y Enel. Los principales motivos de visita se relacionan con inconformidad frente a valores de la factura, suspensión del servicio y solicitudes de información.

## Problemas de calidad de datos
- Presencia de nombres de variables muy extensos, lo que dificulta su manejo en análisis y reportes.
- Columnas con la categoría “Otro” que en realidad contienen texto libre heterogéneo.
- Inconsistencias en la escritura de nombres de puntos de atención (ejemplo: “Super Cade 30” y “SUPER CADE 30”).
- Existencia de categorías con muy baja frecuencia que reducen la claridad en los resultados.
- Aparición de columnas vacías o con valores nulos en el 100% de los registros.

## Propuestas de limpieza
- Reducir y estandarizar los nombres de columnas.
- Unificar categorías repetidas considerando mayúsculas/minúsculas y tildes.
- Separar el texto libre de “Otro” en una columna específica para su análisis cualitativo.
- Evaluar la pertinencia de agrupar categorías de baja frecuencia en la opción “Otros”.
- Documentar las variables en un diccionario de datos para mejorar consistencia y trazabilidad.
