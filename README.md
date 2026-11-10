# casos_de_usos
actividad
Informe Técnico: Sistema de Evaluación
1. Introducción
El presente informe describe el diseño de un sistema de evaluación automatizado de opción múltiple. El objetivo es garantizar objetividad, rapidez y retroalimentación inmediata en los procesos de enseñanza-aprendizaje. El sistema permitirá a los estudiantes responder cuestionarios y obtener un puntaje automático, mientras que los docentes podrán crear y gestionar evaluaciones de manera eficiente.
2. Identificación de Clases y Objetos
 Pregunta: Contiene enunciado, opciones y respuesta correcta.
 Opción: Alternativa de respuesta asociada a una pregunta.
 Respuesta: Selección realizada por el estudiante.
 Estudiante: Usuario que responde las evaluaciones.
 Evaluación: Conjunto de preguntas configuradas por el docente.
 Puntaje: Resultado numérico obtenido tras responder.
 Docente/Administrador: Actor que crea y gestiona evaluaciones.
3. Glosario de Términos
1. Intento: Acción de un estudiante al responder una evaluación.
2. Respuesta Correcta: Opción definida como válida en una pregunta.
3. Puntaje Total: Suma de los puntajes obtenidos en todas las preguntas.
4. Evaluación Activa: Cuestionario disponible para ser respondido.
5. Retroalimentación: Información inmediata sobre el desempeño del estudiante.
4. Casos de Uso y Diagrama
Casos principales:
 Responder preguntas
 Calcular puntaje
 Mostrar resultado
 Crear evaluación
{"prompt":"Diagrama de casos de uso","progression_text":"Generando el esquema de
5. Escenarios de Casos de Uso
Escenario 1: Responder preguntas
1. El estudiante inicia sesión.
2. Selecciona una evaluación activa.
3. El sistema muestra las preguntas.
4. El estudiante selecciona opciones.
5. El sistema guarda las respuestas.
Escenario 2: Calcular puntaje
1. El estudiante finaliza la evaluación.
2. El sistema compara respuestas con las correctas.
3. Se calcula el puntaje total.
4. Se genera retroalimentación automática.
6. Fichas de Casos de Uso
Caso de Uso: Responder preguntas
 Actores: Estudiante
 Precondiciones: Evaluación activa disponible
 Postcondiciones: Respuestas almacenadas
 Flujo principal: Selección de opciones y registro en sistema
 Flujo alternativo: Error de conexión → guardar progreso parcial
Caso de Uso: Calcular puntaje
 Actores: Sistema
 Precondiciones: Respuestas registradas
 Postcondiciones: Puntaje calculado y mostrado
 Flujo principal: Comparación automática y cálculo
 Flujo alternativo: Pregunta sin respuesta → asignar cero
7. Conclusiones
El sistema de evaluación automatizado optimiza la objetividad y eficiencia en la medición del aprendizaje. La identificación de clases, glosario, casos de uso y fichas proporciona una base sólida para su implementación. El diagrama de casos de uso refleja claramente las interacciones entre estudiantes, docentes y el sistema.

