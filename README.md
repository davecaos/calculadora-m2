# Calculadora de valor por m²

Calculá el valor del m² cubierto y descubierto de una propiedad (el descubierto vale el 50% del cubierto) y compartí el resultado con un link.

**https://davecaos.github.io/calculadora-m2/**

## Links para compartir

Pegá el link de la propiedad, completá los valores y copiá el "Link para compartir". Quien lo abra ve la calculadora ya cargada y un botón **Ver propiedad**.

```
https://davecaos.github.io/calculadora-m2/?p=A8026701-PH-en-Venta-en-Almagro-Salguero-200-/-Diaz-Velez&v=150000&c=120&d=40
```

| Param | Contenido |
| ----- | --------- |
| `p` | URL de la propiedad: una letra de prefijo (ver `PREFIXES` en `index.html`) + el resto de la URL |
| `z` | Igual que `p`, pero el resto va comprimido con deflate + base64url. Se usa solo cuando sale más corto |
| `v` | Valor de la propiedad |
| `c` | m² cubiertos |
| `d` | m² descubiertos |

Solo se aceptan URLs `http`/`https`. El botón siempre muestra el dominio de destino.

Es un único `index.html` sin dependencias ni build.
