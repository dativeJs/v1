![Logo](public/logo.svg)

# **DativeJs - A Micro JavaScript Ui Framework**

![License](https://img.shields.io/github/license/Tobithedev/dativejs?style=plastic)

![size](https://img.shields.io/github/size/Tobithedev/dativejs/dist/dative.min.js.svg)
![Downloads](https://img.shields.io/jsdelivr/gh/hm/dativeJs/dativejs)

### Installation
### Download
```html 
<script src="path/to/dative.min.js"></script>
```
### CDN
```html
<!--Development-->
<script src="https://cdn.jsdelivr.net/gh/Tobithedev/dativejs@main/dist/dative.js"></script>
<!--Production-->
<script src="https://cdn.jsdelivr.net/gh/Tobithedev/dativejs@main/dist/dative.min.js"></script>
```
## Clone The Template
```bash
 git clone https://github.com/Tobithedev/dative-template.git
```
## EsModule
```js
import Dative from "https://cdn.jsdelivr.net/gh/Tobithedev/dativejs@main/dist/dative.es.min.js";
```
<!--## Npm
```bash
  npm install dative
```
### Usage
```js
import Dative from 'dative';
```-->
## Get Started

```html
<body>
  <div id="app"></div>
  <script src="https://cdn.jsdelivr.net/gh/Tobithedev/dativejs@main/dist/dative.min.js"></script>
  <script>
    // Code goes here
  </script>
</body>
```

```html
<body>
  <div id="app"></div>
  <script src="https://cdn.jsdelivr.net/gh/Tobithedev/dativejs@main/dist/dative.min.js"></script>
  <script>
    var vm = new Dative({
      el: "#app",
      data:{
        msg: "Hello World"
      },
      template(){
        return `
          <h1 :text="msg"></h1>
        `;
      }
    });
    vm.render()
  </script>
  </body>
```
