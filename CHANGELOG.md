## Changelog

### Version 0.2.3
* Fix broken user-agent string in 1.8.7, thanks Sean Porter
* Update outdated spec

### Version 0.2.2
* Fix abstract persistence instantiation in Ruby 1.8/REE

### Version 0.2.1
* Add better handling for start_time and end_time params when fetching measurements

### Version 0.2.0
* Fix bug with stale excon connections not reconnecting
* Add custom User-Agent
* Items added to Queue objects have their measure_time set automatically
* Metric 'type' key can be string or symbol, thanks Neil Mock

### Version 0.1.0
* Initial release