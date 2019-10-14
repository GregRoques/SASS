## Official Website
* https://sass-lang.com/

### Install with Node
* npm install -g sass

![SASS Features](/readMeImage/Features.JPG)

### SASS/SCSS syntax
* SASS removes brackets and semi-colons; indentation determines attribution to above element
* SCSS retains CSS syntax

## Compiling in Terminal
* $ sass main.scss main.css
    * translation: sass (the command) main.scss (the file we are converting) main.css (the new css file that will generate from our .scss file)
    * -- will generate a map file to link to related html documents
    * once created, you can type in a command to watch for changes to constantly update our new .css file:
        *  $ sass --watch main.scss:main.css

## Working With Colors
* Sass color Modules:
    * https://sass-lang.com/documentation/modules/color
* Non-SASS color tools and Extenstions
    * Adobe Capture for mobile
    * ColorPick Eyedropper Google Chrome Extenstion for Desktop
