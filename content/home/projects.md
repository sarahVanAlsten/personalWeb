+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Topic Areas"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  #filling in buttons currently as statistical topics (eg correlation, regression)
  #currently listing in alphabetical order
  
  [[content.filter_button]]
    name = "All"
    tag = "*"
    
  [[content.filter_button]]
    name = "ANOVA"
    tag = "ANOVA"
    
  [[content.filter_button]]
    name = "Central Limit Theorom"
    tag = "Central Limit Theorom"
    
  [[content.filter_button]]
    name = "Chi-Square"
    tag = "Chi-Square"   
    
  [[content.filter_button]]
    name = "Correlation"
    tag = "Correlation"
    
  [[content.filter_button]]
    name = "Cox Regression"
    tag = "Cox Regression" 

  [[content.filter_button]]
    name = "Latent Class Analysis"
    tag = "Latent Class Analysis"

  [[content.filter_button]]
    name = "Linear Regression"
    tag = "Linear Regression"

  [[content.filter_button]]
    name = "Logistic Regression (Binary)"
    tag = "Logistic Regression (Binary)"
    
  [[content.filter_button]]
    name = "Logistic Regression (Multinomial)"
    tag = "Logistic Regression (Multinomial)"

  [[content.filter_button]]
    name = "Logistic Regression (Ordinal)"
    tag = "Logistic Regression (Ordinal)"
    
  [[content.filter_button]]
    name = "Negative Binomial Regression"
    tag = "Negative Binomial Regression"
    
  [[content.filter_button]]
    name = "Poisson Regression"
    tag = "Poisson Regression"  

  [[content.filter_button]]
    name = "Power"
    tag = "Power"  
    
  [[content.filter_button]]
    name = "Sampling"
    tag = "Sampling"
    
  [[content.filter_button]]
    name = "T-Test"
    tag = "T-Test"
    
[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

