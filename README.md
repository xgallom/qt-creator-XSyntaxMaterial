# QtCreator XSyntaxMaterial Color Scheme
A dark colored scheme for QtCreator that I use, works great with the default Flat Dark theme.
Loosely based on [Atom Material Syntax Theme](https://atom.io/themes/atom-material-syntax) and the defaults of Qt Creator Dark color scheme.

## Note
Currently uses Material colors or their slight modifications for all C++ syntax, the QML and Diff editor are left as defaults.

## Install
- **Clone or download this repository**

- **Copy the color scheme to QtCreators styles directory**

  QtCreator stores styles in different locations on different operating systems:
  - *Windows:* `%APPDATA%\QtProject\qtcreator\styles`
  - *Linux, Mac:* `~/.config/QtProject/qtcreator/styles`

- **Open QtCreator and set the color scheme to XSyntaxMaterial**

  - Go to `Tools -> Options -> Text Editor -> Fonts & Colors`
  - Change Color scheme to **XSyntaxMaterial**

- **_(Optional) Also set the QtCreator theme to Flat Dark_**

  - Go to `Tools -> Options -> Environment -> Interface`
  - Change Theme to **Flat Dark**
  - Restart Qt Creator

  _Note: Changing theme might change your color scheme to default,
  so I recommend changing it **before** setting your color scheme._

## Example installation
```Shell
git clone https://github.com/xgallom/qt-creator-XSyntaxMaterial.git
cp qt-creator-XSyntaxMaterial/xsyntaxmaterial.xml ~/.config/QtProject/qtcreator/styles/
rm -r qt-creator-XSyntaxMaterial
```

## Features
- Default background colors of **Flat Dark** theme - Fits in with it perfectly!
- Modern and well readable look of [Atom Material Syntax Theme](https://atom.io/themes/atom-material-syntax) with few modifications to keep the code all and well in the darker QtCreator theme
- Different color of **Types**, **Primitive Types**, **Globals**, and **Locals and Functions** (found having a separate color for **Functions** and **Local Variables** quite intrusive)

## Contributing
If I never get to finish the QML and Diff highlights, and you want to do your part, just hit me with a pull request and if it's good then it's good!

## License
This project is licensed under MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Author
Milan Gallo - [xgallom](https://github.com/xgallom)

