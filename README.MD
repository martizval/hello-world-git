# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar *formato italica*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://image.flaticon.com/icons/png/512/25/25231.png)

# Code Snippets
Codigo en JSON
```JSON
[
  {
      "title":"apples",
      "count": [12000,20000],
      "description": {"text": "...","sensitive":false}
  },
  {
      "title":"oranges",
      "count":[17500,null],
      "description": {"text":"...","sensitive":false}
  }
]
```
Codigo en Javascript
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
| -------| -------- | --------- |
| Martín | Izaga | 45751337 |
| Emma | Valderrama | 32836625 |

# Citas
esto es un texto referente que pondrermos debajo :
> Esto es una cita.

Esto es otro texto que no se relaciona.
> Esto es otra cita

# Lineas Divisorias
Esto es un texto que sera dividido por guiones medios

---
este es otro texto dividido por asteriscos

***

este es otro texto dividido por guiones bajos

___

# Saltos de Línea
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.