# Documentation for ANNarchy 4.8

The documentation for ANNarchy < 5.0 is at <https://annarchy.github.io/ANNarchy4>. 

Generating the documentation requires **Quarto** (<https://quarto.org>) and `quartodoc` (<https://github.com/machow/quartodoc>, `pip install quartodoc`) for the API. 

First build the API:

```bash
quartodoc build
```

Preview the doc:

```bash
quarto preview
```

Push it to github:

```bash
quarto publish gh-pages
```
