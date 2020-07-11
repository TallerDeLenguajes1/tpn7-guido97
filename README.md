## Resolución TP7

#### a) ¿Qué es la propiedad TabIndex? ¿Para qué se utiliza?

La propiedad TabIndex indica el orden en que los controles reciben el foco cuando el usuario presiona la tecla TAB en un formulario. De forma predeterminada, este orden es igual que el orden en el que se crearon los controles. La numeración comienza en 0.

#### b) ¿Cómo funciona el foco en un control en particular?

El foco de un objeto es una propiedad que permite la interacción desde la entrada. Existen eventos que pueden poner o sacar el foco de un objeto, como al hacerle clic, o con la tecla TAB, se obtiene el foco, mientras que los otros objetos lo pierden. Aquel control que tenga el foco, es posibilitado de recibir eventos desde la entrada, ya sea un onPressed por ejemplo desde el teclado (con enter o el espacio) o recibir texto, como en el caso de los TextInput, no lo reciben si no están enfocados.

#### c) ¿Qué son los eventos? ¿Cómo se utilizan los eventos del teclado?

Los eventos son sucesos que se generan ante una determinada acción. Una clase puede generarlos y otra recibirlos, disparando una acción para determinado evento. Por ejemplo un clic puede ser un evento, o apretar una tecla del teclado.
Los eventos del teclado se reciben desde un mismo método, éste tiene como argumento la tecla que generó el evento, debiendose diferenciar cual fue para ejecutar la tarea correspondiente.