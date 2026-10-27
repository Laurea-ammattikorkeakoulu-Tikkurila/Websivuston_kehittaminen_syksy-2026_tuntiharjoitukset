# WS02: CSS Basics – Workshop Exercise

In this workshop exercise, we explore the basics of CSS and learn how a webpage becomes clearer and more visually appealing when styling is added on top of a plain HTML structure.

## Exercise Files

The folder contains two HTML files:

- `index1.html` = the basic version of the page without CSS styling
- `index2.html` = the same page styled using CSS

In addition, there is a separate stylesheet:

- `styles/style.css` = external CSS rules used by `index2.html`

Compare `index1.html` and `index2.html`. You will see how the same HTML elements can look completely different when CSS styling is applied.

## What is CSS?

**CSS (Cascading Style Sheets)** is a style language used to define the appearance of a webpage. HTML describes what is on the page (such as headings, paragraphs, images, and links), while CSS describes how those elements should look (such as colors, fonts, spacing, and layout).

In short:

- HTML = content and structure
- CSS = appearance and styling

## How is CSS Used?

CSS is written as rules that select specific elements and apply style properties to them.

Example:

```css
h1 {
    color: #1f4e79;
    font-size: 2rem;
}
```

The rule above styles all `h1` headings with a blue color and a larger font size.

## Where Can CSS Be Defined?

1. In an external stylesheet (recommended), for example `styles/style.css`
2. Inside a `<style>` section within the HTML document's `<head>`
3. Directly within an element using the `style` attribute

An external stylesheet is the preferred approach because it keeps the code clean and easier to maintain.

## What Will You Learn in This Exercise?

The goal is to practice common CSS properties such as:

- Text colors and fonts
- Background colors
- Margins and padding
- Borders
- Element widths and positioning

By adding CSS rules to the same HTML elements, the appearance of the page quickly becomes more organized, attractive, and professional.

## Summary

CSS is the foundation of web page styling. It allows developers to separate content (HTML) from presentation (CSS), making websites easier to build, update, and maintain.

## Note

The content of this README file was created with the assistance of