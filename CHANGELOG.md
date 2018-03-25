<a name="2.0.0"></a>
# [2.0.0](https://github.com/troch/search-params/compare/v1.3.0...v2.0.0) (2018-03-19)


### Code Refactoring

* major library refactor ([5b53d09](https://github.com/troch/search-params/commit/5b53d09))


### BREAKING CHANGES

* do NOT upgrade to version 2.x.x if you use router5@5.x.x, route-node@2.x.x or path-parser@3.x.x
* 'toObject' method has been removed
* 'parse' now returns an object of parameters rather than a list
* 'build' now takes an object of parameters rather than a list
* 'omit' now returns an object with 'removedParams' and 'querystring'
* 'getSearch' and `withoutBrackets` methods have been removed



<a name="1.3.0"></a>
# [1.3.0](https://github.com/troch/search-params/compare/v1.2.0...v1.3.0) (2016-09-09)


### Bug Fixes

* don't serialize undefined or null parameter, handle parsing and building true values ([41d700a](https://github.com/troch/search-params/commit/41d700a))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/troch/search-params/compare/v1.1.0...v1.2.0) (2016-03-29)



<a name="1.1.0"></a>
# [1.1.0](https://github.com/troch/search-params/compare/v1.0.0...v1.1.0) (2016-02-22)


### Features

* export hasBrackets and withoutBrackets functions ([84a5f0b](https://github.com/troch/search-params/commit/84a5f0b))



<a name="1.0.0"></a>
# [1.0.0](https://github.com/troch/search-params/compare/584f20d...v1.0.0) (2016-02-20)


### Features

* add parse, build and omit functions ([584f20d](https://github.com/troch/search-params/commit/584f20d))
* add toObject function and add tests ([15bea67](https://github.com/troch/search-params/commit/15bea67))


