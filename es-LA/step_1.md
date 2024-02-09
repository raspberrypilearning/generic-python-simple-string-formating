- Si quieres unir dos cadenas en Python, a menudo es más sencillo usar **concatenación**. Por ejemplo, puedes hacer lo siguiente:

    ```python
    oracion = 'El rápido zorro marrón' + ' saltó sobre el perro perezoso'
    print(oracion)
    ```

- Esto convertirá las dos cadenas en una y la devolverá.

    ```python
    "El rápido zorro marrón saltó sobre el perro perezoso"
    ```

- A veces, es posible que desees insertar cosas entre dos cadenas, en cuyo caso es más fácil usar el método de cadena `.format()`. Puedes usar `.format()` con números dentro de llaves como marcadores de posición. Así, por ejemplo:

    ```python
    oracion = 'El {0} {1} zorro saltó sobre el {2} perro'
    ```

- Si le das a `.format()` una tupla de valores, los insertará en la cadena. Por ejemplo, lo siguiente devolverá la frase original...

    ```python
    oracion.format('rápido', 'marrón', 'perezoso')
    ```

- ... pero puede cambiarlo fácilmente a otra cosa, por ejemplo así:

    ```python
    oracion.format('lento', 'verde', 'travieso')
    ```

- También puedes pasar otros objetos, como variables.

    ```python
    foo = 'cansado'
    bar = 'morado'
    baz = 'peludo'
    oracion.format(foo, bar, baz)
    ```
