Try Handlebars.js 
=================

---
[http://www.tryhandlebarsjs.com](http://www.tryhandlebarsjs.com "Try Handlebars in your browser!")

Try Handlebars is a web tool I made to help preview [Handlebars.js](http://www.handlebarsjs.com/) templates easily in the browser. 

This site was built quickly on top of [HTML5 Boilerplate](http://html5boilerplate.com/).

__How does it work?__

All of the example templates and contexts are stored in the index.html file as different script blocks. When you select a template it populates the textareas.
They are eval'd when you click compile and HTML output is displayed in the output textarea. An html preview is also displayed inline but I will probably remove that.

__Contributing__

- Fork the repo
- You need to run npm install, bower install, grunt build, grunt sass
- Do not commit build artifacts (node_modules, components, etc)
- Submit pull request (please rebase your changes into one commit)
