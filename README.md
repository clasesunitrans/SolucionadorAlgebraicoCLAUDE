# SolucionadorAlgebraicoCLAUDE
La version de CLAUDE solucionadorAlgebraicoCLAUDE tiene validaciones de la expresion de entrada con expresiones regulares pero no permite resolver 2 ecuaciones con 2 incognitas
tiene codigo para MAXXNiveles de Validación:
1. Validación Básica:
* Longitud mínima y máxima
* Entrada no vacía
2. Validación de Caracteres:
* Solo permite caracteres matemáticos válidos
* Bloquea caracteres peligrosos como <, >, ;, &
3. Validación de Estructura:
* Paréntesis balanceados
* No operadores consecutivos
* Solo un signo de igualdad
4. Validación de Seguridad:
* Bloquea palabras como eval, function, script
* Previene inyección de código
5. Validación de Sintaxis:
* No puede empezar con operadores (excepto -)
* No puede terminar con operadores
* Detecta división por cero
