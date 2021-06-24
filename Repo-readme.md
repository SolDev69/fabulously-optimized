# Fabulously Optimized repository

Welcome to my repository.
Here you'll find the resources for:

* Curseforge modpack [(read more)](https://support.curseforge.com/en/support/solutions/articles/9000196904-creating-a-custom-profile)
* MultiMC modpack [(read more)](https://github.com/MultiMC/MultiMC5/wiki/Instance-settings)
* MultiMC modpack with packwiz [(read more)](https://github.com/comp500/packwiz#packwiz-installer-for-pack-installation)
* Packwiz files [(read more)](https://github.com/comp500/packwiz#packwiz)

Other things to note:

* As seen in the `.gitignore` file, this repo will not include JAR files of any kind to respect the modders. If you want to build a pack based on this, get the JARs manually via any method you like (Curseforge launcher, Curseforge website, Modrinth, packwiz, ...).
* Because there are no JARs, some folders would usually not be uploaded by Git at all, this is worked around using a `.gitkeep` file [(read more)](https://stackoverflow.com/a/7229996) to keep the folder structure.
* Since some folders are duplicated - such as config folders, I am using Windows-like soft symlinks [(read more)](https://blogs.windows.com/windowsdeveloper/2016/12/02/symlinks-windows-10/). Those don't work very well in Github, so I recommend using a [local Git client](https://desktop.github.com).