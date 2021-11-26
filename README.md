# Footer Component in Shared Module using Ionic with Angular

Example of a footer component in a shared module in an Ionic project using Angular.

This way you can share the same footer in all ionic pages. With this solution you just have to include the following lines in every page where you want your footer after the ion-content element:

```
<ion-footer>
  <app-footer></app-footer>
</ion-footer>
```

## Getting Started

After cloning this project don't forget to:

```
npm install
```

After that:

```
cd ionic-angular-footer
ionic serve
```

Enjoy!!!

### Prerequisites

You need a working environment with:
* [Git](https://git-scm.com) - You can install it from https://git-scm.com/downloads.
* [Node.js](https://nodejs.org) - Install node.js from https://nodejs.org/es/download/. It's advisable to install the LTS version.
* [Ionic](https://ionicframework.com/docs/intro/cli) - Installing Ionic.

## Built With

* [Visual Studio Code](https://code.visualstudio.com/) - The Editor used in this project
* [Node.js](https://nodejs.org/) - Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.
* [Ionic](https://ionicframework.com/docs/intro/cli) - Installing Ionic.

## Acknowledgments

* https://stackoverflow.com/questions/57290461/ionic-how-to-set-a-header-on-multiple-pages. Stack overflow post which helped me a lot.
* https://stackoverflow.com/questions/64270125/ionic5-setting-a-footer-on-all-app-pages-with-a-sharedmodule-and-controlling-it. Stack overflow post which helped me a lot.
* https://gist.github.com/PurpleBooth/109311bb0361f32d87a2. A very complete template for README.md files.