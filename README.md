# Sort International

Sort an array into an international alphabetical order.

![Travis-CI](https://api.travis-ci.org/rthor/sort-international.png)

## Usage Guide

```sh
$ npm install sort-international
```

Then to work with it:

```javascript
// Require the algorithm
var international = require('sort-international');

// Sort array of strings
myArray.sort( international() );

// Sort array of objects, e.g. with property 'name'
myArray.sort( international('name') );
```

## The MIT License (MIT)

Copyright (c) 2013 Ragnar Þór Valgeirsson (rthor) [http://rthor.is](http://rthor.is)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.