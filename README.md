# ES6 modules Hello World

A minimal app that uses modules as defined in ES6. 

As with all Hello Worlds it does very litte other than give you something to follow to get started with your own apps. 

### Notes

* You can only invoke modules from other modules. So any code in your JavaScript app that builds on modules, which would seem to be all of it, has to be contained in a module. 

* To make something  a module you just have to include it with a &lt;script> element with a type attribute of "module".

* The first thing code.js does is import secsSince from module.js. You must refer to module.js as "./module.js" -- it won't work if you refer to it as "module.js".

* The second thing code.js does is call secsSince in module.js and use it in a message that it displays in the HTML code. 

* If you want to run the code yourself, you'll have to upload it to a server. Modules can't be loaded from local files. 

* There was a <a href="https://github.com/scripting/Scripting-News/issues/189">thread</a> in the Scripting News repo on the topic of this app.

* To run the code without downloading, <a href="http://scripting.com/code/moduleshello/">click here</a>.

### Links

* <a href="https://javascript.info/modules-intro">Modules, introduction</a>.

* <a href="https://github.com/mdn/js-examples/tree/master/modules">JavaScript module examples</a>.

* <a href="https://blog.vanila.io/es6-modules-ccd896b50d22">ES6 Modules</a>.

* <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules">JavaScript modules</a>.

### Blog post

* Dave's <a href="http://scripting.com/2020/09/29.html#a160251">blog post</a> on this project.

