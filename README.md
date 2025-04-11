# Learn Accessibility - Quiz

## Purpose

Create a form based quiz that addresses accessibility concerns.

## What I learnt

When addressing accessibility concerns (notwithstanding understanding the target audiences disability challenges), start with **_good structure_** using appropriate **_semantic html tags_** to organise content.

Typeface and the contrast between background and foreground is also important when designing for accessibility. Use **_web safe_** fonts (sans-serif works well for accessibility), don't use bright or garish colours and make sure the contrast between background and font colour is at least **_4.5 / 1_**

Remember basic stuff such as **_alt_** tags for images, **_aria_** labels, **_role attributes_** (see below)

### Search Engine Optimisation

Use `<meta>` tags to help improve SEO - index.html[6]

### Semantic HTML

Navigation is a core element of accessibility. In order to make it easier for users with accessibility needs to navigate web pages must have **_structure_**. We achieve this by using **_semantic html_**. These are **_html tags_** that describe sections or content of a web page.

### role attribute

This indicates the role of an element to assistive technologies. This and other assistive technologies are documented in by the [Web Accessibility Initiative](https://www.w3.org/WAI/).

See index.html [35]

### aria-labelledby

What is the difference between aria-label and aria-labelledby?

### Type face

Pick fonts that are more accessible (easier to read)

Contrast between text and background should be at least **_4.5:1_**

## Screen Readers

To assist visually impaired users additional text can be added to an element but hidden which will then be picked up by a screen reader. There is a **_common pattern_** to achieve this.

Firstly see index.htm. [58] where text that will be used by the screen reader is wrapped within `<span></span>`. Then we style these with CSS [52-60]

### Scaling logo image

The provided logo image is too large. User the `max()` function to reduce scale. I need to research this more!!!

## Reflection

I kinda got lost with this exercise. Initial steps were relatively simple although I do need to practice creating and styling forms. However, I struggled to understand the following concepts that need further research:

1. Contrast - particularly contrast ratios
2. `content` property styles.css [63]
3. `scroll-behavior`
4. `@media (prefers-reduced-motion:)`
5. `max()` function

## References

[Semantic HTML W3 Schools](https://www.w3schools.com/html/html5_semantic_elements.asp)

[W3C Making the Web Accessible](https://www.w3.org/WAI/)

[W3C Contrast](https://www.w3.org/TR/WCAG20-TECHS/G18.html)

[CSS-Tricks Understandin Web Accessibility Colour Contrast Guidelines and ratios](https://css-tricks.com/understanding-web-accessibility-color-contrast-guidelines-and-ratios/)
