# metisMenu [![Build Status](https://secure.travis-ci.org/onokumus/metisMenu.svg?branch=master)](https://travis-ci.org/onokumus/metisMenu)

> A jQuery menu plugin for Bootstrap 3


## Installation

* [npm](http://npmjs.org/)

```bash
npm install metismenu
```

* [Bower](http://bower.io)

```bash
bower install metisMenu
```

* [composer](https://getcomposer.org/)

```bash
composer require onokumus/metismenu:dev-master
```

* [Download](https://github.com/onokumus/metisMenu/archive/master.zip)

## Usage

1. Include Twitter Bootstrap StyleSheet

    ```html
    <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.4/css/bootstrap.min.css">
    ```

2. Include metisMenu StyleSheet

    ```html
    <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/metisMenu/1.1.3/metisMenu.min.css">
    ```

3. Include jQuery

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
    ```

4. Include Twitter Bootstrap Script

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.4/js/bootstrap.min.js"></script>
    ```

5. Include metisMenu plugin's code

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/metisMenu/1.1.3/metisMenu.min.js"></script>
    ```

6. Call the plugin:

    ```javascript
    $("#menu").metisMenu();
    ```

### Options

#### toggle
Type: `Boolean`
Default: `true`

For auto collapse support.

```javascript
  $("#menu").metisMenu({
    toggle: false
  });
```

#### doubleTapToGo
Type: `Boolean`
Default: `false`

For double tap support.

```javascript
  $("#menu").metisMenu({
    doubleTapToGo: true
  });
```


### [DEMO](http://demo.onokumus.com/metisMenu/)

Contains a simple HTML file to demonstrate metisMenu plugin.

### Release History
**DATE**       **VERSION**   **CHANGES**
* 2015-03-24   v1.1.3        composer support
* 2014-11-01   v1.1.3        Bootstrap 3.3.0
* 2014-07-07   v1.1.0	     Add double tap functionality
* 2014-06-24   v1.0.3	     cdnjs support & rename plugin
* 2014-06-18   v1.0.3        Create grunt task
* 2014-06-10   v1.0.2        Fixed for IE8 & IE9


## Author

metisMenu was made with love by these guys and a bunch of awesome [contributors](https://github.com/onokumus/metisMenu/graphs/contributors).

[![Osman Nuri Okumuş](https://0.gravatar.com/avatar/4fa374411129d6f574c33e4753ec402e?s=70)](http://onokumus.com) |
--- | --- | --- | --- | --- | --- | ---
[Osman Nuri Okumuş](http://onokumus.com) |


## License

[MIT License](https://github.com/onokumus/metisMenu/blob/master/LICENSE)
