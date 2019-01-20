[![npm](https://img.shields.io/npm/v/absurdum.svg)](https://www.npmjs.com/package/absurdum)
[![Build Status](https://gitlab.com/evanplaice/absurdum/badges/master/build.svg)](https://gitlab.com/evanplaice/absurdum/pipelines)

# Absurdum

## Why the Funky Name?

It's a play on the latin phrase [Reductio ad absurdum][wikipedia]

> In logic, reductio ad absurdum (Latin for "reduction to absurdity"; or argumentum ad absurdum, "argument to absurdity") is a form of argument which attempts either to disprove a statement by showing it inevitably leads to a ridiculous, absurd, or impractical conclusion, or to prove one by showing that if it were not true, the result would be absurd or impossible.

It is often said that of the big trio **Map**, **Filter**, and **Reduce**, that reduce is by far the most flexible. In fact, it's trivial to implement both map and filter using reduce.

This library exists to take that concept to an absurd extreme by experimenting with leveraging reduce to produce as many different types functional transforms as possible.

## What's the Point?

Who cares, it's fun. It's good practice. It's a challenging approach to practice transforming data in a purely function manner. At some point, Javscript will include the pipeline operator and these may actually become useful. If you're up for the challenge give it a try.

## Operator(s) Documentation

### [Arrays][arrays]

- [filter][arr-filter]
- [map][arr-map]
- [reverse][arr-reverse]
- [tap][arr-tap]

[arrays]: ./docs/arrays.md
[arr-filter]: ./docs/arrays.md#arraysfilterarray-predicate
[arr-map]: ./docs/arrays.md#arraysmaparray-func
[arr-reverse]: ./docs/arrays.md#arraysreversearray
[arr-tap]: ./docs/arrays.md#arraystaparray-func

### [Objects][objects]

[objects]: ./docs/objects.md

### [Strings][strings]

- [endsWith][str-endswith]
- [startsWith][str-startswith]

[strings]: ./docs/strings.md
[str-endswith]: ./docs/strings.md#stringsendswithstring-substr
[str-startswith]: ./docs/strings.md#stringsstartswithstring-substr

### [HTML][html]

[html]: ./docs/html.md

[wikipedia]: https://en.wikipedia.org/wiki/Reductio_ad_absurdum
[operator]: https://github.com/evanplaice/absurdum/issues/new?title=Operator([operator])&template=OPERATOR_TEMPLATE.md&labels=enhancement,operator
[type]: https://github.com/evanplaice/absurdum/issues/new?title=Type([typ])&template=TYPE_TEMPLATE.md&labels=enhancement,type
[feature-workflow]:https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow
