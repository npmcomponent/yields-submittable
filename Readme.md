*This repository is a mirror of the [component](http://component.io) module [yields/submittable](http://github.com/yields/submittable). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-submittable`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# submittable

  check if the given form element is submittable.

## Installation

  Install with [component(1)](http://component.io):

    $ component install yields/submittable

## Example

```js
submittable('<input type="text" name="baz">'); // > true
submittable('<select></select>'); // > false
submittable('<input type="checkbox" name="baz" checked>'); // > true
submittable('<input type="submit" name="foo">'); // > false
```

## License

  MIT
