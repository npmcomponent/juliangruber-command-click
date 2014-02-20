*This repository is a mirror of the [component](http://component.io) module [juliangruber/command-click](http://github.com/juliangruber/command-click). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/juliangruber-command-click`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# command-click

  Make links in a text command-click-able.

## Example

```js
var clickable = require('command-click');
var el = document.querySelector('p');

clickable(p);
```

## Installation

  Install with [component(1)](http://component.io):

    $ component install juliangruber/command-click

## API

### clickable(el)

  Wrap each link inside `el` in a `<span>` and on `CMD+Click` open it in a new tab/window.

  Returns the `unbind` function.

### unbind()

  Stop listening for events.

## License

  MIT
