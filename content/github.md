+++

outputs = ["Reveal"]
title = "Interesting GitHub Projects"
layout = "list"

[params.revealOptions]
dependencies = [
  ["css", "/css/custom.css"]
]

[reveal_hugo.templates.convex]
transition = "convex"

+++

{{< slide id="hello" transition="zoom" transition-speed="fast" notes="Go slow!" >}}

## Welcome to My Presentation
- This is a slide in a Hugo Reveal.js presentation.
- Hugo makes site generation fast and modular.

<img src="/Untitled.png" alt="My Logo" style="border: none; box-shadow: none;">

---

{{< slide id="hello" transition="zoom" transition-speed="fast" >}}

{{% section %}}

## Vertical Slides Below

### Vertical Slide 1
- Example of a vertical slide.

---

{{< slide id="hello" transition="zoom" transition-speed="fast" >}}

### Vertical Slide 2
- Here's another vertical slide.
- You can add more slides as needed!

{{% /section %}}

---

{{< slide id="hello" transition="zoom" transition-speed="fast" >}}

## Using Hugo Templates

### Hugo Templates
- Hugo allows for reusable templates:
  - Shortcodes for consistent layout.
  - Partials for HTML fragments.
- Examples on the next slides.

---

{{< slide id="hello" transition="zoom" transition-speed="fast" >}}

## Template Example: Shortcode

### Shortcode Example

{{</* my-shortcode "Hello from a shortcode!" */>}}

---

{{< slide id="hello" transition="zoom" transition-speed="fast" >}}

## Template Example: Partials

### Partial Example

{{ partial "header.html" . }}

---

{{< slide id="hello" transition="zoom" transition-speed="fast" >}}

## Embedded Website Example

### Live Website

<iframe src="https://agilebuckle.com" style="width: 100%; height: 500px; border: none;"></iframe>

This embeds a live website directly into the presentation.

---

{{< slide id="hello" transition="zoom" transition-speed="fast" >}}

## Closing Slide
- Thank you for attending!
- Questions? Feel free to ask.

---
