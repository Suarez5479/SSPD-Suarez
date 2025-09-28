# Notas de Análisis – Enc_SS.xlsx

## Hallazgos principales
La base contiene 600 encuestas con información demográfica, de caracterización y percepción del servicio. La distribución por sexo es equilibrada entre hombres y mujeres. El grupo de edad predominante corresponde a personas entre 41 y 59 años. La mayoría de los encuestados residen en zonas urbanas y en general el lugar de residencia coincide con el lugar de atención. Los estados civiles más frecuentes son casado/a y soltero/a. El nivel educativo con mayor presencia es básica secundaria, seguido por estudios superiores. En cuanto a ocupación, destacan trabajadores independientes, cuidadores del hogar y pensionados.

Respecto a la atención, la dirección de residencia coincide con la de la factura en la mayoría de los casos. Los puntos de atención más frecuentes son los SuperCade (Américas y Kennedy en primer lugar). En relación con las empresas, sobresalen Acueducto, Vanti y Enel. Los principales motivos de visita se relacionan con inconformidad frente a valores de la factura, suspensión del servicio y solicitudes de información.

## 2. Problemas de calidad detectados
- Hay columnas completamente vacías o casi sin información: `Otro`, `Otro.3`, `Otro.4`, `Otro.6`, `Otro.9`, `Otro.15`, `Otro.17`.  
- En los campos "Otro" con texto libre, hay respuestas muy variadas, algunas repetidas con pequeñas diferencias de escritura.  
- Se identifican preguntas con una sola opción de respuesta (variables casi constantes), que no aportan variabilidad al análisis.  
- Existen columnas con demasiados valores distintos (alta cardinalidad), que hacen difícil resumir la información sin agrupar.  

