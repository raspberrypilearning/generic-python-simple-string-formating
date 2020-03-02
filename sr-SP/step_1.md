- If you want to join two strings together in Python, then it's often simplest to use **concatenation**. For example, you can do the following:

    ```python
    sentence = 'The quick brown fox' + ' jumped over the lazy dog'
    print(sentence)
    ```

- This will turn the two strings into one and return it.

    ```python
    'The quick brown fox jumped over the lazy dog'
    ```

- Sometimes you might want to insert things into the middle between two strings, in which case the `.format()` string method is easier. You can use `.format()` with numbers inside curly brackets as placeholders. Like this for example:

    ```python
    sentence = 'The {0} {1} fox jumped over the {2} dog'
    ```

- If you give `.format()` a tuple of values, it will insert them into the string. For example, the following will return the original sentence...

    ```python
    sentence.format('quick', 'brown', 'lazy)
    ```

- ...but you can easily change it to something else, for example like this:

    ```python
    sentence.format('slow', 'green', 'naughty')
    ```

- You can also pass in other objects, like variables.

    ```python
    foo = 'tired'
    bar = 'purple'
    baz = 'hairy'
    sentence.format(foo, bar, baz)
    ```
