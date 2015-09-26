Material Design Template used to develop the Cameroon Programming Contest 2015 site.

Demo of the site can be found here: http://vg.am/devfest

## Quick-start guide
1.  [Fork](https://github.com/GDG-Buea/cameroonpc/fork) this repo and clone locally.
2.  Install [Node.js](www.nodejs.org).
3.  Run `npm install -g gulp bower && npm install && bower install` from the root of the folder.

#### Requirements

Project dependencies:

- Node.js used to run JavaScript tools from the command line.
- npm, the node package manager, installed with Node.js and used to install Node.js packages.
- gulp, a Node.js-based build tool.
- bower, a Node.js-based package manager used to install front-end packages (like Polymer).

**To install dependencies:**

1)  Check your Node.js version.

```sh
node --version
```

The version should be 0.12.x or above.

2)  If you don't have Node.js installed, or you have a lower version, go to [nodejs.org](https://nodejs.org) and click on the big green Install button.

3)  Install `gulp` and `bower` globally.

```sh
npm install -g gulp bower
```

This lets you run `gulp` and `bower` from the command line.

4)  Install the projects's local `npm` and `bower` dependencies.

```sh
cd cameroonpc && npm install && bower install
```

This installs the element sets and tools the hoverboard template requires to build and serve apps.

5) To run the code and see the changes you've made, just open the index.html file in a browser OR on the terminal run

```sh
firefox index.html
```
