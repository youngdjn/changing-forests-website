+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 28  # Order that this section will appear.

title = "Drones, AI, and big data"
subtitle = "For mapping forest trees"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "#e6e6e6"

  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"

  # Background image.
  # image = "empo1.JPG"  # Name of image in `static/img/`.
  # image_darken = 0.3  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["90px", "0", "50px", "0"]

[advanced]
 # Custom CSS.
 css_style = ""

 # CSS class.
 css_class = ""
+++
<script src="https://static.kuula.io/embed.js" data-kuula="https://kuula.co/share/7qD7n?fs=1&vr=0&sd=1&thumbs=1&alpha=0.60&hideinst=1&chromeless=0&logo=0" data-width="100%" data-height="259px"></script>

I am developing an automated workflow to map forest trees over large (> 100 ha) areas using drone imagery. The workflow incorporates:

* Construction of 3D stand structure models from drone imagery using photogrammetry
* Segmentation of individual trees from structure models
* Identification of trees to species using convolutional neural networks for computer vision

[More details ... ](drones-ai/)
