Simulador de Evaluación Clásica de f(x)

Esta herramienta web la armé en un solo archivo usando HTML, CSS y JavaScript para simular cómo se evalúa y procesa el conteo de bits en 1 sobre cadenas binarias grandes (¡hasta de 4096 bits!), además de contrastarlo con la lógica de algoritmos como Deutsch-Jozsa.

Qué puedes hacer con esto
Elegir el tamaño: Configura cuántos bits quieres procesar y genera patrones aleatorios al instante para probar diferentes escenarios.

Ver el proceso en acción: La interfaz te muestra visualmente el recorrido bit a bit y calcula su valor en decimal usando BigInt para evitar problemas con números gigantes.

Hacer pruebas por lotes: Puedes correr hasta 500 repeticiones seguidas con patrones distintos para ver el comportamiento estadístico y la dispersión de los resultados.

Gráficas y métricas: Incluye gráficos hechos con el elemento canvas para comparar las consultas reales frente al peor caso clásico, junto con un historial detallado que mide los milisegundos exactos que toma cada cálculo.
