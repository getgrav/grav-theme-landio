# Landio Theme for Grav

![Landio](assets/readme_1.png)

Landio is a responsive HTML template, built on top of [Bootstrap 4](https://v4-alpha.getbootstrap.com/) and based on the [Land.io Sketch design](https://tympanus.net/codrops/2015/09/16/freebie-land-io-ui-kit-landing-page-design-sketch/) by [Peter Finlan](https://peterfinlan.com/). This template and the UI kit were coded by [Taty Grassini](https://tatygrassini.github.io/).

# Built on:

* Bootstrap 4
* Icomoon
* Power of GRAV

# Features:

* Admin plugin support with customizable user area
* VideoJS
* Testimonials layout
* HTML5 and CSS3
* Fully Responsive
* Attractive and modern design
* Various templates for presenting your content

# Installation

Installing the Landio theme can be done in one of two ways. Our GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file.

The theme by itself is useful, but you may have an easier time getting up and running by installing a skeleton. The [Landio Site Skeleton](https://github.com/getgrav/grav-skeleton-landio-site) is a self-contained repository for a complete sites which includes: sample content, configuration, theme, and plugins.

## GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](https://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install landio

This will install the Landio theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/landio`.

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `landio`. You can find these files either on [GitHub](https://github.com/getgrav/grav-theme-landio) or via [GetGrav.org](https://getgrav.org/downloads/themes).

You should now have all the theme files under

    /your/site/grav/user/themes/landio

>> NOTE: This theme is a modular component for Grav which requires the [Grav](https://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

# Updating

As development for the Landio theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating Landio is easy, and can be done through Grav's GPM system, as well as manually.

## GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](https://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update landio

This command will check your Grav install to see if your Landio theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

## Manual Update

Manually updating Landio is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/landio` directory.
* Download the new version of the Landio theme from either [GitHub](https://github.com/getgrav/grav-theme-landio) or [GetGrav.org](https://getgrav.org/downloads/themes).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `landio`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.

# Setup

If you want to set Landio as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: landio`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **landio** folder.

# Usage

To customize Land.io footer, header, topbar and social counts open [example configuration file](https://github.com/getgrav/grav-skeleton-landio-site/blob/develop/config/site.yaml) from Land.io skeleton. You can customize each section to fit your needs.

# Credits

*   [Bootstrap](https://getbootstrap.com/)
*   [Icomoon](https://icomoon.io/)
*   [UI Faces](https://uifaces.com/)
*   [Quotes on Design](https://quotesondesign.com/)
*   [Unsplash](https://unsplash.com/)
*   [Video JS](https://videojs.com/)
*   [Vimeo jQuery API](https://github.com/jrue/Vimeo-jQuery-API)
*   [Chart JS](https://www.chartjs.org/)
*   [Waypoints](https://github.com/imakewebthings/waypoints)
*   [Animate.css](https://daneden.github.io/animate.css/)

### Misc

Follow Pete: [Twitter](https://twitter.com/peterfinlan), [Dribbble](https://www.dribbble.com/peterfinlan)

Follow Taty: [Twitter](https://twitter.com/tatygrassini), [GitHub](https://github.com/tatygrassini)

Follow Codrops: [Twitter](https://www.twitter.com/codrops), [Facebook](https://www.facebook.com/pages/Codrops/159107397912), [Google+](https://plus.google.com/101095823814290637419), [GitHub](https://github.com/codrops), [Pinterest](https://www.pinterest.com/codrops/)
