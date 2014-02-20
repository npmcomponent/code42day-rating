*This repository is a mirror of the [component](http://component.io) module [code42day/rating](http://github.com/code42day/rating). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/code42day-rating`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# rating

  Read-only numeric rating (0-100) displayed as stars.
  Click [here](http://code42day.github.com/rating) to see the example.

## Installation

    $ component install code42day/rating

## API

### rating(el, value)

Add rating component to `el` and display the `value`


### rating(el, options)

options is an object that allows specifying alternative star character and/or initial value

````javascript
var rating = require('rating');

// use ★ and initial value 25
rating(parent, 25);

// use ❤ and initial value 50
rating(parent, {
  value: 50,
  star: '&#x2764;'  // ❤
});
````

### rating.set(value)

Change the `value` of existing rating.


## License

  MIT
