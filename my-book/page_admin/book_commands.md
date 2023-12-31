Resource:

Commands (from book directory)
* build the page: ```ghp-import -n -p -f my-book/_build/html```


### Toggle
How to make a "toggle-able" bar to make them try it before looking at the answer. Link: https://jupyterbook.org/en/stable/interactive/hiding.html

```{toggle}
Some hidden toggle content!

![](../images/cool.jpg)
```

Alternatively:

```{admonition} Click the button to reveal!
:class: dropdown
Some hidden toggle content!

![](../images/cool.jpg)
```

### Notes

Here is a "note" directive:

```{note}
Here is a note
```