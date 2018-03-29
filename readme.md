# Girl Effect Theming

This theming pack will assist developers with theming the core authentication service.

## Get started

### Running locally

* It's best to run a small static node server locally.

#### Install Node.js:

* Use your favourite package manager to install Node:
https://nodejs.org/en/download/package-manager/

#### Install static-server:

* You can do this by typing the following in your terminal:

`npm -g install static-server`

* And then run it with:

`static-server`

You can now navigate to the URL in your terminal

## Contents

* `docs` It's only purpose is the contents of this theming pack, as well as hosting the default theme
* `components` Lists all the various components that is used, along with their classes
* `pages` Lists all the various pages and how the components are placed, along with theming instructions

## Advanced

The core authentication service's view layer uses Django templating. This means we can overwrite some of the templates 
completely, and have different HTML altogether. This approach will take longer to implement, but is possible.

## Note

Please make sure you cater for both feature and enhanced devices, so please provide 2 stylesheets as per the theming advice on `pages`.