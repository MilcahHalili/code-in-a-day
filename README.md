# Code in a Day

## Tools
- IDE (Integrated Development Environment): [CodeSandbox.io](https://codesandbox.io/)
- Browser: Google Chrome or Firefox
- Search Engine: Google

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

### Don't Reinvent the Wheel
Simultaneous to turning your static files into the web pages we visit every day, it builds something called the accessibility tree - which is conveniently visible in your browser's dev tools, and is a huge part of why it's so important to use semantic HTML whenever you possibly can. There's a lot of information tied up in those semantic tags, which does a lot of the work of making your almost purely visual site at all useable through screen readers and other assistive technology.

If there's an element that captures the meaning of what you're trying to accomplish, use it. If the default styling for that element doesn't fit your aesthetics, push up your sleeves and dig into the CSS. Then everyone visiting your page can have an optimal experience.

### WAI-ARIA
There are, unfortunately, plenty of gaps in the semantic elements available to us. If you want to include something like a carousel or a tab list, it'll take some extra work to make sure assistive tech can communicate what's happening. And that's where ARIA comes in. 

[Web Accessibility Initiative - Accessible Rich Internet Applications](https://www.w3.org/TR/wai-aria-1.1/) is a very large set of tools that we can use to inject that missing semantic information into the accessibility tree before it gets handed off to assistive tech. 

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