
<img width="574" alt="Screen Shot 2021-07-11 at 9 10 17 PM" src="https://user-images.githubusercontent.com/51871665/125229855-76b7fc00-e28c-11eb-9d36-2b2b2eb74507.png">
# Amazing Mountain - landing page

[![Netlify Status](https://api.netlify.com/api/v1/badges/8dd3688a-8f84-4c53-8702-a2cd7fcbe574/deploy-status)](https://mountainrecreation.netlify.app)

👆🏽 click to check the live page

This is a 1 page landing page.

## Demo
<img width="300px" alt="Screen Shot 2021-07-11 at 9 09 57 PM 1" src="https://user-images.githubusercontent.com/51871665/125229848-728bde80-e28c-11eb-9ade-655f81ab3452.png">
<img width="300px" alt="Screen Shot 2021-07-11 at 9 10 17 PM" src="https://user-images.githubusercontent.com/51871665/125229855-76b7fc00-e28c-11eb-9d36-2b2b2eb74507.png">

## How it's built

**Tech used**: HTML, CSS

## Lesson learnt

### Before start writing CSS

* Make elements border-box

```css
    *,
    *::before,
    *::after {
        box-sizing: border-box;
    }
```
* Set general font family, font size, color, line-height, `margin: 0;` under `body`
1.125rem = 18 px
Instead of doing 62.5% under `html` tag, we want to accommodate others' change in their browser

### single-colon vs dowble-colon in CSS

* single-colon selectors are pseudo-selectors: used to selecting things that already exist, such as `:nth-child(2)`

* double-colon selectors are pseudo-elements: used to selecting things that have no HTML element for, such as `::first-letter`

### Custom CSS

Define custom CSS with name and value under `:root`: 

```css
:root {
    --name:value;
}
```

The two dash lines are necessary before the name.


### Other tips
* Opacity is applied not just the element but also its contents.

* line height

It's better to use the unitless value becasue in this way the line box height will be the multiplication of the number and the element font-size. In the block-level elements, it specifies the minimum height of line boxes. 

* Use outline instead of border to style button to make the button the same size. Outline can be shifted and it won't affect other elements.

* Length unit: (ch) character count

* Negative margin is doable.

* Categorize the alignment of elements

Design:
https://www.figma.com/file/GwRmx1FJ31evTNq6hpCpCs/Amazing-Mountain?node-id=2%3A9
