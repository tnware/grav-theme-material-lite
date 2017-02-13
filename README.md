# Material Lite

![Material Lite](screenshot.jpg)

# Features

Material Lite has few features aside from base design.

### Plugins:
Breadcrumbs Plugin Support
 - adds breadcrumbs above page title in each page


# Installation

Installing the Material Lite theme can be done in one of two ways. Our GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file.

The theme by itself is useful, but you may have an easier time getting up and running by installing a skeleton. The Material Lite theme can be found in both the [One-page](https://github.com/getgrav/grav-skeleton-onepage-site) and [Blog Site](https://github.com/getgrav/grav-skeleton-blog-site) which are self-contained repositories for a complete sites which include: sample content, configuration, theme, and plugins.

## GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install material-lite

This will install the Material Lite theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/material-lite`.

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `material-lite`. You can find these files either on [GitHub](https://github.com/tnware/grav-theme-material-lite) or via [GetGrav.org](http://getgrav.org/downloads/themes).

You should now have all the theme files under

    /your/site/grav/user/themes/material-lite

>> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

# Updating

As development for the Material Lite theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating Material Lite is easy, and can be done through Grav's GPM system, as well as manually.

## GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update material-lite

This command will check your Grav install to see if your Material Lite theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

## Manual Update

Manually updating Material Lite is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/material-lite` directory.
* Download the new version of the Material Lite theme from either [GitHub](https://github.com/tnware/grav-theme-material-lite) or [GetGrav.org](http://getgrav.org/downloads/themes#extras).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `material-lite`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.
