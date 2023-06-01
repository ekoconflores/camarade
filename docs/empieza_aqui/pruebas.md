---
comments: true
---

## Prueba

Esto está escrito con un pull request!

## Hola

??? note

    Holaaa, esto es un admonition

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vitae nisl euismod, aliquam nisl quis, ultricies nisl. Nulla facilisi. Sed euismod, nisl quis aliquam ultricies, nisl nisl aliquam nisl, quis aliquam nisl nisl quis. Nulla facilisi. Sed euismod, nisl quis aliquam ultricies, nisl nisl aliquam nisl, quis aliquam nisl nisl quis. Nulla facilisi. Sed euismod, nisl quis aliquam ultricies, nisl nisl aliquam nisl, quis aliquam nisl nisl quis. Nulla facilisi. Sed euismod, nisl quis aliquam ultricies, nisl nisl aliquam nisl, quis aliquam nisl nisl quis.

```python linenums="1" hl_lines="2 3"
import numpy as np
x = 5 # (1)!
a = np.ones(10) * x
print(x)
```

1. Heyyy, esto es una anotación

=== "Tab 1"
    Markdown **content**.

    Multiple paragraphs.

=== "Tab 2"
    More Markdown **content**.

    - list item a
    - list item b

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

++ctrl+alt+del++

$$
\int_0^{10} x^2 + 1
$$

Esto es $x_2$ y vale $5$. :duck:

- [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
- [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Praesent sed risus massa
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
