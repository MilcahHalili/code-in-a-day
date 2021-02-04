# Code in a Day

## Tools
- IDE (Integrated Development Environment): [CodeSandbox.io](https://codesandbox.io/)
- Browser: Google Chrome or Firefox
- Search Engine: Google
- Visualization Tool: [Webflow](https://webflow.com/)

## HTML
HTML stands for Hypertext Markup Language.

Here's the anatomy of HTML tags:

Opening tag:
`<p>`

Closing tag:
`</p>`

Self closing tag:
`<img />`

Tag with an attribute:
`<img src="img_file_path.jpg">`

### Semantic Elements
Semantic elements are more readable than non-semantic HTML. They provide great accessibility for screen readers. Semantic elements refer to the purpose or role that the element has.

These are common semantic elements:

```
<article>
<aside>
<footer>
<header>
<main>
<nav>
<section>
<summary>
```

## Accessibility

## CSS
CSS stands for Cascading Style Sheets.

### Inline Styling
Devs can implement inline styling by using the `style` attribute inside HTML elements.

```
<p style="font-weight: 600;">
  This is a styled paragraph tag.
</p>
```

### Internal Styling
Devs can implement interal styling by using a `<style>` element in the `<head>` section.

```
<head>
  <style>
    p {
      font-weight: 600;
    }
  </style>
</head>
```

### External Styling
Devs can implement external styling by using a `<link>` element to link to an external CSS file.

```
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```