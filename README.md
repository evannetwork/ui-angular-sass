# angular-sass
The angular-sass library includes styling definitions for evan.network featured DApps.
Install angular-sass to your project and reference the variable files and core stylings. 

## Features
- font-style: Open Sans
- [Ionic Styles](https://github.com/ionic-team/ionic)
- positioning & color sass variables
- evan.network start page & loading symbol
- alert style adjustments
- button styles
- content containers with dynamic sizes
- dashboard side panel style
- form specific stylings
- grid styles
- modal styles
- popover styles
- table styles
- tab styles
- Ionic adjustments

## API Documentation and Tutorials
- [DApp Tutorials](https://evannetwork.github.io/dapps/basics)
- [API Reference UI](https://ipfs.test.evan.network/ipns/QmReXE5YkiXviaHNG1ASfY6fFhEoiDKuSkgY4hxgZD9Gm8/angular-sass/index.html)

## Installation
```sh
npm i @evan.network/ui-angular-libs
```

## Usage
Include sass libs by importing files like to following:

```sass
@import "angular-sass/src/colors";

div.my-class {
  background-color: $background-color;
}
```
