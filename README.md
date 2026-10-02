# I AM PLASTIC · Designer Art Toys

Curaduría digital del libro *I AM PLASTIC* de Paul Budnitz (2006), que reúne más de 300 obras de art toys creadas por diseñadores de todo el mundo. Esta página presenta una selección de 4 figuras de distintos países, cada una con su tagline, datos del toy y del creador.

---

## Descripción del proyecto

Página web informativa con estilo de sitio digital, construida a partir de información estructurada. El contenido no se escribió directamente en HTML: primero se investigó, se organizó en Markdown y después se transformó a HTML semántico.

**Tema:** art toys de diseñador.
**Fuente principal:** *I AM PLASTIC*, de Paul Budnitz.
**Idioma:** español.

---

## Flujo de trabajo

```text
INFORMACIÓN
↓
MARKDOWN
↓
HTML SEMÁNTICO
↓
CSS
```

1. **Información:** se define qué datos se necesitan de cada art toy.
2. **Markdown:** se estructura y revisa el contenido (`i-am-plastic-estructurado.md`).
3. **HTML:** se convierte el Markdown a HTML semántico usando `base.html`.
4. **CSS:** se aplica el diseño en `style.css`.

La IA se usa como apoyo para procesar y transformar la información. La estructura y las decisiones del proyecto son de quien diseña.

---

## Archivos del proyecto

```text
/
├── index.html                      Página final
├── base.html                       Estructura base (header, main, footer)
├── style.css                       Estilos
├── i-am-plastic-estructurado.md    Fuente única de contenido
└── README.md                       Este archivo
```

> Ajusta los nombres si tu proyecto usa otros, por ejemplo si la página final no se llama `index.html`.

---

## Estructura del contenido

Cada art toy mantiene exactamente los mismos campos:

- nombre
- tagline
- diseñador
- ubicación / nacionalidad
- año
- formato
- descripción del toy
- descripción del creador
- enlace

Si un dato no está disponible, se indica como "No disponible". No se inventa información.

---

## Estructura del HTML

```text
header          Título y presentación
main
├── section     Introducción
├── section     Asia
│   └── article Gloomy Bear
├── section     Europa
│   └── article Monsterium
├── section     Estados Unidos
│   └── article MARS-1
└── section     Singapur
    └── article Gehenom Zombie
footer          Créditos y fuentes
```

Reglas de la conversión:

- `section` para cada grupo temático (región).
- `article` para cada art toy, porque es una unidad de contenido independiente.
- Encabezados según su jerarquía (`h1` título, `h2` regiones, `h3` toys).
- `p` para párrafos, `ul` para listas, `a` para enlaces, `img` para imágenes.
- Sin estilos inline, sin JavaScript y sin CSS fuera de `style.css`.

---

## Contenido: art toys incluidos

| Región | Toy | Diseñador | Ubicación | Año |
|---|---|---|---|---|
| Asia | Gloomy Bear | Mori Chack | Tokio, Japón | 2004 |
| Europa | Monsterium (Island Woodland Volume 3) | Pete Fowler | Reino Unido | No disponible |
| Estados Unidos | MARS-1 · Obras escultóricas en vinilo | Mario Martínez (MARS-1) | San Francisco, California | No disponible |
| Singapur | Gehenom Zombie | Le Messie y Amanda Scully (LMAC) | Singapur | 2005 |

---

## Cómo usar el proyecto

1. Descarga o clona la carpeta del proyecto.
2. Verifica que `index.html` y `style.css` estén en la misma carpeta.
3. Abre `index.html` en cualquier navegador.

No requiere instalación ni dependencias.

---

## Fuentes y enlaces

- Gloomy Bear: https://gloomybearstore.com/
- Pete Fowler: https://petefowlershop.com/dept/~drawings/
- MARS-1: https://mars-1.com/filter/SCULPTURE
- Gehenom Zombie (LMAC): sin enlace oficial, la marca ya no está activa.

---

## Datos pendientes

- Monsterium: año y formato.
- MARS-1: año y nombre de una pieza específica.
- Gehenom Zombie: enlace oficial.

---

## Créditos

- Libro: *I AM PLASTIC*, Paul Budnitz.
- Curaduría y diseño de la página: [tu nombre].
- Los art toys y sus imágenes pertenecen a sus respectivos creadores.