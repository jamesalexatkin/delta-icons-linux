<p align="center">
	<img src="https://github.com/Delta-Icons/android/raw/master/delta-logo.png" alt="">
</p>

<h1 align="center" padding="100">Delta Icons</h1>
<p align="center">Matted out icon pack for GNOME.</p>

## Installation
* Clone this repository to somewhere on your machine:
	- `git clone https://github.com/Delta-Icons/linux.git`

* Move the `Delta` folder to `/home/.icons`.

* Set `Appearances -> Icons` to `Delta` in the GNOME Tweak Tool.

## Contributing
In case you want to contribute to Delta by providing icons please do so by creating a vector-based icon, cloning this repo and issuing a pull request with regards to these points:
- Vectors (SVG, EPS, PDF, ...) go to the `contributed-vectors` folder 
	-  Please keep filenames in lowercase alphabet with underscores
- 192 * 192 pixel PNG file `icon_name.png` goes to `app/src/main/res/drawable-nodpi`
- Name of the icon in these files, in this format `<item drawable="icon_name" />`
	- `app/src/main/assets/drawable.xml` 
	- `app/src/main/res/xml/drawable.xml`
- ComponentInfo has to be in the following files according to their format:
	- `app/src/main/assets/appfilter.xml`
	- `app/src/main/res/xml/appfilter.xml`
	- `app/src/main/res/xml/appmap.xml`
	- `app/src/main/res/xml/theme_resources.xml`
- Give yourself an entry at the bottom of `app/src/main/res/xml/contributors.xml`

### Resources for Contributions
The color palette
![Palette for Delta](https://github.com/Delta-Icons/android/raw/master/Palette.svg) (Right-Click &rarr; Save as)

Icon template
![Icon Template for Delta](https://github.com/Delta-Icons/android/raw/master/template.svg) (Right-Click &rarr; Save as)

Licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives License 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)
