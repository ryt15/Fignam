Prefices
========

::: {.Section1}
GUI Elements {#GUINamingConvention-GUIElements}
============

Below table specifies which prefixes to use when naming a GUI component.
It\'s very important to base the prefix from **what it [looks
like]{.underline} to the user**, not what actual code was used to
implement it! E.g. a combo box can be implemented either as a `<select>`
or a `<datalist>` element, but it still looks like a combo box so the
prefix `cox` shall be used!

::: {.table-wrap}
+-----------+-----------+-----------+-----------+-----------+-----------+
| **Compone | **HTML^1) | **Prefix* | **Example | **Comment | **Links** |
| nt        | ^**       | *         | **        | s**       |           |
| Type**    |           |           |           |           |           |
+===========+===========+===========+===========+===========+===========+
| Audio     | `<audio>` | `aud`     |           |           | <https:// |
| player    |           |           |           |           | www.w3sch |
|           |           |           |           |           | ools.com/ |
|           |           |           |           |           | tags/tag_ |
|           |           |           |           |           | audio.asp |
|           |           |           |           |           | >         |
+-----------+-----------+-----------+-----------+-----------+-----------+
| Button    | `<button> | `btn`     |           |           | <https:// |
|           | `^3)^     |           |           |           | www.w3sch |
|           |           |           |           |           | ools.com/ |
|           |           |           |           |           | tags/tag_ |
|           |           |           |           |           | button.as |
|           |           |           |           |           | p>        |
+-----------+-----------+-----------+-----------+-----------+-----------+
| Canvas    | `<canvas> | `can`     |           |           | <https:// |
|           | `         |           |           |           | www.w3sch |
|           |           |           |           |           | ools.com/ |
|           |           |           |           |           | tags/tag_ |
|           |           |           |           |           | canvas.as |
|           |           |           |           |           | p>        |
|           |           |           |           |           |           |
|           |           |           |           |           | <https:// |
|           |           |           |           |           | www.w3sch |
|           |           |           |           |           | ools.com/ |
|           |           |           |           |           | tags/ref_ |
|           |           |           |           |           | canvas.as |
|           |           |           |           |           | p>        |
+-----------+-----------+-----------+-----------+-----------+-----------+
| Card      | `<div>`   | `crd`     |           | A         |           |
|           |           |           |           | presentat |           |
|           |           |           |           | ion       |           |
|           |           |           |           | containin |           |
|           |           |           |           | g         |           |
|           |           |           |           | a mixed   |           |
|           |           |           |           | set of    |           |
|           |           |           |           | data,     |           |
|           |           |           |           | usually   |           |
|           |           |           |           | an image  |           |
|           |           |           |           | on top    |           |
|           |           |           |           | with data |           |
|           |           |           |           | underneat |           |
|           |           |           |           | h.        |           |
|           |           |           |           | See also  |           |
|           |           |           |           | `swi`.    |           |
+-----------+-----------+-----------+-----------+-----------+-----------+
| Checkbox  | `<input t | `cbx`     |           |           |           |
|           | ype="chec |           |           |           |           |
|           | kbox">`   |           |           |           |           |
+-----------+-----------+-----------+-----------+-----------+-----------+
