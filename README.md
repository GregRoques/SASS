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

# With React
* https://www.w3schools.com/react/react_sass.asp

Install Sass by running this command in your terminal:

```
C:\Users\Your Name>npm install node-sass
```

Import the Sass file the same way as you imported a CSS file:

* Example:

    ```
    import React from 'react';
    import ReactDOM from 'react-dom';
    import styles from './mysass.scss';
        // can also do: import './mysass.scss';
    ```
    ```
    <button
        className={styles.btn}
        onClick={() => alert('I am styled with CSS Modules')}
    > I am a Button </button>
    ```