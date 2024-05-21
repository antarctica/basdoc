# Quarto BAS Theme

This is a template repository using `Quarto` `reveal.js`:

![](images/title-slide.png)

This is a minimal template intended to mimic the [Presentation Hub's PowerPoint guidance](https://nercacuk.sharepoint.com/sites/BASDigitalwmod-Communications/sitePages/PowerPointPresentationsToolkit.aspx). It sets background images for the title and content slides, and refers to the BAS Style Kit CSS file, as per the [BAS Style Kit's Getting Started page](https://style-kit.web.bas.ac.uk/start/introduction/).

## Installing

``` bash
quarto use template antarctica/basdoc
```

This will install the extension and create an example qmd file that you can use as a starting place for your presentation.

## Background images

You can choose different background images for title and content slides directly from the [presentation toolkit](https://nercacuk.sharepoint.com/sites/BASDigitalwmod-Communications/sitePages/PowerPointPresentationsToolkit.aspx).

For the title slide, you will need to replace the link in `data-background-image:` in \_extensions/basdoc/\_extension.yml.

For content slides, you will need to replace the link in `background-image:` in \_extensions/basdoc/custom.scss

![](images/content-slide.png)

## Acknowledgements

Template created using [Quarto Creating Extensions \> Custom Formats](https://quarto.org/docs/extensions/formats.html#quick-start).

CSS Style sheets and guidance from [BAS Style Kit](https://style-kit.web.bas.ac.uk/).

Background images and guidance from [BAS Presentation Hub](https://nercacuk.sharepoint.com/sites/BASDigitalwmod-Communications/sitePages/presentation-hub.aspx).

[General Guidance on branding and logos](https://nercacuk.sharepoint.com/sites/BASDigitalwmod-Communications/sitePages/BrandingandLogos.aspx).
