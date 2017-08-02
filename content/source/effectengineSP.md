---
title: "EffectengineSP"
date: 2017-08-02T18:51:02+02:00
draft: false
---

# Documento de Referencia del Sistema Effect Engine

## Uso

Este Docmento de Referencia describe el Sistema Effect Engine. Está basado en el contenido de Monsters & Magic, de Sarah Newton. Esta versión ha sido preparada por J.T. Evans, con la participación de Travis S. Casey y Julian A. G. Stanley. La traducción es obra de Pablo Ruiz-Múzquiz.

El DRS Effect Engine está orientado fundamentalmente para el uso por diseñadores de juego que desean emplear el Effect Engine como base para sus propios juegos. No está pensado, por tanto, para ser usado como un juego en sí mismo. A lo largo del documento se podrán encontrar notas marcadas entre corchetes con la intención de guiar a los diseñadores de juego en el uso de este DRS. Si la intención es emplear el DRS como un punto de partida para un juego propio, recomendamos realizar una búsqueda del texto '[NOTE'. Estas notas arrojan luz sobre el diseño del sistema y pueden señalar elementos que modificar para adaptarlo a tu escenario.

Nada en este documento deberia dar a entender que se pueda copiar nada que no sea parte de este documento. Cualquier copia procedente de otras fuentes requiere los derechos necesario o el licenciamiento de esas fuentes.

El DRS Effect Engine se publica bajo los términos de la Open Gaming License. Se puede encontrar unacopia de estos términos al final de este documento. La mara "Effect Engine" y el logo de Effect Engine se licencian de forma separada, bajo los términos de la Effect Engine Trademark License, que también se puede encontrar al final de este documento.


## Introducción: ¿Qué es el *Effect Engine*?

El Effect Engine es un sistema de juego de rol. En otras palabras, es un conjunto de métodos para usar dados que ayuden a los jugadores a relatar historias interesantes e inventadas sobre gente imaginaria.

### Los Fundamentos del Juego

Igual que otros juegos de rol, jugar a un juego basado en Effect Engine se asemeja a una conversación. Una jugadora asume el papel de **director de juego (DJ)**, mientras las otras controlan cada una un **personaje jugador (PJ)**, y se denominan habitualmente **jugadoras**.

Cada jugadora controla su propio PJ y describe las acciones de ese PJ. La DJ controla el resto del mundo del juego y describe las acciones de los otros seres en ese mundo; **personajes no jugadores (PNJs)**. PNJs potencialmente hostiles hacia los PJs a menudo se llaman **monstruos**

Cuando un personaje intenta hacer algo, a esto se le denomina **acción**. Cuando el resultado de esta acción es incierto, puede resolverse esta incertidumbre mediante una **tirada de acción**. Los resultados de las acciones pueden estar representadas en el juego como **efectos** o **consecuencias**.

### Personajes

Los personajes se definen en el juego principalmente mediante **atributos**, **rasgos** y el **nivel**. Éstas, a su vez, se utilizan para determinar otras características empleadas en el transcurso del juego. A continuación se describen brevemente las más relevantes.

**Atributos**: son un conjunto de habilidades básicas que todos los personajes tienen. Éstos indican cuán fuerte, inteligente y en general capaz son. Cada atributo dispone de una **valor** y un **modificador**. Fuerza, por ejemplo, es un atributo que indica la fuerza física de un personaje mientras que Carisma indica su habilidad para influenciar a otros socialmente. Un atributo constituirá el **atributo principal** del personaje, aquél que ha sido más empleado o desarrollado.
**Rasgos**: son palabras o frases cortas que describen detalles interesantes acerca de un personaje, como habilidades, rasos de personalidad, etc. Así, *jugar al escondite* (una habilidad), *leal al rey* (un rasgo de personalidad), *Caballero de la Tabla Redonda* (una relación con un grupo), *resistencia a venenos* (una habilidad natural poco común) o *la espada de mi padre* (un objeto) podrían ser todos rasgos.
**Nivel**: es un indicador global de cuán poderoso es un personaje. Los personajes habitualmente comienzan con nivel uno y, a medida que su nivel se incrementa, obtienen **avances** que les permiten adquirir nuevas capacidades. Habitualmente, éstas capacidades constituyen rasos adicionales.

Entre las características secundarias más usadas encontramos las defensas **mental** y **física** y los **puntos de golpe**. La defensa representa la habilidad de un personaje para evitar ser dañado por ataques físicos o mentales, mientras que los puntos de golpe representan la habilidad para "encajar el golpe", su aguante, suerte y otras habilidades que le permiten recibir sufrir daño sin quedar gravemente herido.

