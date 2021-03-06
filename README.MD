# Versión del curso
Versión actual: v1.2.2
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
------------

Underline 2
==========

# Formatos de enfasis
- Formato *italica* de la primera forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primera forma
- Formato __bold o strong__ de la segunda forma
- Formato ~~tachado~~, formato normal.
- Aqui podemos usar *formato italico*, pero también **bold** y ~tachado~

# Listas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://www.google.com">Esto es un link en HTML </a>
- [Esto es un link en markdown](http://www.google.com)
- [Esto es un index](index.html)

# Imagenes
![Logo GitHub](https://1000logos.net/wp-content/uploads/2018/11/GitHub-logo.png)

# Code Snippets
Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Codigo en JavaScript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
|--|--|--|
| Lorena | Galeano | 123456789 |
| Tomas | Tompson | 1581521 |
| Maxi | Burgos | 489451 |

# Citas
Esto es un texto referente a una cita que colocaremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Lineas divisoras
Esto es un texto dividido por guines medios

---
Esto es un texto dividido por asteriscos
***

Esto es un texto dividido por guines bajos
___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista