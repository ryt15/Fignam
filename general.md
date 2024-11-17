# General naming rules

## Source code related rules

When the design is handed over to developers, its important they can use the same names in their source code
as were used by the designer. This heavily restricts confusion, makes the handover smoother and allows the
project to be maintained cheaper.

But developers have to deal with some programming language restricts. To avoid them, designers ought to follow
these rules when naming their elements, classes and objects:

- Never use blanks in names!
- Only use the characters a-z, A-Z, \_ and digits.
- Pay attention to casing, never use upper-case where it shall be lower-case and vice versa.
- Never start a name with a digit.

## General rules

- Use the words _previous_, _next_, _last_, _first_ only for orientation in lists, but not when discussing versions.
- Never use the words _new_ and _old_
- Always base names on the American English language.
- Make the names distinct enough so they can be found easily using free text search.
- Keep decent lenght of all names (more on that in other chapters).
- Consider everything as multiple! Add a sequence number to the end of the name, and have the same number of digits.
- Use camelCasing instead of underscore (\_) to make the names as short as possible.
- Abbreviate names as long as it is obvious what they mean, or when they are well documented. E.g. use _txt_ instead of _text_, _hdr_ instead of _header_, _prv_ instead of _previous_.
- Things that are closely related, e.g. variants should have the same base names with only one unigue part.
- When enumerating names, make sure they have the same length by using leading zeroes for the numbers.
- Use prefices to classify elements, f.x. prefix all [color](colors.md) names with _col_, buttons with _btn_ and so on.
- Names of entities not meant for production or handover to developers, such as local comments or designer tools, should start with underscore. Ex: _\_colPalette_.
