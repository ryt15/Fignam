# Colors

## Color naming rules



## General color rules and recommendations

| Rule                                   | Motivation                                     |
| :------------------------------------- | :--------------------------------------------- |
| Don't use too many colors.             | It becomes very difficult to administer them.  |
| Name all colors immediately.           | Giving each new color a name already in the design phase makes it easier to avoid creating unnecessary colors, and to keep track of them. Naming colors initially also makes it easy to consider the purpose of every color. |
| Never name a color by its color.       | The names you give your colors should not contain any color names themselves. Suppose you name the background color of your page `lightYellowBG` and assign the value `#FFDDAB` to it. This works well only until someone adds dark mode, changing the color value to `#030303`, so now your `lightYellowBG` color represents a very dark gray tone which is confusing! |
| Use functional color names.            | Let the color name indicate how the color will be used. F.x. text colors for warning messages could be named `colWarnFG`. |
| Prefix all color named with **col**.   | This makes it easy to identify color names. Example: `colLoginBG`. |
| Postfix foreground colors with **FG**. | This minimizes confusion and makes it possible to automatically check contrast. Example: `colLoginFG`. |
| Postfix background colors with **BG**. | This minimizes confusion and makes it possible to automatically check contrast. Example: `colLoginBG`. |
| Only vary the postfix part of colors that should contrast each other. | If you know that one color is always supposed to be used above another color, just vary the end of the name, to maintain readability and allow contrast to be verified programmatically. Typical example is the above **GB** and **FG** variants. |
| Prefix color style names with **sty**. | This makes it easy to quickly change color styles in a large project. Example: `styPageHeader01`. |
| Don't reuse colors with different functions. | Even if color values are the same, but are used for different purposes, a color should be defined for each purpose. |
| Don't use short-lived names. | Color names shall be considered useful throughout the entire life cycle of the app. |
| Make groups obvious. | Suppose you draw a tree with leaves having different nuances of green, you should use the same name for each color, only varying the nuance part, to make it clear they are closely related. Example: `colLeaf01`, `colLeaf02` and so on. |

## Bad examples

| Color name(s) | Complaint |
| :------------ | :-------- |
| SalesText     | Name does not start with prefix **col**. |
| colRedTextLowpriceFG | The color name **Red** is part of the name. |
| colExtraLowPriceDecemberBG | The names is too long. It's unclear if the _December_ part is valid every year or just this year. If the latter, temporary names are not recommended at all, but should at least have some indicator making it clear that it is a temporary name. |
| colPagHrdTxt and colPageHeaderText | Don't use various syntax in the same system. Decide, and document, how to abbreviate names and stick to your rules consequently. In general, the shorter variants are better as they keep names short. |
| col_logo_BG   | Don't use _ as separator. Use camelCase since it makes the names shorter. |
