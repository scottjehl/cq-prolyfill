# Container Queries Prolyfill

[![Build Status](https://travis-ci.org/ausi/cq-prolyfill.svg?branch=master)](https://travis-ci.org/ausi/cq-prolyfill/branches) [![Coverage Status](https://coveralls.io/repos/ausi/cq-prolyfill/badge.svg?branch=master&service=github)](https://coveralls.io/github/ausi/cq-prolyfill?branch=master)

This is a [prolyfill](https://au.si/what-is-a-prolyfill) for a special version of [container queries](https://github.com/ResponsiveImagesCG/container-queries) (aka element queries). You can read more about the idea and how they work internally in [this article](https://au.si/css-container-element-queries).

## Demo

A quick demo of the container queries in action can be found here:  
<https://ausi.github.io/cq-prolyfill/demo/>

## Usage

With this prolyfill you can use container queries in your CSS in the following form:

```css
.element:container(width >= 100px) {
	/* Styles for .element if its container is at least 100px wide */
}
.element:container(height > 100px < 200px) {
	/* Styles for .element if its container is between 100px and 200px high */
}
.element:container(text-align = right) {
	/* Styles for .element if its container has a right text-align */
}
```

For more information take a look at the [usage documentation](docs/usage.md).

## Documentation

[Read the documentation](docs/index.md) to see how you can install and use this script on your next project.

## Browser Support

* Firefox 36+
* Opera 12.16+
* Chrome 40+
* Internet Explorer 9+
* Edge
* Safari 7+
* Yandex 14+
* iOS 7+
* Android 4+
* Windows Phone 8.1+

Thanks to [BrowserStack](https://www.browserstack.com/automate) for sponsoring automated cross browser testing for this project.

## Contribute

* Create a [new issue on GitHub](https://github.com/ausi/cq-prolyfill/issues/new) if you have a question, a suggestion or found a bug.
* Talk about it on IRC: Join `#cq-prolyfill` on Freenode or [connect with the browser](https://webchat.freenode.net?randomnick=1&channels=%23cq-prolyfill&prompt=1).

## License

MIT
