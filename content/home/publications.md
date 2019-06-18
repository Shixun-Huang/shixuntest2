+++
# A Recent Publications section created with the Pages widget.
# This section displays recent blog posts from `content/publication/`.

widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 90  # Order that this section will appear.

title = "Recent Publications"
subtitle = ""

[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "publication"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 5
  
  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    exclude_featured = false
  
[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 2
  
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

{{% alert note %}}
Quickly discover relevant content by [filtering publications]({{< ref "/publication/_index.md" >}}).
{{% /alert %}}

  <h3 class="article-title" itemprop="name">
    <a href="https://JMMackenzie.io/publication/sigir19/" itemprop="url">Accelerated Query Processing Via Similarity Score Prediction</a>
  </h3>

  <div class="pub-abstract" itemprop="text">
    
    Processing top-$k$ bag-of-words queries is critical to many information retrieval applications, including web-scale search. In this work, we consider algorithmic properties associated with dynamic pruning mechanisms. Such algorithms maintain a score threshold (the $k$th highest similarity score identified so far) so that low-scoring documents can be bypassed, allowing fast top-$k$ retrieval with no loss in effectiveness. In standard pruning algorithms the score threshold is initialized to the lowest possible value. To accelerate processing, we make use of term- and query-dependent features to predict the final value of that threshold, and then employ the predicted value right from the commencement of processing. Because of the asymmetry associated with prediction errors (if the estimated threshold is too high the query will need to be re-executed in order to assure the correct answer), the prediction process must be risk-sensitive. We explore techniques for balancing those factors, and provide detailed experimental results that show the practical usefulness of the new approach.
    
  </div>

  <div class="pub-authors" itemprop="author">
    
    M. Petri, A. Moffat, J. Mackenzie, J. S. Culpepper, and D. Beck
    
  </div>

  <div class="pub-publication">
    SIGIR,
    2019</div>

  <div class="pub-links">
