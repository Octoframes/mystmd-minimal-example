---
title: Euler's identity
subject: Math
subtitle: Its math and beauty.
short_title: Euler Identity
authors:
  - name: John Doe
    affiliations:
      - University of Basel
    email: name@surname.com
license: CC-BY-4.0
keywords: myst, markdown, open-science
---
+++ {"part": "abstract"}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Massa tincidunt dui ut ornare lectus sit amet est placerat.
+++
# Intro



Many **phenomena** are described by Euler's identity  [](#euler).

It's used in the wave equation[^myref].

[^myref]: Very useful!

More in [](#my-fig), [](#my-program) and [](#example-table).

Also see  [Wikipedia](https://en.wikipedia.org/wiki/Euler%27s_identity).

And a paper here [](doi:10.4230/DAGMAN.1.1.41).

# Example 

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.


$$e^{ix}=\cos(x)+i\sin(x) $$  (euler)




:::{figure} wave_cc0.jpg
:name: my-fig
:alt: A drop of water.

A  water wave
:::


```{code-block} python
:name: my-program
:caption: Calculation with numpy.

import numpy as np

c = a + b*1j
print(np.real(c))
print(np.imag(c))
```

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.




:::{list-table} Translate from radian to degree
:header-rows: 1
:name: example-table

* - Rad
  - Deg
* - 3.14
  - 180
* - 6.28
  - 360
:::



:::{note}
:class: dropdown
Lorem ipsum dolor sit amet 
:::

