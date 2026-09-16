# Observaciones para corregir los escenarios de calidad

## Escenario 1: Comunicación entre los módulos de Operaciones Marítimas y Monitoreo

### Estímulo
Evaluar si el catálogo de operaciones son: buque atraco, contenedor descargo. ¿Son las únicas operaciones?

Se debería precisar esto para que la fuente del estímulo sea correcta y precisa en base a los módulos que estamos analizando.

### Entorno
Es poco preciso. No indica los procesos concretos de los cuales estos módulos forman parte, si es que ambos intervienen en el mismo proceso.

### Respuesta
¿La respuesta es en caso de fallo? ¿O indica el funcionamiento normal?

Consideraría especificar el caso de cómo ambos módulos intervienen o si es que se habla de solo uno. Eso no me quedó claro.

Si se está hablando de un solo módulo, entonces el análisis anterior estaría mal planteado.

---

## Escenario 2: Pérdida de conexión con GPS en el submódulo de Monitoreo

### Estímulo
¿Es suficiente decir que se interrumpe la transmisión? ¿O se tiene que precisar el tipo de interrupción o el efecto que provoca el estímulo?

En todo caso, lo que se entiende es que, de alguna forma, el sistema deja de recibir la señal del GPS, ¿cierto?

### Entorno
¿Se puede ser más preciso o es suficiente para el nivel de análisis que vamos a llevar?

---

## Escenario 3: Seguridad de los módulos de Monitoreo y Operaciones

### Por qué
No indica en concreto cuáles serían las políticas o normas legales que se arriesgan, en qué país operaría el sistema, si hay seguimiento de órganos gubernamentales o si no se respetan estándares internacionales en caso de fallar.

### Estímulo
Es poco preciso sobre qué es lo que causa el estímulo, si es ocasional o provocado, qué es lo que se identifica como incidencia crítica y si solo se presenta en caso de que afecte a ambos módulos o de manera independiente.

Es decir, habría que precisar si el escenario contempla un fallo de ambos módulos o si cualquiera de los módulos puede generar la incidencia de forma independiente.

---

## Escenario 4: Mantenibilidad de los módulos de Operaciones y Monitoreo
### Configuración de umbrales o catálogo de parámetros

### Estímulo
Se limita a dos estímulos. ¿O habría un catálogo más amplio de estímulos que deberían registrarse en este escenario de calidad?

### Artefacto
Solo se especifican los umbrales. ¿Es el único objeto o variable que permite configurar y sobre el cual recaería la responsabilidad de satisfacer este escenario de calidad?

Si el umbral es el único artefacto involucrado, entonces el estímulo tendría que ser más concreto.

Considero que puede haber incoherencias entre el apartado de **artefacto** y el **estímulo**, por lo que deberían revisarse ambos para asegurar que estén relacionados correctamente.

---

## Escenario 5

### Observación general
Parece que este escenario se confunde con **usabilidad** u **operabilidad**.

No veo claramente la relación con la capacidad, sino más bien algo cualitativo.

¿Este análisis es correcto?

¿O el nombre del escenario está bien planteado y lo que debería corregirse es la forma en que se ha definido el escenario?