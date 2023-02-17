---
title: My new story
subtitle: A tale from the mysts of Jupyter
authors:
  - name: Fernando Pérez
    email: fernando.perez@berkeley.edu
    affiliations:
      - Department of Statistics, UC Berkeley
      - Computing Sciences Research, Lawrence Berkeley National Laboratory
keywords: Jupyter, MyST, Interactive computing.
exports:
  - format: pdf
    template: lapreprint
    venue_footer: arxiv
  - format: docx
---

+++ { "part": "abstract" }

MyST (Markedly Structured Text) is designed to create publication-quality documents
written entirely in Markdown. The markup and publishing build system is fantastic,
MyST seamlessly exports to any PDF template, while collecting metadata to make your
writing process as easy as possible.

+++
# A new Markdown rises from the myst

Let's test a few features of markdown with the 

A little list with checkboxes:

- [ ] Test item
- [ ] Item 2

Testing links: http://google.com

Math works:

$$
x+\alpha
$$

And code: 

```python
def foo(bar):
    return bar

foo("asd")
```
