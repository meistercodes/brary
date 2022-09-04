# Position property

The position property specifies the type of positioning method used for an element.

The five different position values are as followed:

- static
- relative
- fixed
- absolute
- sticky

## static

HTML uses the static posiiton property by default.

Positioned according to the normal flow of the page.

Example:

```css
div {
  position: static;
}
```

## relative

Element is positioned relative to its normal position.

Setting top, right, bottom, and/or left properties will cause it to be adjusted away from its normal position. Other content will not be adjusted.

Example:

```css
div {
  position: relative;
  top: 30px;
}
```

## fixed

Element is positioned relative to the viewport, meaning it always stays in the same place even if the page is scrolled. The top, right, bottom, left properties are used to position the element.

Example:

```css
div {
  position: fixed;
  bottom: 0;
  right: 0;
}
/* Positions an element at the bottom right corner of the page. */
```

## absolute

Element is positioned relative to nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

If an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

**Note:** Absolute positioned elements are removed from the normal flow, and can overlap elements.

Example:

```css
/* Parent Element */
div.relative {
  position: relative;
  width: 400px;
  height: 200px;
  border: 2px solid red;
}
/* Child Element */
div.absolute {
  position: absolute;
  top: 100px;
  right: 0;
  width: 200px;
  height: 100px;
  border: 2px solid red;
}
```

## sticky

Positioned based on a users scroll position.

Example:

```css
/* Positions an element at the top (top: 0) when its scroll position is reached */
div.sticky {
  position: sticky;
  top: 0;
  background-color: green;
  border: 2px solid red;
}
```
