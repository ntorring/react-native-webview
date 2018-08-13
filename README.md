# Infinite Red WebView - a Modern, Cross-Platform WebView for React Native

**Infinite Red WebView** is a modern, well-supported, and cross-platform (even Windows!) WebView for React Native. It is intended to be a replacement for the built-in WebView (which may be [removed from core](https://github.com/react-native-community/discussions-and-proposals/pull/3)).

## Platforms Supported

* [x] iOS
* [x] Android
* [ ] Windows 10 (coming soon)

## Installation

```
$ npm install --save ir-webview
$ react-native link ir-webview
```

## Usage

Import the `WebView` component from `ir-webview` and use it like so:

```jsx
import React, { Component } from 'react'
import { StyleSheet, Text, View } from 'react-native'
import { WebView } from 'ir-webview'

// ...
class MyWebComponent extends Component {
  render () {
    return (
      <WebView
        src={{uri: "https://infinite.red"}}
        style={{marginTop: 20}}
      />
    )
  }
}
```

Additional properties are supported and will be added here; for now, refer to the previous React Native WebView documentation for more.

[https://facebook.github.io/react-native/docs/webview](https://facebook.github.io/react-native/docs/webview)

## Migrate from React Native core WebView to Infinite Red WebView

Simply install Infinite Red WebView and then use it in place of the core WebView. Their APIs are currently identical.

## Contributing

_Guide coming soon_

## Maintainers

* [Jamon Holmgren](https://github.com/jamonholmgren) ([Twitter](https://twitter.com/jamonholmgren)) from [Infinite Red](https://infinite.red/react-native)

## License

MIT