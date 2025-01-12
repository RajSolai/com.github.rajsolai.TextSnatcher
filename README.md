This is a fork of the original repo. I have updated the GNOME Runtime version to 47.

---

<h1>Thanks for all the Support shown by Stars, Issues and PRs 💌 ! Currently I'm Saving money for my Linux PC, Soon (next month) the project will be back with updates and fixes</h1>

[![Vala Programming language](https://img.shields.io/badge/Made%20With-Vala%20-A56DE2)](https://wiki.gnome.org/Projects/Vala)
![Flatpak Build workflow](https://github.com/RajSolai/TextSnatcher/actions/workflows/flatpak-build.yml/badge.svg)

<div align="center">
<img src="./data/icons/com.github.rajsolai.textsnatcher.svg" height="110px" />
<h1>TextSnatcher</h1>
<p>Copy Text from Images with ease, Perform OCR operations in seconds.</p>
<img alt="TextSnatcher OCR App for Linux" src="https://raw.githubusercontent.com/RajSolai/TextSnatcher/master/data/screenshots/snap-default.png"/></br>
<a href="https://www.producthunt.com/posts/textsnatcher?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-textsnatcher" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=344401&theme=light" alt="TextSnatcher - How&#0032;to&#0032;copy&#0032;text&#0032;from&#0032;images&#0044;&#0032;answer&#0032;is&#0032;TextSnatcher | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
</div>

## Download

<div align="center">
  <a href='https://flathub.org/apps/details/com.github.rajsolai.textsnatcher'><img width='240' alt='Download on Flathub' src='https://flathub.org/assets/badges/flathub-badge-i-en.png'/></a></br>
  
<a href="https://appcenter.elementary.io/com.github.rajsolai.textsnatcher"><img src="https://appcenter.elementary.io/badge.svg" alt="Get it on AppCenter"></a>
</div>

## Features

-   Multiple Language Support.
-   Copy Text from images with a Drag.
-   Drag over any Image and Paste.
-   Fast and Easy to Use.
-   This application uses the Tesseract OCR 4.x for the character
    recognition.
-   Read more about [Tesseract](https://tesseract-ocr.github.io/tessdoc/Home.html) and Star ⭐️ [Tesseract-Project](https://github.com/tesseract-ocr/tesseract).

## Screencasts

https://user-images.githubusercontent.com/54436424/152921719-228485ba-0d37-4b01-864e-63a2792248b5.mp4

https://user-images.githubusercontent.com/54436424/152921736-c9567c9d-0afa-4c09-8706-6b2a1b6b635a.mp4

## Screenshots

![TextSnatcher OCR App for Linux](https://raw.githubusercontent.com/RajSolai/TextSnatcher/master/data/screenshots/snap-default.png)

![TextSnatcher OCR App for Linux](https://raw.githubusercontent.com/RajSolai/TextSnatcher/master/data/screenshots/snap-dark.png)

## Support Me

<a href="https://www.buymeacoffee.com/rajsolai" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="width: 200px;" ></a>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R7ABG0F)

## Social Media Posts

[LinkedIn Post on Why I created TextSnatcher](https://www.linkedin.com/posts/solai085_linux-commentbelow-apple-activity-6826408004519374848-wxsw)

## Dependencies

Ensure you have these dependencies installed

### Runtime Dependency

-   scrot
-   tesseract-ocr
-   tesseract language data
    [arch repos](https://archlinux.org/packages/community/x86_64/tesseract)
    [debian repos](https://packages.debian.org/search?keywords=tesseract-ocr)

### Buildtime Dependency

-   granite
-   gtk+-3.0
-   gobject-2.0
-   gdk-pixbuf-2.0
-   libhandy-1
-   libportal-0.5

## Install, build and run

```bash
# clone repository
git clone https://github.com/RajSolai/TextSnatcher.git TextSnatcher
# cd to dir
cd TextSnatcher
# run meson
meson build --prefix=/usr
# cd to build, build and test
cd build
sudo ninja install && com.github.rajsolai.textsnatcher
```

## Inspirations

-   ReadMe: https://github.com/alainm23/planner
-   Application Structure: https://github.com/alcadica/develop
-   TextSniper (MacOS Application)

Made with ❤️ for Linux
