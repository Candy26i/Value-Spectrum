Usage
=====

Plain_
------------
Make sure you have finished everything in the Setting up section






Creating recipes
----------------

To retrieve a list of random ingredients, you can use the
`lumache.get_random_ingredients()` function:

::: lumache.get_random_ingredients
    options:
      show_root_heading: true

<br>

The `kind` parameter should be either `"meat"`, `"fish"`, or `"veggies"`.
Otherwise, [`get_random_ingredients`][lumache.get_random_ingredients] will raise an exception [`lumache.InvalidKindError`](/api#lumache.InvalidKindError).

For example:

```python
>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']
```
