Visual Studio Dark Theme for IDEA Intellij
============================================

A replica of Visual Studio's dark theme for Intellij.

![Example with Groovy](/screenshots/groovy.png)

## Installation

### Automatic

- Download [settings.jar](/settings.jar)
- In Intellij, go to File -> Import Settings
- Select the settings.jar file you downloaded and press OK.

Intellij will then restart before applying the color theme. If the theme is not automatically applied, go to File -> Settings and then Editor -> Colors & Fonts and select the theme manually (Visual Studio 2015).

### Manual

Download [Visual Studio 2015.icls](https://raw.githubusercontent.com/BenBanerjeeRichards/Intellij-Visual-Studio-Dark-Theme/master/Visual%20Studio%202015.icls). Place it in:

- **Windows:** `C:\<username>\<Intellij Folder>\config\colors\`
- **Mac:** `~/Library/Preferences/<Intellij Folder>/colors`
- **Linux:** `~/<Intellij Folder>`

\`Intellij  Folder\` will be something like \`.IntelliJIdea2017.1\`. For more information, see the [Intellij  help page](https://www.jetbrains.com/help/idea/directories-used-by-intellij-idea-to-store-settings-caches-plugins-and-logs.html).

Then select the theme in File -> Settings and then Editor -> Colors & Fonts.

## Supported Languages

Currently, the theme will work with:

- Java
- Groovy (with grails support)
- Python
- Kotlin
- HTML, CSS, Less, Sass/SCSS
- Javascript, Typescript and CoffeeScript, 
- Templating Languages (GSP, JSP...)
- Actionscript
- Batch Script
- Cucumber
- SQL
- XML and XSLT
- JSON and YAML

and some others.
