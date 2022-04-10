---
layout: post
---

# Javascript COMPLETE course

This is a slightly (i.e completely) different javascript course that you guys used to find online. I will try to give you an in-depth introduction to every element regarding the javascript language, standard, libraries and so on.

[A brief history of JavaScript](https://medium.com/@_benaston/lesson-1a-the-history-of-javascript-8c1ce3bffb17)

## ECMAScript
It is a JavaScript standard to ensure the interoperability of web pages across different web browsers? 

- How does this standard influence the development of web browsers?
- Are all JavaScript libraries standards-compliant? How to be sure you create modules, plugins, libraries and packages that are standard-compliant?

## CommonJs
## NodeJs
- An open-source backend javascript runtime environment.
- Event-driven architecture

## The JavaScript Engine
- V8 engine
   - Google Chrome
   - Couchbase
   - Deno
   - Electron
   - MarkLogic
   - NativeScript
   - Node.js
   - Qt Quick
- ECMAScript engine
- WebAssembly

### Difference between Webpack and Babel
Babel basically transforms your ES6+ code into ES5 friendly code. Why would we need to do that? Because there are a lot of browser that do not support newer versions of the ECMAScript standard yet. In the other hand, Webpack is a bundler, i.e, it locates all the javascript modules and other external and vendor files and then groups them in bundles to be included in the html scripts. When the code is split in this way, it allows to load parts of the application on demand. Using *loaders*, Webpack can use modules such as CommonJs, AMD, ES6 modules, CSS, images, JSON, Coffeescript, LESS.

- Babel is a JavaScript compiler
- Webpack is a JavaScript build tool and JavaScrip task runner