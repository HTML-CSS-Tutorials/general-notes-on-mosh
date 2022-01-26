# general-notes-on-mosh
#### Course from codewithmosh.com
#### Notes on all three parts

#### Part 1
- (For HTML)[https://validator.w3.org/]\
- (For CSS)[https://jigsaw.w3.org/css-validator/]
- Get free photos from (unsplash.com)[https://unsplash.com/]
- Get free photos, videos from (pexels.com)[https://pexels.com/]
- Check (caniuse.com)[https://caniuse.com/#home] to see how different browsers support html elements and css features.
- (Normalize.css)[https://necolas.github.io/normalize.css/] provides basic default styles for some HTML elements, so they look exactly the same way, accross different browsers.
- type `meta:desc` in `index.html` to get:\
  ` <meta name="description" content="">`\
  In the `content` we type what we want to appear when search engings find our page.
- We don't use `<em>` or `<storng>` `<h1,2,3...>` to display different content, but when we want search engings to use that content.
- Relational selectors i.e `CSS Combinators` help us write cleaner markup because we don't have to write ids and classes... But they are fragile... (check w3scholls)[https://www.w3schools.com/css/css_combinators.asp]
- `Pseudo class` selectors are also fragile...\
- The most common pseudo-elements are: `first-letter, first-line, selection, before and after`.
- We use `:` for pseudo-classes, and `::` for pseudo-elements. Check [Pseudo-classes and Pseudo Elements](https://www.w3schools.com/css/css_pseudo_classes.asp)
- Selectors specificity determines the weight of a selector. When multiple selectors target the same element, the browser applies the selector with the higher specificity (weight). If two selectors have the same specificity, the one that comes last is the winner.
- ID selectors are the most specific selectors because we cannot have multiple elements with the same ID. Class and attribute selectors are less specific because we can have many elements with the same class and/or attributes. Element selectors are the least specific selectors.
- Avoid using `!important` it makes CSS messy and creates a lot of issues. Instead use a selector with more specificity, by combining selectors...
- Inheritance: **Some** CSS values are inherited from their parents.
- Check (cssgradient.io)(https://cssgradient.io/)
- set `box-sizing: border-box` in the universal selector `*` to select all elements. Note: Do not use `*` often, because it can have performance implications. 

#### Part 2

```js
* *::before, *::after {
box-sizing: border-box;
}
```
- Set the bellow and use `rem` for giving size.
```js
html {
// 62.5% of 16px = 10px
font-size: 62.5%
}
```
- Use `Emmet Abbreviations` like: `div.boxes>.box*3` 



