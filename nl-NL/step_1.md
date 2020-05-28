- Als je twee strings wilt samenvoegen in Python, dan is het vaak eenvoudig om **concatenatie (aaneenschakeling)** te gebruiken. Je kunt bijvoorbeeld het volgende doen:

    ```python
    zin = 'De snelle bruine vos' + ' sprong over de luie hond'
print(zin)
    ```

- Hiermee worden de twee strings één en wordt deze teruggegeven.

    ```python
    'De snelle bruine vos sprong over de luie hond'
    ```

- Soms wil je misschien dingen in het midden tussen twee strings invoegen, in welk geval de `.format()` string-methode eenvoudiger is. Je kunt `.format()` met getallen tussen accolades als tijdelijke aanduidingen gebruiken. Zoals dit bijvoorbeeld:

    ```python
    zin = 'De {0} {1} vos sprong over de {2} hond'
    ```

- Als je `.format()` een aantal waarden geeft, worden deze in de tekenreeks ingevoegd. Het volgende geeft bijvoorbeeld de oorspronkelijke zin terug...

    ```python
    zin.format('snel', 'bruin', 'lui)
    ```

- ... maar je kunt het eenvoudig veranderen in iets anders, bijvoorbeeld als dit:

    ```python
    zin.format('langzaam', 'groen', 'ondeugend')
    ```

- Je kunt ook andere objecten doorgeven, zoals variabelen.

    ```python
    aap = 'moe'
noot = 'paars'
mies = 'harig'
zin.format(aap, noot, mies)
    ```
