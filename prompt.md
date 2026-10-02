# Prompt maestro · Información estructurada

Este archivo contiene una instrucción base para utilizar IA como apoyo
en la investigación, organización y transformación de información.

La idea no es pedir directamente una página terminada.

El flujo de trabajo es:

```text
INFORMACIÓN
↓
MARKDOWN
↓
HTML SEMÁNTICO
↓
CSS
```

-

# Prompt base

Quiero construir un documento digital sobre: Una curaduría digital del libro I AM PLASTIC que da a conocer obras Art Toys por diseñadores 

# I AM PLASTIC · Información estructurada

---

# Tema

Curaduría digital del libro *I AM PLASTIC* de Paul Budnitz (publicado el 2 de noviembre de 2006) que da a conocer obras de art toys hechas por diseñadores.

**Tipo de colección:** Art toys de diseñador.

---

# Objetivo

Construir un documento de información estructurada que pueda utilizarse posteriormente para generar una página web con estilo de sitio digital.

Cada art toy lleva un tagline: una frase corta que describe al toy con personalidad, como el de Gloomy Bear.

---

# Estructura

Cada elemento mantiene exactamente los mismos campos:

```text
COLECCIÓN · I AM PLASTIC
│
├── ART TOY
│   ├── nombre
│   ├── tagline
│   ├── diseñador
│   ├── ubicación / nacionalidad
│   ├── año
│   ├── formato
│   ├── descripción del toy
│   ├── descripción del creador
│   └── enlace
│
├── ART TOY
│   └── ...
│
└── ART TOY
    └── ...
```

---

# Orden y jerarquía

**Criterio de orden:** por ubicación geográfica, siguiendo el orden del libro: Asia, Europa, Estados Unidos y Singapur.

1. **Título principal:** I AM PLASTIC · Designer Art Toys.
2. **Introducción:** contexto del fenómeno art toy y del libro.
3. **Grupos o secciones:** una sección por región.
4. **Elementos individuales:** un art toy por sección.
5. **Información secundaria:** descripción del creador, temas y notas.
6. **Fuentes o enlaces:** un enlace por toy cuando existe.

---

# Reglas

- La información se organiza de manera consistente.
- No se inventan datos.
- Si un dato no está disponible, se indica como "No disponible".
- Se mantiene una jerarquía clara con títulos y subtítulos.
- Se usan listas cuando la información es repetitiva.
- Se conservan los enlaces a fuentes o recursos relevantes.
- Sin diseño, sin CSS y sin JavaScript.
- Resultado en formato Markdown.

---

# Contenido

## Introducción

A mediados de los años 90 comenzó un fenómeno que poco a poco se globalizó y abrió las puertas a una nueva forma de expresión artística y de diseño. Los art toys denotan origen y cultura, y representan la intersección de distintos medios llevados a nuevos formatos y a la exploración de nuevas posibilidades creativas.

A través de estas figuras icónicas, los artistas nos invitan a entrar en su mundo y nos cuentan historias entrañables, llenas de personalidades únicas y peculiaridades inconfundibles.

*I AM PLASTIC* reúne más de 300 de estas obras, creadas por diseñadores notables que en su momento generaron gran conversación. A continuación exploraremos 4 figuras de distintos países que destacan la genialidad de esta forma de expresión.

---

## Asia

### Gloomy Bear

> A pesar de su tierno color rosa, Gloomy Bear demuestra que los impulsos sanguinarios no se pueden controlar…

- **Diseñador:** Mori Chack
- **Ubicación:** Tokio, Japón
- **Año:** 2004 (Chax Colony Edition)
- **Formato:** Figura de vinilo

**Descripción del toy**
Gloomy Bear nació como una crítica a la cultura kawaii y a la falsa idea de que los animales salvajes pueden domesticarse. La historia gira en torno a Pity, un niño que rescata a un osezno abandonado que, al crecer, se convierte en un enorme oso grizzly de dos metros. A pesar de los constantes ataques y de la naturaleza violenta de Gloomy, Pity nunca lo odia ni lo abandona: entiende que el oso solo actúa por instinto en este lazo trágico pero tierno.

**Descripción del creador**
Mori Chack es un creador pionero del estilo kawaii oscuro, una corriente que resalta la sátira social y la hipocresía del mundo actual.

