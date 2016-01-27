# beamer-theme-tub
Unoffical Beamer theme for Technische Universität Berlin

This based upon the offical PowerPoint theme of the university. The layout and all spacings are matching with the ppt.

## Installation
**Arch**

Install [beamer-theme-tub](https://aur.archlinux.org/packages/beamer-theme-tub-git/) from the AUR (e.g. with yaourt)

    yaourt -S beamer-theme-tub
    
**Manually**

Create an image and a theme folder within your texmf-dist directory and copy the files in these.

    mkdir -p $texmf-dist/tex/latex/beamer/themes/{theme,images}
    cp images/TU_Logo_lang_RGB_red.pdf $texmf-dist/tex/latex/beamer/themes/images/
    cp theme/beamerthemeTUBlayout.sty $texmf-dist/tex/latex/beamer/themes/theme/
    cp theme/beamerinnerthemeTUBlayout.sty $texmf-dist/tex/latex/beamer/themes/theme/
    cp theme/beamerouterthemeTUBlayout.sty $texmf-dist/tex/latex/beamer/themes/theme/

### Example

![Alt text](https://cloud.githubusercontent.com/assets/15649114/11145090/7fc732ae-8a02-11e5-8189-2427b74939d1.png "Titlepage")
