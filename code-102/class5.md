# Class 5 Notes - Design Web Pages with CSS

## [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

A styling language
- Used to stylize HTML
- Modify particular elements or groups
    - Ex. color, text, text size, images, etc.
- The community also ensures CSS is supported over multiple web browsers

## [How to add CSS](https://www.w3schools.com/css/css_howto.asp)
- External CSS - changes entire sheet by including a reference sheet
- Internal CSS - change one single HTML page to a unique style
- Inline CSS - apply a unique style to a single element

Cascading order if multiple styles are identified

1. Inline style (inside HTML element)
2. External and internal style sheets (in the head section)
3. Browser default

## Additional References
- [CSS Cheat Sheet](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [CSS Tools: Reset CSS](https://meyerweb.com/eric/tools/css/reset/)

## Answer

- What is the purpose of CSS? - Styling language
- What are the three ways to insert CSS into your project?
1. External
2. Internal
3. Inline
- Write an example of a CSS rule that would give all paragraph elements red text.

p {
    color: red;
}

## Class notes

Float takes an element outside of his default state
Display property modifies a default display state

Selector examples
- Elements ex. p
- Class ex. .new
- ID ex. #sitemap
- Universal ex. *