**Enlace:** [Gloomy Bear Store](https://gloomybearstore.com/?srsltid=AfmBopmEwpDNN1UKDFiO2sQIhsiab_cnINp0HHYxk40jNW9NbOX434B)

---

## Europa

### Monsterium (Island Woodland Volume 3)

> Directo desde una isla de criaturas místicas, este pequeño monstruo demuestra que hasta lo más extraño puede tener su propio encanto…

- **Diseñador:** Pete Fowler
- **Ubicación:** Reino Unido
- **Año:** No disponible
- **Formato:** No disponible
- **Figuras destacadas:** Grynt, Boris

**Descripción del toy**
Para dar vida a sus creaciones, Pete Fowler imaginó una isla donde residen criaturas místicas. Diseñó intrincadas historias de fondo para cada personaje, otorgándoles rasgos específicos, relaciones ecológicas y distintos niveles de lo que él llama "Monsterism".

**Descripción del creador**
Pete Fowler es un ilustrador freelance y autodenominado creador de monstruos, inspirado por el arte japonés y su cultura. Su estilo posmoderno y caricaturesco se despliega en distintos medios, como el dibujo, la pintura y la escultura. Es conocido principalmente por ser el ilustrador principal de la banda Super Furry Animals, a la que dio una identidad visual conectada con la música. Su trabajo gira en torno a una narrativa central de monstruos y personajes recurrentes.

**Enlace:** [Pete Fowler Shop](https://petefowlershop.com/dept/~drawings/)

---

## Estados Unidos

### MARS-1 · Obras escultóricas en vinilo

> Entre formas biológicas y energías de otros mundos, esta criatura parece haber evolucionado más allá de lo que nuestra propia conciencia puede comprender…

- **Diseñador:** Mario Martínez (MARS-1)
- **Ubicación:** San Francisco, California · Nacionalidad estadounidense
- **Año:** No disponible
- **Formato:** Vinilo de colección con carácter escultórico

**Descripción del toy**
Las obras de MARS-1 trascienden el vinilo y se acercan a lo escultórico. Su estética tiene un lenguaje propio que se nutre tanto de referencias contemporáneas como de movimientos pasados. Su proceso está en constante evolución y se expande con cada nueva serie, explorando conceptos que van más allá de su propia conciencia.

**Temas que explora**
- Desde lo científico hasta fenómenos más esotéricos.
- Física teórica, metamorfosis y conciencia colectiva.
- Ufología y el examen de las posibilidades de otros mundos.
- El vínculo entre las ciencias físicas y las ciencias de la vida.
- Energías transicionales, multiplicidad natural, hélices y ocurrencias biológicas espontáneas.

**Descripción del creador**
Mario Martínez, también conocido como MARS-1, es un artista estadounidense con sede en San Francisco.

**Enlace:** [MARS-1 · Sculpture](https://mars-1.com/filter/SCULPTURE)

---

## Singapur

### Gehenom Zombie

> Con el cerebro al descubierto y listo para atacar, Gehenom Zombie demuestra cómo la obsesión puede terminar consumiéndote desde adentro…

- **Diseñadores:** Le Messie y Amanda Scully (LMAC)
- **Ubicación:** Singapur
- **Año:** 2005
- **Formato:** Figura de 7 pulgadas, producida por Flying Cat

**Descripción del toy**
La figura destacaba por su cabeza desmontable, que permitía ver el cerebro, y por una maza con pinchos removible. También tuvo varias versiones con diseños creados por distintos artistas.

**Descripción del creador**
LMAC, fundada en Singapur en 2004 por Le Messie y Amanda Scully, combinaba moda, música y arte, y destacó por sus camisetas, juguetes de diseñador y estética oscura. Sus figuras, especialmente los zombies, representaban temas como la obsesión y la autodestrucción dentro de un universo acompañado por la música electrónica de Le Messie.

**Nota:** LMAC ya no se encuentra activo, por lo que la información disponible sobre estas figuras es limitada.

**Enlace:** No disponible

---

# Fuentes y enlaces

- Gloomy Bear: https://gloomybearstore.com/?srsltid=AfmBopmEwpDNN1UKDFiO2sQIhsiab_cnINp0HHYxk40jNW9NbOX434B
- Pete Fowler: https://petefowlershop.com/dept/~drawings/
- MARS-1: https://mars-1.com/filter/SCULPTURE
- Gehenom Zombie (LMAC): No disponible

---

# Datos no disponibles

- Monsterium (Pete Fowler): año y formato.
- MARS-1: año y nombre de una pieza específica.
- Gehenom Zombie: enlace oficial, porque LMAC ya no está activo.