Algunos rasos de los personajes pueden estar determinados por su **raza** y **clase**. Éstas proporcionan **rasgos iniciales** y pueden otorgar acceso a avances especiales que otros personajes que no pertenecen a esa clase o raza no podrían conseguir normalmente, llamados **avances de clase** o **raciales**. Pueden asimismo determinar los **dados de golpe** que se usan para cancular puntos de golpe físicos y mentales. Si se emplean las clases, la clase de un personaje puede también determinar su atributo principal.
Algo particularmente importante es el hecho de que un personaje debería tratarse como una *persona* con aspiraciones, objetivos, defectos y fortalezas. Un buen personaje dispone de una personalidad que permite un desarrollo de su propia historia y que puede cambiar a lo largo del tiempo de forma sutil o más drástica. Algunos de estos cambios pueden verse representados dentro de las mecánicas de juego como modificaciones a los atributos o los rasgos pero incluso aquéllos que no lo hacen son igualmente importantes a la hora de configurar un personaje de forma completa.
[NOTA: las razas y las cases son una parte estándar de los juegos de rol fantásticos pero pueden no ser esenciales en otros escenarios de juego. Históricamente las razas alteraban los valores base de los atributos además de proveer rasgos iniciales pero *no tendrían por qué*.]


### Uso de dados

Los dados se emplean en el sistema *Effect Engine* para añadir aleatoriedad a los resultados. Se emplean abreviaturas para referirnos alos dado utilizando el formato NdX. N es el número de dados que se tiran y X es el número de caras que tiene el dado. Los resultados de todos los dados se suman, no se tratan de forma individual. En ocasiones se emplea una referencia del tipo "dX", sin un número delante de la "d", cuando se habla de tirar un solo dado.

**Ejemplo**: 3d6 se refiere a tirar tres dados, cada uno de seis caras, y sumar su total.
**Ejemplo**: "tirar un d8" significa tirar un dado de ocho caras y utilizar el resultado.

Los tipos de dados que más se emplean en el Effect Engine son d4, d6, d8, d10, d12 y d20. A estos dados se les conoce comúnmente como "dados poliédricos" y se pueden encontrar fácilmente en tiendas de juegos y comercios en internet. En ocasiones, algunos otros tipos de dados se "emulan" tirando un dado, diviendo el resultado redondeado hacia arriba. Por ejemplo, si se necesita un "d3", se puede tirar un d6, se divide entre dos y se redondea hacia arriba, de forma que 1-2 cuenta como 1, 3-4 cuenta como dos y 5-6 cuenta como 3.

En alguna ocasión, puede requerirse tirar un d100 (o d%). Esto se consigue con dos d10 de diferentes colores. En lugar de sumar ambos resultados, antes de la tirada uno es declarado el de las "decenas" mientras que el otro es el de las "unidades". Si ambos dados muestran un cero (0) en su cara superior, el resultado equivale a 100, no a 0.
**Ejemplo**: d% -- El dado de las decenas saca un 3. El dado de las unidades saca un 7. El total sería 37, no 10.
Algunos sets de dados tienen dos dados de diez caras, uno de los cuales tiene números del 0 al 9 mientras que el otro muestra múltiplos de 10, desde el 00 hasta 90. Lo habitual es unir ambos resultados salvo en el caso de obtener un "00" y un "0", que se considera un resultado de 100. Algunos grupos de jugadores prefieran otra convención en donde "10" y "0" equivalen a 100 y "00" y "0" se considera como 10.

### Hacer cosas

Si la capacidad de un personaje para hacer algo es incierta, el DJ puede aplicar una **resistencia** (también llamada **dificultad**). Ésta consiste en un número que representa cuán difícil resulta realizar la acción propuesta. Un número alto refleja una acción difícil. Para determinar si el personaje tiene éxito en la acción se realiza una tirada de dados, de hecho, cada vez que el personaje trate de hacer algo es probable que haya que tirar los dados.

Habitualmente se usan 3d6. La suma total de los dados se añade al modificador del atributo relevante del personaje (ej: FUE si se está tratando de levantar un objeto pesado, DES si se está intentando una acción basada en la agilidad, etc). Si el personaje dispone de un rasgo que podría ayudar, entonces el nivel del personaje se añade al total. Si existen otros rasgos que también podrían ayudar, cada uno aporta un +1 al resultado total, con un límite del bonus total por rasgos del doble del nivel actual del personaje. Otros bonus o penalizaciones se aplican en algunos casos, veremos algunos casos más adelante. El total de todas estas sumas se denomina **resultado total**. Este valor se compara con la **resistencia**. Si el resultado total es igual o superior a la resistencia, la diferencia entre ambos valores es el número de **puntos de efecto** que se obtienen. Si el resultado total es menor que la resistencia, a esa diferencia se la denomina **puntos de consecuencia**.

**resultado total = 3d6 + modificador del atributo relevante + bonus de rasgos +/- otros bonus y penalizaciones**

Si el resultado total es igual o mayor que la resistencia, se considera un éxito y:

**resultado total - resistencia = puntos de efecto**

En caso contrario,

**resistencia - resultado ttoal = puntos de consecuencia**

Este proceso se denomina **tirada**. Cuando un personaje trata de hacer algo, es una **tirada de acción**; si están tratando de ofrecer resistencia frente a algo o alguien (ej: esquivar un golpe, resistir un intento de intimidación, etc), es una **tirada de resistencia**, y el resultado total se convierte en la resistencia para la tirada de acción del oponente.

Para reducir el número de veces que hay que tirar los dados, a veces se emplean las tiradas estáticas para calcular las resistencias. Así, en lugar de tirar los dados, simplemente se añade 10 al bonus del atributo, los bonus de rasgos, etc. Las dos tiradas estáticas más habituales son **defensa física** y **defensa mental**.


