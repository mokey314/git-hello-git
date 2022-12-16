# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H2
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
----
Underline 2
====

# Formatos de enfasis
- letra *italica* de la primer forma.
- letra _italica_ de la segunda forma.

- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.

- formato ~~tachado~~, formato normal.

# Listas 
1. Esto es un  item de lista ordenada.<ol>
2. Esto es un  item de lista ordenada.
3. Esto es un  item de lista ordenada.
- Esto es un  item de lista desordenada.</ol>

# links
- <a href="http://google.com" >Esto es un link html</a>
- [Esto es otro link en MD](http://google.com)
- [Esto es un link al index](index.html)

# Imagenes

![Logo Github](https://www.shareicon.net/download/2017/05/24/886283_media.ico)

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
Codigo en JAVA SCRIPT
```javascript
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




