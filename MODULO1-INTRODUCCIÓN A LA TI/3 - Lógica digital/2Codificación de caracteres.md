> [!TIP]  
> [Ver video](https://youtu.be/7aqeC_H6PXY)


# Fundamentos de la Computación: Codificación de Caracteres y Modelos de Color

 ¿Recuerdas del video anterior que un byte solo puede almacenar ceros y unos? Eso significa que podemos tener 256 valores posibles. Al final de este video aprenderás cómo podemos representar palabras, números, emojis y muchas cosas más que vemos en nuestras pantallas, con solo estos 256 valores posibles. Todo gracias a la codificación de caracteres.

 La codificación de caracteres se utiliza para asignar nuestros valores binarios a caracteres para que nosotros, como humanos, podamos leerlos. Definitivamente no nos gustaría ver todo el texto en nuestros correos electrónicos y páginas web representado en complejas secuencias de ceros y unos. Aquí es donde la codificación de caracteres nos viene bien.

 Puedes pensar en la codificación de caracteres como un diccionario. Para las computadoras, es la manera de buscar qué caracteres humanos deben estar representados por un valor binario dado. El estándar de codificación de caracteres más antiguo utilizado es ASCII. Representa el alfabeto inglés, dígitos y signos de puntuación. El primer carácter en la tabla de conversión ASCII/binario, una "a" minúscula, se mapea como 0 1 1 0 0 0 0 1 en binario. Esto se hace para todos los caracteres que puedes encontrar en el alfabeto inglés, así como los números y algunos símbolos especiales.

 Lo bueno de ASCII era que solo necesitábamos usar 127 valores de nuestros 256 posibles. Duró mucho tiempo, pero, al final, no fue suficiente. Se crearon otros estándares de codificación de caracteres para representar diferentes idiomas, diferentes cantidades de caracteres y más.

 Con el tiempo, se requerirían más de los 256 valores que podíamos tener. Luego vino UTF-8. El estándar de codificación más usado hoy en día. Además de tener la misma tabla ASCII, también nos permite usar un número variable de bytes. ¿Qué quiero decir con eso? Piensa en cualquier emoji. No es posible hacer emojis con un solo byte dado que solo podemos almacenar un carácter en un byte, en cambio, UTF-8 nos permite almacenar un carácter en más de un byte, lo que significa infinita diversión con emojis.

 UTF-8 se basa en el estándar de Unicode. No vamos a entrar en mucho detalle, pero el estándar de Unicode nos ayuda a representar la codificación de caracteres de manera uniforme. Ahora que podemos representar letras, números, signos de puntuación e incluso emojis, ¿cómo representamos el color? Bueno, hay todo tipo de modelos de color. Por ahora, mantengámonos en uno básico, que se usa en muchas computadoras: RGB o modelo rojo, verde y azul. Al igual que los colores reales, si mezclas una combinación de cualquiera de estos, podrás obtener la gama completa de colores.

 En el mundo de las computadoras, usamos 3 caracteres para el modelo RGB. Cada carácter representa un tono del color y eso luego cambia el color del píxel que ves en tu pantalla. Con solo ocho combinaciones de ceros y unos, pudimos representar todo lo que ves en tu computadora, desde una simple letra "a", al mismo video que estás viendo ahora mismo en el sitio web de Coursera. Muy bueno.

 En el siguiente video, hablaremos sobre cómo generamos realmente los ceros y los unos.
