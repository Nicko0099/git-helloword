# Version del curso
Version actual: v1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
 ### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underline
Underline 1
--------------

Underline 2
============

# Formatos de enfasis.
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar *formato italico* pero tambien **bold** y tambien  ~~tachado~~ 
 
 # Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista ordenada.
- Esto es un item de lista ordenada.
- Esto es un item de lista ordenada.

# Links
- <a hrev="http://google.com">Esto es un link HTML</a>
- [Esto es un Link Markdown](http://google.com)
- [Esto es un Link al index](index.html)

# Imagenes
![Logo Github](https://logos-marcas.com/wp-content/uploads/2020/11/GitHub-Logo.png)

# Code Snippets
codigo en JSON
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
```JavaScript
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
| ------ | -------- | --------- |
| Maxi   |   Burgos | 321564    |
| Tomas  |  Tompson | 216546    |

# Citas
Esto es un texto referente a una cira que estara abajo
> Esto es una cita

Esto es otro texto sin relacion a la cita anterior
> Esto es otra cita

# Linias Divisoras
Esto es un texto que sera dividido por giones medios.

---

Esto es otro texto dividido por astetiscos.

***

Esto es otro texto dividido por guines bajos

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro Tercer parrafo.
- Lista
