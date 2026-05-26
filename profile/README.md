# BrickCode - A community maintained fork of Microsoft MakeCode for LEGO MINDSTORMS EV3

Microsoft is no longer updating the main [pxt-ev3](https://github.com/microsoft/pxt-ev3/) project.
The [cloud version](https://makecode.mindstorms.com/) is available but running an old version of MakeCode.

This GitHub organization contains a community fork of the MakeCode repositories and hosts it on GitHub pages.

## [Go to BrickCode for EV3 ▶](https://brickcode.org/)

The latest release from `pxt-ev3` repository is published here: [https://brickcode.org/](https://brickcode.org/).

The latest master branch from `pxt-ev3` is published on the beta site: [https://beta.brickcode.org](https://beta.brickcode.org/)

### Repositories

* [pxt-ev3](https://github.com/pxt-ev3-community/pxt-ev3): The MakeCode system module for EV3 platform
* [pxt-ev3-translations](https://github.com/pxt-ev3-community/pxt-ev3-translations): Mirror of the translation files from Crowdin

### Saving and cloud integration

By default the editor saves files to local storage in your browser.
The files will only be present on your own computer.

Alternatively you can use GitHub integration to save files by creating an API token.

### Translations

Translations are downloaded from [Crowdin makecode project](https://crowdin.com/editor/makecode/) weekly.

If there are any strings that are not included in the Crowdin project, they can be manually added to json files in [pxt-ev3-translations](https://github.com/pxt-ev3-community/pxt-ev3-translations).

### Forking

You can [fork the repository on GitHub](https://github.com/pxt-ev3-community/pxt-ev3/fork).

After forking, enable these settings to make the site build and host itself on GitHub Pages under your account:

* **Settings -> Actions -> General**: Allow all actions
* **Settings -> Pages**: Source = GitHub Actions

### Self-hosting

Easily self-hostable release .zips are available on the [releases page](https://github.com/pxt-ev3-community/pxt-ev3/releases).

You can host it using e.g. Python:

    cd self-hostable-pxt-ev3
    python3 -m http.server

### Privacy

Nothing is uploaded to the pxt-ev3-community sites from the editor.
The editor may access some Microsoft's makecode.com cloud APIs, for which the privacy statement is available [here](https://go.microsoft.com/fwlink/?LinkId=521839).

### License

This is a community effort, it is not endorsed by LEGO or Microsoft.

LEGO, the LEGO logo, MINDSTORMS and the MINDSTORMS EV3 logo are trademarks and/ or copyrights of the LEGO Group. ©2018 The LEGO Group. All rights reserved.

The MakeCode project is available under the [MIT License](https://github.com/pxt-ev3-community/pxt-ev3/blob/master/LICENSE).
