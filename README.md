# gradstrap
A css gradient library

## Motivation
I made gradstrap to ease the way i use gradients in ui designs, Instead of first having to find the right 
color fit every time i want to use gradients in a project, i can choose from an already made library of well
thought out color combinations following color theory. All you have to do is use the relevant css class
on the element you want to have a gradient.


## Usage

You can use gradstrap in two ways 
 1. Use of CDN in your link tag
 2. Npm installation

### Using CDN

this library is available on jsdelivr cdn ` ` inorder to boost load time speeds. It can be referenced it your link tags to have it avalable for use in your project
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gradstrap@1.0.1/gradstrap.min.css">

```
Then you can reference any particular gradient by calling its class name in the element's class tag
for example
```html
<div class= "grad-tomato"></div>

``` 
that would set the div's background colour to the specified gradient

### Using npm install

You can install the development version to your local machine from npm
```bash
npm install gradstrap
```
## Pull Requests

Gradstrap is built using sass and Pull requests are welcome for an overview on the available gradients in the library check out [Gradstrap](https://www.tibetegya.com/gradstrap) Website


## License
MIT License

Copyright (c) 2018 George Tibetegya
