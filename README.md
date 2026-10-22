# ScrollFlow

**A lightweight, customizable scroll-to-top button for WordPress.**

ScrollFlow adds a fixed-size back-to-top button with a circular
reading-progress ring, SVG arrow choices, and editable HEX color
settings. It is designed to reduce conflicts with theme and page-builder
button styles.

**Developer:** Rakib Hasan\
**Website:** [codewithrakib.com](https://codewithrakib.com)\
**Plugin slug:** `scrollflow`\
**Version:** 1.0.0\
**License:** GPL-2.0-or-later

## Features

-   **Custom HEX colors:** Set the button background, progress-ring
    track, and arrow icon colors using a color picker or HEX input.
-   **Four SVG icons:** Choose Chevron, Arrow, Caret, or Long Arrow.
-   **Fixed dimensions:** 48 × 48 px outer button and 36 × 36 px inner
    button.
-   **Position controls:** Set the bottom and right offsets.
-   **Progress indicator:** Enable or disable the circular
    scroll-progress ring.
-   **Mobile option:** Choose whether to display the button on mobile
    screens.
-   **Accessibility:** Includes an accessible button label and respects
    the reduced-motion preference.
-   **No external icon dependency:** Icons are inline SVG.

## Preview

The button appears after scrolling down the page. Click it to smoothly
return to the top.

## Requirements

-   WordPress 5.8 or later
-   PHP 7.4 or later

## Installation

### Install from a ZIP file

1.  Download `scrollflow.zip` from the project's release assets.
2.  In WordPress, go to **Plugins → Add New Plugin → Upload Plugin**.
3.  Select `scrollflow.zip` and click **Install Now**.
4.  Activate **ScrollFlow**.
5.  Open **Settings → ScrollFlow** to customize the button.

### Install manually

1.  Extract the plugin archive.
2.  Upload the `scrollflow` folder to `wp-content/plugins/`.
3.  Activate **ScrollFlow** from the WordPress Plugins page.

## Settings

Open **Settings → ScrollFlow** to configure:

  -----------------------------------------------------------------------
  Setting                             Description
  ----------------------------------- -----------------------------------
  Button background color             HEX color for the inner button
                                      background

  Progress ring background            Color of the unfilled progress ring

  Arrow icon color                    Color of the SVG arrow

  Arrow icon                          Choose one of four SVG icons

  Distance from bottom                Vertical offset in pixels

  Distance from right                 Horizontal offset in pixels

  Show circular scroll progress       Toggles the progress ring

  Show on mobile                      Toggles the button on mobile
                                      screens

  Developer credit tooltip            Toggles the developer credit in the
                                      button tooltip
  -----------------------------------------------------------------------

Example HEX color: `#0F5938`.

## GitHub development

Clone the repository:

``` bash
git clone https://github.com/code-with-rakib/ScrollFlow.git
cd ScrollFlow
```

The main plugin file is `scrollflow.php`.

To contribute:

1.  Fork the repository.
2.  Create a branch for your change.
3.  Make and test your change on a WordPress test site.
4.  Commit your work and push the branch.
5.  Open a pull request describing the change.

## Reporting issues

Please open an issue in the GitHub repository and include:

-   WordPress and PHP versions
-   The theme or page builder being used
-   Steps to reproduce the problem
-   Any relevant error messages or screenshots (with private information
    removed)

## License

ScrollFlow is distributed under the **GNU General Public License v2.0 or
later**. See [LICENSE](LICENSE).

## Credits

Developed by **Rakib Hasan** ---
[codewithrakib.com](https://codewithrakib.com).
