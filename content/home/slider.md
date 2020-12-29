---
widget: slider
headless: true  # This file represents a page section.

weight: 25

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 600px


item:
  - overlay_color: '#666'  # An HTML color value.
    overlay_img: face.jpg  # Image path relative to your `static/media/` folder
    overlay_filter: 0  # Darken the image. Value in range 0-1.
  - title: Left
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    overlay_img: ''
    overlay_filter: 0.5
  - title: Right
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
    
---
