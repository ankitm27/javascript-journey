# javascript-journey

> Companion source code to [Journey from procedural to reactive JavaScript with stops][post]

[![Build status][ci-image] ][ci-url]

Problem: given a list of numbers, multiply each one by a constant
and print the result.

```js
var numbers = [3, 1, 7];
var constant = 2;
// expected output [6, 2, 14]
```

To install and run

    git clone git@github.com:bahmutov/javascript-journey.git
    cd javascript-journey
    npm install

Then execute individual files using `node src/<filename>` command. The following
implementations are available

* [procedural](src/00-procedural.js)
* [procedural with individual functions](src/01-procedural-with-reuse.js)
* [object-oriented](src/02-oo.js)
* [object-oriented using Array methods](src/02-oo-with-array-methods.js)
* [functional](src/03-functional.js)
* [functional using lodash](src/03-functional-with-lodash.js)
* [functional using Ramda](src/03-functional-with-ramda.js)
* [lazy async sequence](src/04-lazy.js)
* [promises in parallel](src/05-promises.js)
* [promises in sequence](src/06-promises-sequence.js)
* [events](src/07-events.js)
* [events with decoupled code](src/08-events-decoupled.js)
* [each step creates new emitter](src/09-step-emitters.js)
* [reactive](src/10-reactive.js)
* [generators](src/11-generators.js)
* [streams](src/12-streams.js)
* [transducers](src/13-transducers.js)

[post]: http://glebbahmutov.com/blog/journey-from-procedural-to-reactive-javascript-with-stops/

### Small print

Author: Gleb Bahmutov &copy; 2015

* [@bahmutov](https://twitter.com/bahmutov)
* [glebbahmutov.com](http://glebbahmutov.com)
* [blog](http://glebbahmutov.com/blog/)

License: MIT - do anything with the code, but don't blame me if it does not work.

Spread the word: tweet, star on github, etc.

Support: if you find any problems with this module, email / tweet /
[open issue](https://github.com/bahmutov/javascript-journey/issues) on Github

## MIT License

Copyright (c) 2015 Gleb Bahmutov

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

[ci-image]: https://travis-ci.org/bahmutov/javascript-journey.png?branch=master
[ci-url]: https://travis-ci.org/bahmutov/javascript-journey
