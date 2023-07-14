# Introduction
This repository host the `matplotlib` style sheet I use for making publication-quality figures.

# Requirements
You will need at least `matplotlib` 1.4.0 or a later version to use custom style sheets. There is no specific requirement for Python version, but I recommend using the latest stable version.

STIX fonts is required to use this style sheet. To install the fonts, visit the STIX website at https://www.stixfonts.org/, or download and install the OTF or TTF files from their GitHub repository at https://github.com/stipub/stixfonts.


# Installation
To use this style sheet, download and put the `.mplstyle` file under `stylelib/` in the matplotlib configuration directory. On most systems, the default location for the `matplotlib` configuration directory is within your user directory, e.g.,

* Windows: C:\Users\<username>\.matplotlib

* macOS: /Users/<username>/.matplotlib

* Linux: /home/<username>/.matplotlib

Or, if you want to check the location of `matplotlib` configuration directory, you can do

`
from matplotlib import get_configdir
`

and

`
print(get_configdir())
`

# Usage
Once installed, you can use the style sheet by

`
matplotlib.pyplot.style.use("mycustomised")
`
