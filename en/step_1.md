- If you want to join two strings together in Python, then it's often simplest to use **concatenation**.

	```python
	sentence = 'The quick brown fox' + ' jumped over the lazy dog'
	print(sentence)
	```

- This would give you the whole string.

	```python
	'The quick brown fox jumped over the lazy dog'
	```

- Sometimes though, you want to insert things into the middle of a string, and then the `.format()` string method is easier to use.

- With `.format()` you can use numbers inside curly brackets as placeholders. Like this for example:

	```python
	sentence = 'The {0} {1} fox jumped over the {2} dog'
	```

- By giving `.format()` a tuple of values, they will be inserted into the string.

	```python
	sentence.format('quick', 'brown', 'lazy)
	```

- This gives the original sentence, but you can easily change it.

	```python
	sentence.format('slow', 'green', 'naughty')
	```

- You can also pass in other objects, like variable.

	```python
	foo = 'tired'
	bar = 'purple'
	baz = 'hairy'
	sentence.format(foo, bar, baz)
	```
