#Front-end Job Interview Questions

This file contains a number of front-end interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

**Note:** Keep in mind that many of these questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

## Table of Contents

  1. [General Questions](#general-questions)
  1. [HTML Questions](#html-questions)
  1. [CSS Questions](#css-questions)
  1. [JS Questions](#js-questions)
  1. [Testing Questions](#testing-questions)
  1. [Performance Questions](#performance-questions)
  1. [Network Questions](#network-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)

## Getting Involved

  1. [Contributors](#contributors)
  1. [How to Contribute](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/LICENSE.md)

#### General Questions:

* What did you learn yesterday/this week?
* What excites or interests you about coding?
* What is a recent technical challenge you experienced and how did you solve it?
* **What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?**
* Talk about your preferred development environment.
* **Which version control systems are you familiar with?**
* Can you describe your workflow when you create a web page?
* **If you have 5 different stylesheets, how would you best integrate them into the site?** (研究Async loading)
* **Can you describe the difference between progressive enhancement and graceful degradation?** [Info](http://augus-blog.logdown.com/posts/143403-graceful_degradation_and_progressive_enhancement)
* How would you optimize a website's assets/resources?
* **How many resources will a browser download from a given domain at a time?**
  * What are the exceptions?
* Name 3 ways to decrease page load (perceived or actual load time).
* If you jumped on a project and they used tabs and you used spaces, what would you do?
* Describe how you would create a simple slideshow page.
* If you could master one technology this year, what would it be?
* **Explain the importance of standards and standards bodies.**
* What is Flash of Unstyled Content? How do you avoid FOUC?
* **Explain what ARIA and screenreaders are, and how to make a website accessible.**
* Explain some of the pros and cons for CSS animations versus JavaScript animations.
* **What does CORS stand for and what issue does it address?** ([Same Origin Policy](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Same_origin_policy_for_JavaScript), [JSONP](http://stackoverflow.com/questions/2067472/what-is-jsonp-all-about), [CORS](https://developer.mozilla.org/zh-TW/docs/HTTP/Access_control_CORS))

#### HTML Questions:
* [看H5BP的Documentation了解他的做法](https://github.com/h5bp/html5-boilerplate/blob/master/dist/doc/TOC.md)
* [The Open Graph porotocol](http://ogp.me/)
* What does a `doctype` do? ([What is doctype?](http://stackoverflow.com/questions/414891/what-is-doctype))
* What's the difference between standards mode and quirks mode? ([Quirks Mode and Standards Mode](https://developer.mozilla.org/en-US/docs/Quirks_Mode_and_Standards_Mode))
* What's the difference between HTML and XHTML? ([Differences Between HTML and XHTML](http://www.sitepoint.com/web-foundations/differences-html-xhtml/))
* Are there any problems with serving pages as `application/xhtml+xml`?
* How do you serve a page with content in multiple languages? 
* What kind of things must you be wary of when design or developing for multilingual sites? [Link](https://www.quora.com/What-kind-of-things-one-should-be-wary-of-when-designing-or-developing-for-multilingual-sites/answer/Ted-Goas?srid=pmde)
* What are `data-` attributes good for?
* Consider HTML5 as an open web platform. What are the building blocks of HTML5?
* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
* Describe the difference between `<script>`, `<script async>` and `<script defer>`. [Link](http://peter.sh/experiments/asynchronous-and-deferred-javascript-execution-explained/)
* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions? Exception: [Modernizr](http://stackoverflow.com/questions/6272702/should-modernizr-file-be-placed-in-head)
* What is progressive rendering? [Link](http://stackoverflow.com/questions/33651166/what-is-progressive-rendering)
* Have you used different HTML templating languages before? [Handlebar](http://handlebarsjs.com/), [Liquid](http://liquidmarkup.org/)

#### CSS Questions:

* What is the difference between classes and ID's in CSS?
* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
* Describe Floats and how they work.
* **Describe z-index and how stacking context is formed.**
* **Describe BFC(Block Formatting Context) and how it works.*  [Link](http://www.sitepoint.com/understanding-block-formatting-contexts-in-css/)*
* What are the various clearing techniques and which is appropriate for what context?
* Explain CSS sprites, and how you would implement them on a page or site.
* What are your favourite image replacement techniques and which do you use when? [Link](https://css-tricks.com/the-image-replacement-museum/)
* **How would you approach fixing browser-specific styling issues?**
* How do you serve your pages for feature-constrained browsers?
  * What techniques/processes do you use?
* **What are the different ways to visually hide content (and make it available only for screen readers)?**[Link](https://css-tricks.com/places-its-tempting-to-use-display-none-but-dont/)
* Have you ever used a grid system, and if so, what do you prefer?
* Have you used or implemented media queries or mobile specific layouts/CSS?
* **Are you familiar with styling SVG?**
* **How do you optimize your webpages for print?**
* What are some of the "gotchas" for writing efficient CSS?
* What are the advantages/disadvantages of using CSS preprocessors?
  * Describe what you like and dislike about the CSS preprocessors you have used.
* **How would you implement a web design comp that uses non-standard fonts?**
* Explain how a browser determines what elements match a CSS selector.
* Describe pseudo-elements and discuss what they are used for. 
* **Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.**
* What does ```* { box-sizing: border-box; }``` do? What are its advantages?
* List as many values for the display property that you can remember.
* What's the difference between inline and inline-block?[Link](http://stackoverflow.com/questions/9189810/css-display-inline-vs-inline-block)
* What's the difference between a relative, fixed, absolute and statically positioned element?
* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage?
* What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
* Have you played around with the new CSS Flexbox or Grid specs?
* **How is responsive design different from adaptive design? [Link](http://thenextweb.com/dd/2015/09/01/is-adaptive-better-than-responsive-design/)**

> “Responsive design is client-side, meaning the whole page is delivered to the device browser (the client), and the browser then changes how the page appears in relation to the dimensions of the browser window.

> “Adaptive design is server-side, meaning before the page is even delivered, the server (where the site is hosted) detects the attributes of the device, and loads a version of the site that is optimized for its dimensions and native features.”

* Have you ever worked with retina graphics? If so, when and what techniques did you use? (<img srcset> or <picture>)
* Is there any reason you'd want to use `translate()` instead of *absolute positioning*, or vice-versa? And why?

#### JS Questions:

* **Explain event delegation**
* Explain how `this` works in JavaScript
* Explain how prototypal inheritance works
* What do you think of AMD vs CommonJS?
* Explain why the following doesn't work as an IIFE: `function foo(){ }();`.
  * What needs to be changed to properly make it an IIFE?
* What's the difference between a variable that is: `null`, `undefined` or undeclared?
  * How would you go about checking for any of these states?
  * null: `if (aVar === null)`
  * undefined: `if (aVar === undefined)` or `if (typeof aVar === 'undefined')`
* What is a closure, and how/why would you use one?
  * 應用: Data Privacy, Partial applying function, Curry...
* What's a typical use case for anonymous functions?
* **How do you organize your code? (module pattern, classical inheritance?)**
* **What's the difference between host objects and native objects?** [Link](http://stackoverflow.com/questions/7614317/what-is-the-difference-between-native-objects-and-host-objects)
  * Native: 語言內件的物件，如:Math, Array, Date...
  * Host: 根據執行環境而被定義的:如:document(DOM), history(BOM), console...
* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
* What's the difference between `.call` and `.apply`?
* Explain `Function.prototype.bind`.
* When would you use `document.write()`

```html
<script src="https://code.jquery.com/jquery-1.12.1.min.js"></script>
<script>window.jQuery || document.write('<script src="js/vendor/jquery-1.12.1.min.js"><\/script>')</script>
```

* What's the difference between feature detection, feature inference, and using the UA string? [Link](http://stackoverflow.com/questions/20104930/whats-the-difference-between-feature-detection-feature-inference-and-using-th)
* **Explain AJAX in as much detail as possible.**
* Explain how JSONP works (and how it's not really AJAX).
* Have you ever used JavaScript templating?
  * If so, what libraries have you used?
* Explain "hoisting".
* Describe event bubbling.
* What's the difference between an "attribute" and a "property"? [Link](http://stackoverflow.com/questions/258469/what-is-the-difference-between-attribute-and-property)
* Why is extending built-in JavaScript objects not a good idea?
* Difference between document load event and document ready event?
* What is the difference between `==` and `===`?
* Explain the same-origin policy with regards to JavaScript.
* Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```
* Why is it called a Ternary expression, what does the word "Ternary" indicate?
* What is `"use strict";`? what are the advantages and disadvantages to using it?
* Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`
* Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
* Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
* **Explain what a single page app is and how to make one SEO-friendly.**
* What is the extent of your experience with Promises and/or their polyfills?
* **What are the pros and cons of using Promises instead of callbacks?**
* What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
* **What tools and techniques do you use debugging JavaScript code?**
* What language constructions do you use for iterating over object properties and array items?
* **Explain the difference between mutable and immutable objects.**
  * What is an example of an immutable object in JavaScript?
  * What are the pros and cons of immutability?
  * How can you achieve immutability in your own code?
* Explain the difference between synchronous and asynchronous functions.
* **What is event loop?**
  * **What is the difference between call stack and task queue?** [Link1](https://www.youtube.com/watch?v=8aGhZQkoFbQ), [Link2](http://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/), [Link3](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop)

#### Testing Questions:

* What are some advantages/disadvantages to testing your code?
* What tools would you use to test your code's functionality?
* What is the difference between a unit test and a functional/integration test?
* What is the purpose of a code style linting tool?

#### Performance Questions:
* What tools would you use to find a performance bug in your code? PageSpeed Insights, DevTool Timeline 
* What are some ways you may improve your website's scrolling performance? throttle, debounce
* **Explain the difference between layout, painting and compositing.** (**之後回來看**)

#### Network Questions:
* **Traditionally, why has it been better to serve site assets from multiple domains?** [Sharding Dominant Domains](http://www.stevesouders.com/blog/2009/05/12/sharding-dominant-domains/), [Domain Sharding revisited](http://www.stevesouders.com/blog/2013/09/05/domain-sharding-revisited/), [SO_160376](http://stackoverflow.com/questions/160376/why-move-your-javascript-files-to-a-different-main-domain-that-you-also-own):通常browser對在同一個hostname可以同時下載的靜態資源數量會有所限制(ex. Chrome=6)，因此將靜態資源分散在不同的domain(ex. a.example.com. b.example.com)可以增加browser平行下載的靜態資源數量，增進效能
* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen. [Link](http://stackoverflow.com/questions/2092527/what-happens-when-you-type-in-a-url-in-browser)
* **What are the differences between Long-Polling, Websockets and Server-Sent Events?** [Link1](http://stackoverflow.com/questions/11077857/what-are-long-polling-websockets-server-sent-events-sse-and-comet) [Link2](http://blogger.gtwang.org/2014/01/websocket-protocol.html)
* Explain the following request and response headers: [Link](http://code.tutsplus.com/tutorials/http-headers-for-dummies--net-8039)
  * Diff. between Expires, Date, Age and If-Modified-...
  * Do Not Track
  * Cache-Control
  * Transfer-Encoding
  * ETag
  * X-Frame-Options
* What are HTTP actions? List all HTTP actions that you know, and explain them. [Link](http://www.tutorialspoint.com/http/http_methods.htm)
  1. GET
  2. HEAD
  3. POST
  4. PUT
  5. DELETE
  6. CONNECTION
  7. OPTIONS
  8. TRACE

#### Coding Questions:

*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```

*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

*Question: What is the value of `window.foo`?*
```javascript
( window.foo || ( window.foo = "bar" ) );
```
--- 20160420 ---
*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

*Question: What is the value of `foo.x`?*
```javascript
var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};
```

*Question: What does the following code print?*
```javascript
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```

#### Fun Questions:

* What's a cool project that you've recently worked on?
* What are some things you like about the developer tools you use?
* Do you have any pet projects? What kind?
* What's your favorite feature of Internet Explorer?
* How do you like your coffee?


#### Contributors:

This document started in 2009 as a collaboration of [@paul_irish](https://twitter.com/paul_irish) [@bentruyman](https://twitter.com/bentruyman) [@cowboy](https://twitter.com/cowboy) [@ajpiano](https://twitter.com/ajpiano)  [@SlexAxton](https://twitter.com/slexaxton) [@boazsender](https://twitter.com/boazsender) [@miketaylr](https://twitter.com/miketaylr) [@vladikoff](https://twitter.com/vladikoff) [@gf3](https://twitter.com/gf3) [@jon_neal](https://twitter.com/jon_neal) [@sambreed](https://twitter.com/sambreed) and [@iansym](https://twitter.com/iansym).

It has since received contributions from over [100 developers](https://github.com/h5bp/Front-end-Developer-Interview-Questions/graphs/contributors).
