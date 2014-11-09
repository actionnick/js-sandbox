js-sandbox
==========

JS sandbox with modern JS features for client side prototyping. Comes with [browserify](http://browserify.org/), [react](http://facebook.github.io/react/), [es6ify](https://github.com/thlorenz/es6ify), and more. Structured to allow rapid prototyping for JS heavy applications.

### Up and Running
js-sandbox comes with express js web server with live reload. This allows you to have your browser automatically refresh when you make changes to your code. Great for rapid prototyping. Follow these steps to get js-sandbox up and running. 

- Make sure you have [node](http://nodejs.org/) installed.
- Download the [livereload](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en) chrome extension.
- Download and unpack zip file from the [`builds`](https://github.com/nschaubeck/js-sandbox/tree/master/builds) directory.
- Run `npm install`.
- Run `grunt web` to bring up a webserver with livereload enabled.
- Enable livereload from the browser by clicking on the extension icon ![click livereload](https://www.evernote.com/shard/s351/sh/46fdd789-342b-4238-928c-b58c292d0210/383ebe016a88053393f415c751f8f4f0/deep/0/New-File.png)
- Edit the alert in `js/frontend/example/main.js` to see livereload in action!
