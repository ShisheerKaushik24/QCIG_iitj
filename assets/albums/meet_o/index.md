---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: First Group Meet
subtitle:

tags:
  - Gallery

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'
  background:
    color: '#292725'
    # Text color (true=light, false=dark, or remove for the dynamic theme color). 
    text_color_light: true
  spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
    padding: ["0", "0", "0", "0"]

gallery_item:
- album: meet_o
  image: "meet_0.jpg"
  caption: "Write your image caption here"

---
{{< gallery album="phone_photography" >}}

