# Ejercicio 09 - Interfaz bancaria

## Qué he aprendido
- A utilizar MovementProps para definir qué datos espera recibir los componentes, y la funcion Movement para recibir las props y construir una fila con los datos recibidos

## Respuesta a la pregunta de comprensión
¿Qué partes de esta pantalla convertirías en componentes y cuáles dejarías directamente en App? Justifica.

Respuesta:
Todo lo relacionado con los movimientos como movementInfo o movementTitle los convertiría en componentes reutlizables porque se van a utlizar para cada movimiento bancario realizado.

## Qué he modificado
- He creado una card grande con el balance disponible y cards mas pequeñas con componentes reutilizables que muestren los movimientos, el concepto y el saldo que entra y sale de la cuenta.

## Resultado
Ha quedado una interfaz minimalista con el saldo disponible en grande y una lista de los movimientos de la cuenta bancaria de la que podemos añadir más y scrollear para ver todos los movimientos realizados.