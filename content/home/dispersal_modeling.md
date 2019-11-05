+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 29  # Order that this section will appear.

title = "Seed dispersal modeling"
subtitle = "Following high-severity wildfire"

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
{{< figure library="true" src="dispersal.JPG" title="Hypothetical conifer seed rain density (shading) for a given spatial arrangement of surviving reproductive trees following wildfire (points)." lightbox="true" >}}

I am building a non-linear spatially-explicit Bayesian model for predicting seed rain (and, subsequently, regeneration) of conifers following high-severity wildfire given a known spatial arrangement of surviving reproductive trees. Data on surviving tree spatial arrangement will be [derived from drone imagery](#drones_ai). To otbain dispersal data to train the model, I am coordinating intensive field surveys that involve documenting the density of regenerating conifers in a dense grid of plots across several recent severely burned areas.
