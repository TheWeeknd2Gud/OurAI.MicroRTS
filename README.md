# OurAI.MicroRTS
Nuestro bot para informe basado en la Competicion de IA MicroRTS

Para ejecutar OurAI, se debe realizar lo siguiente

1. Clonar OurAI y microRTS (https://github.com/santiontanon/microrts)
2. pegar el archivo OurAI.java en la ruta microRTS/src/ai/abstraction
3. Ir a la ruta microRTS/src/gui/frontend y editar el archivo FEStatePane.java y realizar los siguientes cambios:
4. agregar la siguiente linea de codigo al incio del archivo: "import ai.abstraction.OurAI;"
5. Luego, ir a la linea 130, donde se encuentra un array de IA y agregar OurAI.class
6. Una vez realizados estos cambios, compilar microRTS por java
