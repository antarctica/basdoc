# Quarto BAS Theme

This is a template repository using `Quarto` `reveal.js`:

![](images/title-slide.png)

This is a minimal template intended to mimic the [Presentation Hub's PowerPoint guidance](https://nercacuk.sharepoint.com/sites/BASDigitalwmod-Communications/sitePages/PowerPointPresentationsToolkit.aspx).

It sets background images for the title and content slides, and refers to the BAS Style Kit CSS file, as per the [BAS Style Kit's Getting Started page](https://style-kit.web.bas.ac.uk/start/introduction/).

## Installing
### New Directory
``` bash
quarto use template antarctica/basdoc
```
This will install the extension in a new directory and create an example qmd file that you can use as a starting place for your presentation.

### Existing Directory
To add the extension to an existing directory, you can use:
``` bash
quarto add antarctica/basdoc
```
This will add the extension to an existing directory, but will not provide you with an example qmd file.

## Background images

You can choose different background images for title and content slides directly from the [presentation toolkit](https://nercacuk.sharepoint.com/sites/BASDigitalwmod-Communications/sitePages/PowerPointPresentationsToolkit.aspx).

To change the **title slide** image, in `_extensions/basdoc/_extension.yml` replace `data-background-image:`.

``` yaml
title-slide-attributes: 
  data-background-image: https://nercacuk.sharepoint.com/sites/basdigitalwmod-communications/creative%20services%20assets/ppt_title_halley.jpg
```

For **content slides**, in `_extensions/basdoc/custom.scss` replace `background-image:`

``` sass
/*-- scss:rules --*/
.slide-background-content{
  background-image: url("https://nercacuk.sharepoint.com/sites/basdigitalwmod-communications/creative%20services%20assets/ppt_page_glider01.jpg");
  background-size: 100% 100%
}
```

![](images/content-slide.png)

If you want to override the global content slide background, you can do so by specifying it in the slide title:

```md
## Content slides {background-image=https://nercacuk.sharepoint.com/sites/basdigitalwmod-communications/creative%20services%20assets/ppt_page_adelie01.jpg}
text
```

## Acknowledgements

Template created using [Quarto Creating Extensions \> Custom Formats](https://quarto.org/docs/extensions/formats.html#quick-start).

CSS Style sheets and guidance from [BAS Style Kit](https://style-kit.web.bas.ac.uk/).

Background images and guidance from [BAS Presentation Hub](https://nercacuk.sharepoint.com/sites/BASDigitalwmod-Communications/sitePages/presentation-hub.aspx).

This repository aims to provide a minimum template. Further customisation is up to the user, see [General Guidance on branding and logos](https://nercacuk.sharepoint.com/sites/BASDigitalwmod-Communications/sitePages/BrandingandLogos.aspx).
