# px-theme

## Overview

`Px-theme` is a Predix UI component which serves as the starting point for theming other Predix UI components. It is based loosely on the concepts outlined [here](https://www.polymer-project.org/1.0/docs/devguide/styling.html#xscope-styling).


## Usage

### Prerequisites
1. node.js
2. npm
3. bower
4. [webcomponents-lite.js polyfill](https://github.com/webcomponents/webcomponentsjs)

Node, npm, and bower are necessary to install the component and dependencies. webcomponents.js adds support for web components and custom elements to your application.

### Getting Started

First, install the style module via bower on the command line:

```
bower install px-theme --save
```

Second, import the style module in your application with the following tag in your head:

```
<link rel="import" href="/bower_components/px-theme/px-theme-styles.html"/>
```

Finally, use the style module in your application.

```
<style include="px-theme-styles"></style>
```

Read more about Polymer style modules [here](https://www.polymer-project.org/2.0/docs/devguide/style-shadow-dom#style-modules).


## Local Development

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

From the component's directory, to start a local server run:

```
$ gulp serve
```

Navigate to the root of that server (e.g. http://localhost:8080/) in a browser to open the API documentation page, with link to the "Demo" / working examples.




### GE Coding Style Guide
[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

<br />
<hr />

## Known Issues

Please use [Github Issues](https://github.com/PredixDev/px-theme/issues) to submit any bugs you might find.
