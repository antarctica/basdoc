# Quarto BAS Theme

This is a template repository using `Quarto` `reveal.js`:

![](images/title-slide.png)

This is a minimal template intended to mimic the Presentation Hub's PowerPoint guidance. All it does it set background images for the title and content slides, and refer to the BAS Style Kit CSS file, as per the [BAS Style Kit's Getting Started page](https://style-kit.web.bas.ac.uk/start/introduction/).

## Installing

``` bash
quarto use template antarctica/basdoc
```

This will install the extension and create an example qmd file that you can use as a starting place for your presentation.

## Background images

You can choose different background images for title and content slides directly from the [presentation toolkit](https://nercacuk.sharepoint.com/sites/BASDigitalwmod-Communications/sitePages/PowerPointPresentationsToolkit.aspx).

For the title slide, you will need to replace the link in `data-background-image:` in \_extensions/basdoc/\_extension.yml.

For content slides, you will need to replace the link in `background-image:` in \_extensions/basdoc/custom.scss