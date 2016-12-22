# Social-Links

<p align="center">
  <img alt="social-links" src="SocialLinks400.png" width="200">
</p>

<p align="center">
Simple way to add links to social networks with their logos.
</p>

<p align="center">
  <a href="https://beta.webcomponents.org/element/convoo/social-links"><img src="https://img.shields.io/badge/webcomponents.org-published-blue.svg"></a>
  <a href="https://gitter.im/convoo/general"><img src="https://img.shields.io/badge/gitter-join%20chat-brightgreen.svg"></a>
</p>

---

## Install

```
bower install convoo/social-links --save
```


# \<social-link\>

You can import and use `<social-link>` and then enter the network you want to use.
Or you can import the specific network's link only and use that.

In some cases, you may want to pass the network name as a variable - that's why we built `<social-link>`.

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="social-link.html">
    <div>
      <template is="dom-bind">
        <next-code-block></next-code-block>
      </template>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<social-link network="twitter" href="https://www.twitter.com/@bkawk" height="15px" color="grey"></social-link>
<br><br>
<twitter-link href="https://www.twitter.com/@bkawk" height="15px" color="grey"></twitter-link>
```

Currently available networks are:

* behance
* convoo
* dribbble
* email
* facebook
* github
* instagram
* linkedin
* pinterest
* skype
* snapchat
* twitter
* vimeo
* youtube

## Contributing

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### Viewing Your Application

```
$ polymer serve
```

### Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
