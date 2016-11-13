[js-heapq](http://aureooms.github.io/js-heapq)
==

Python's heap and priority queue library for JavaScript. Parent is
[js-data-structures](https://github.com/aureooms/js-data-structures).


```js
let {
	heapify ,
	heappop ,
	heappush ,
	heappushpop ,
	heapreplace ,
	merge ,
	nlargest ,
	nsmallest ,
} = heapq ;
```

[![NPM license](http://img.shields.io/npm/l/aureooms-js-heapq.svg?style=flat)](https://raw.githubusercontent.com/aureooms/js-heapq/master/LICENSE)
[![NPM version](http://img.shields.io/npm/v/aureooms-js-heapq.svg?style=flat)](https://www.npmjs.org/package/aureooms-js-heapq)
[![Build Status](http://img.shields.io/travis/aureooms/js-heapq.svg?style=flat)](https://travis-ci.org/aureooms/js-heapq)
[![Coverage Status](http://img.shields.io/coveralls/aureooms/js-heapq.svg?style=flat)](https://coveralls.io/r/aureooms/js-heapq)
[![Dependencies Status](http://img.shields.io/david/aureooms/js-heapq.svg?style=flat)](https://david-dm.org/aureooms/js-heapq#info=dependencies)
[![devDependencies Status](http://img.shields.io/david/dev/aureooms/js-heapq.svg?style=flat)](https://david-dm.org/aureooms/js-heapq#info=devDependencies)
[![Code Climate](http://img.shields.io/codeclimate/github/aureooms/js-heapq.svg?style=flat)](https://codeclimate.com/github/aureooms/js-heapq)
[![NPM downloads per month](http://img.shields.io/npm/dm/aureooms-js-heapq.svg?style=flat)](https://www.npmjs.org/package/aureooms-js-heapq)
[![GitHub issues](http://img.shields.io/github/issues/aureooms/js-heapq.svg?style=flat)](https://github.com/aureooms/js-heapq/issues)
[![Documentation](https://aureooms.github.io/js-heapq/badge.svg)](https://aureooms.github.io/js-heapq/source.html)

## Changes w.r.t. Python's API

```js
let array = [ 2 , 1 , 3 ] ;
let heap = heapq.heapify( compare.increasing , array ) ;
array[0] ; // 1
heapq.heappop( heap ) ; // 1
heapq.heappop( heap ) ; // 2
heapq.heappop( heap ) ; // 3
array.length ; // 0
```

## References

  - [Python's heapq library](https://docs.python.org/3.6/library/heapq.html).
