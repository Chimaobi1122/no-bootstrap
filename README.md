# no-bootstrap

no-bootstrap is a CSS/SCSS library for abstracting boostrap responsive layout models without having to import bootstrap and the many other unnecessary 10,000 lines of boostrap styles.

![GitHub package.json version](https://img.shields.io/github/package-json/v/Nnaji-Victor/no-bootstrap)

![GitHub last commit (branch)](https://img.shields.io/github/last-commit/Nnaji-Victor/no-bootstrap/development)

![GitHub](https://img.shields.io/github/license/Nnaji-Victor/no-bootstrap)
![GitHub followers](https://img.shields.io/github/followers/Nnaji-Victor?style=social)
![GitHub forks](https://img.shields.io/github/forks/Nnaji-Victor/no-bootstrap?style=social)
:rocket:

## Installation

[clone](https://github.com/Nnaji-Victor/no-bootstrap.git) the repo on your local machine as thus

```git
git clone https://github.com/Nnaji-Victor/no-bootstrap.git
```


## Usage
no-bootstrap uses the bootstrap class names for it's layout such as
* container
* container-fluid
* row
* col-*

some utility classes like
* d-flex
* d-*
* w, h, vh, vw

## Styling
The no-bootstrap container comes with an additional left and right padding of 15px each. You can override this with your own padding or none at all. Example
```css
.container {
    padding-right: 0px;
    padding-left: 0px;
}
```
The code above overrides the default container padding.

## Changing the variable properties of no-bootstrap
no-bootstrap is written in SCSS which leaves room for more code organization. The variables such as the device-width and container width are stored in the **_variables.scss** file. Changing the value of the variables will affect the overall values of the same name used anywhere in the code. 

```scss
$small-device: 600px;
```
This overides the default 576px set as the breakpoint for small devices. 

## want to learn how to use scss?
The sass lang website offers some good documentation to begin with. Find it [here](https://sass-lang.com/documentation)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
