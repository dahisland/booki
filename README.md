[![forthebadge](./readme-assets/html5-badge.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)

<br/>

<div id="header" align="left">
  <img src="./readme-assets/Booki.png" width="200"/>
</div>

# Project BOOKI

Booki is a small company offering an online vacation planning tool.

Its site allows users to find accommodation and activities in the city of their choice.
The accommodations can also be filtered by theme, for example their budget or their atmosphere.

The objective of this project has been to produce the HTML/CSS prototype of the homepage for the next company's new site from the models provided.

# Basic instructions

## Functional specifications

1. Users will be able to search for accommodation in the city of their choice.
   The search field is an input field, so the text must be editable by the user.
   This field must be included in a form to be valid with the W3C.
   The research part should not be functional.
2. Each accommodation or activity card must be clickable in its entirety (not just the title).
   For now, the links are empty.
   You can use the `href=”#”` to simulate the link url.
3. Filters should change appearance on hover.
   The appropriate effect is left free but the filters must not be functional.
4. The texts “Accommodations” and “Activities”, located in the header, are links.
   They must lead respectively to the “Accommodation in Marseille” and “Activities in Marseille” sections.

## Technical specifications

1.  Two models have been created : one desktop and the other mobile.
    The site must also be adapted to tablet formats.
    For tablets, we are free to make the necessary adaptations.
    It is important that no element is cut off, and that the text is of sufficient size.
2.  Regarding breakpoints, it was agreed with the UI designer to use 992 px and 768 px:
    992 px for computer screens, 768 px for tablets and anything below 768 for mobile phones.
3.  It is first necessary to carry out the integration for the computers (desktop first), then the tablets and
    finally the telephones.
    The use of Media Queries will allow integration for the different media.
4.  Several image formats and sizes have been exported.
    It will be necessary to choose the most suitable format in relation to the resolution and the loading time.
5.  The icons come from the Font Awesome library (go through a CDN to make loading the icons easier).
6.  The chart colors are blue (#0065FC), a lighter version of this blue (#DEEBFF) and gray for the background
    (#F2F2F2).
7.  The site font is Raleway ( Google Font import link https://fonts.google.com/specimen/Raleway ).
8.  It is important to use pixels and percentages rather than REM and EM.
9.  It is important to use Flexbox rather than Grid because it is the technology that the team masters best.
10. No CSS framework (BootStrap or Tailwind CSS type) or CSS preprocessor (Sass or Less type) should be used.
11. It is important to use semantic tags (type `main`, `header`, `nav`, etc.).
12. The code must be valid to W3C HTML and CSS validators.
13. The mockup should be compatible with the latest versions of Google Chrome and Mozilla Firefox.
    The prototype will have to be tested on these two browsers.
14. There is no need to version the code.

# Project report

An HTML/CSS prototype was produced in accordance with the instructions set out above.
The rendered files consist of an index.html along with its formatting CSS files.
The project meets the client's expectations on the following points:

- HTML and CSS compliant with W3C standards
- Responsive design for desktop, tablet and smartphone resolutions (compliance with provided breakpoints)
- Respect for the design and the graphic charter proposed by the models and the summary note provided
- Prototype compatibility with the latest versions of Chrome and Firefox
- Optimization of loading time with judicious integration of image resolutions adapted to different media
- Majority use of flexbox to optimize the responsive design
- Use of appropriate semantic tags to facilitate accessibility and referencing of the site
