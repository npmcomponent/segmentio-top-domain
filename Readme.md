*This repository is a mirror of the [component](http://component.io) module [segmentio/top-domain](http://github.com/segmentio/top-domain). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-top-domain`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# top-domain

  Makes a reasonable guess at the 'top' domain for a url, useful for cookie-ing.

## Installation

    $ component install segmentio/top-domain

## API

```
var topDomain = require('top-domain');

topDomain('http://www.google.co.uk/some_other_path#good') // 'google.co.uk'
```
   

## License

  MIT
