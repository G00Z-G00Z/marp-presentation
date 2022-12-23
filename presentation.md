---
title: Presentacion Markdown
description: Una presentacion sin usar pptx
paginate: true
marp: true
theme: uncover
class: invert
style: |
    .colums {
            display: grid;
            grid-template-columns: repeat(2, minmax(0,1fr));
            gap: 1rem;
        }
---

# <!-- fit --> Intro to marp :rocket:
By: Eduardo Gomez

---

## Code block :robot:

```python
def add(a : int, b : int):
    return a + b
```

<!-- Debo de recordar que esto es una presentacion -->

---

## Math :book:

The derivative form is the following: ${dy \over dx}$

$$
L = \lim_{h\rightarrow0}{f(a+h) - f(a) \over h}
$$


--- 

# <!-- fit -->Powerpoint sucks :man_shrugging:

![bg left:33% w:10cm][powerpoint]

- Slow gui :turtle:
- Microsoft :window:
- Lame :see_no_evil:

--- 

# Marp rules :fire:

![bg right:33% w:10cm][marp]
- Text based :sparkles:
- Blazingly fast ⚡
- Exports to pdf, html and pptx :pencil:

---

# <!-- fit --> Change to Marp Now !!


[powerpoint]:https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Microsoft_Office_PowerPoint_%282019%E2%80%93present%29.svg/1200px-Microsoft_Office_PowerPoint_%282019%E2%80%93present%29.svg.png
[powerpoint]:https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Microsoft_Office_PowerPoint_%282019%E2%80%93present%29.svg/1200px-Microsoft_Office_PowerPoint_%282019%E2%80%93present%29.svg.png
[marp]:https://avatars.githubusercontent.com/u/20685754?s=280&v=4
