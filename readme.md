Actividad Clase 10, Emiliano Daniel Tallarico, com 3

Ejercicio 1:
Investigar y documentar críticas a los patrones de diseño. Mencione ejemplos concretos.

Los patrones de diseño son herramientas útiles, pero a menudo se suelen criticar por su Sobreingeniería, su complejidad innecesaria, su uso injustificado y por su antiguo
uso para lenguajes más limitados.
1)Sobreingeniería: Aplicar patrones donde no hay un problema real, esto suele hacer el código mucho más complejo. Un ejemplo puede ser el abuso de Abstract factory o Factory method cuando requerimos clases simples o resolver consultas de manera simple.
2)Complejidad innecesaria: Ocurre cuando la solución propuesta es más compleja que el problema original, lo que hace que sea dificil de entender y mantener. Un ejemplo seria el uso de el patron Chain of Responsibility para resolver una validación sencilla.
3)Uso injustificado: La mala práctica de aplicar patrones de aplicar patrones cuando no son necesarios. Un ejemplo podría ser el uso de el patron Decorator para agregar funcionalidades básicas que simplemente podrian estar en la herencia.
4)Antiguo uso para lenguajes limitados: Algunos patrones surgieron para solucionar carencias o problemas de lenguajes antiguos, los lenguajes modernos resuelven algunos de estos problemas de manera nativa. Un claro ejemplo es el del patron Strategy
que en un lenguaje más moderno como Phyton se resulven facilmente con funciones de primera clase.

Ejercicio 3:
Piense en 3 problemas habituales de su vida diaria en los cuales podría aplicar patrones de diseño.

1) Despacho e impresiones: Aplicaria Chain of Responsibility para modelar un sistema en donde luego de cada venta y mediante manejadores se verifique que la venta no fue cancelada, luego se verifique la venta este cobrada, en el tercer manejador verifique el día de entrega
del producto y el ultimo manejador envíe la orden directa para la impresion del comprobante.
2) Desayunos: Podría aplicar el patron Builder para armar el desayuno de todos los días, cada objeto sería una parte del desayuno, basado en 3 objetos, bebida, comida y acompañamiento.
3) Recetas: Usaría el patron Template Method para definir recetas en donde varíen los detalles pero el proceso general sea el mismo, un ejemplo podría ser cocinar pure, no importa si es de calabaza, de papa o de manzana, el proceso general es lo mismo.

Ejercicio 5:
¿Qué son los antipatrones de diseño? Ejemplifique algunos casos. 

Los antipatrones de diseño son supuestas soluciones que al final son ineficaces y terminan causando más problemas de los que solucionan, un antipatron es una práctica que parece razonable pero que a la larga genera un codigo propenso a erorres. Algunos ejemplos:
1)Copy-paste : Consiste en duplicar código en lugar de abstraerlo o reutilizarlo, así los bugs y errores se multiplican.
2)Spaghetti Code: Código sin estructura, flujo dificil de seguir con funciones muy largas y sin estructura clara.
