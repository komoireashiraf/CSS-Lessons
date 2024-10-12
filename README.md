# CSS Operators 

This repository provides a quick guide to fundamental CSS selectors and properties. The code in this project demonstrates how to use basic and advanced CSS selectors, as well as key CSS properties, all in one place.

## Table of Contents

1. [Selectors](#selectors)
    - Universal Selector
    - ID Selector
    - Class Selector
    - Tag Selector
    - Attribute Selectors
    - Pseudo-Class Selectors (e.g., :first-child, :nth-child)
    - Structural Pseudo-Class Selectors
    - Language Selector
    - Empty Selector
    - Parent Selector
2. [Properties](#properties)
    - Background
    - Border
    - Box Shadow
    - Color
    - Display
    - Flexbox
    - Positioning
    - Text & Font Properties
    - Spacing (Margin, Padding)
    - Sizing (Width, Height)
    - Transitions & Transformations
    - Visibility
    - Overflow

## Selectors

CSS selectors allow you to target HTML elements and apply styles to them. This project contains examples of various selectors like:

- *Universal Selector* (* {})
- *ID Selector* (#id {})
- *Class Selector* (.class {})
- *Tag Selector* (tag {})
- *Attribute Selectors* (e.g., [attr="value"], [attr~="value"])
- *Pseudo-Class Selectors* (:first-child, :last-child, :nth-child(n))
- *Structural Selectors* (:only-of-type, :empty)
- *Language Selector* (:lang(en))

Example usage:

```css
/* Universal Selector */
* {
  margin: 0;
  padding: 0;
}

/* Class Selector */
.container {
  max-width: 1200px;
  margin: 0 auto;
}
