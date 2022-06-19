This plugin adds an AJAX-powered Masonry portfolio with category filters and a modal dialog.

## Requirements
This plugin requires **jQuery** and the **Ajax Framework** to be included in your layout/page:
```
{% put scripts %}
    <script src="{{ [
        '@jquery',
        '@framework',
        ...
        'assets/js/main.js'
    ]|theme }}"></script>
{% endput %}
```

## Features
- Pinterest-inspired masonry-based layout with ragged bottoms
- Complete control over column count, gutter and spacing
- Custom styling with Sass
- Loading effects
- Responsive images
- 2x image variants for high pixel-density displays
- AJAX-powered
- Category filters
- Modal dialog with details
- Custom scrollbar
- Optioanl horizontal left-to-right order

## Contribution
The GitHub repository for this plugin can be found [here](https://github.com/PictureElement/portfolio-plugin). Please feel free to contribute or report any bugs.
