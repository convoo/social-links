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

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="social-links.html">
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
<twitter-link href="https://www.twitter.com/@bkawk" height="15px"></twitter-link>
<vimeo-link href="https://www.vimeo.com/@bkawk" height="15px"></vimeo-link>
<skype-link href="https://www.skype.com/@bkawk" height="15px"></skype-link>
<youtube-link href="https://www.youtube.com/@bkawk" height="15px"></youtube-link>
<linkedin-link href="https://www.linkedin.com/@bkawk" height="15px"></linkedin-link>
<behance-link href="https://www.behance.com/@bkawk" height="15px"></behance-link>
<pinterest-link href="https://www.pinterest.com/@bkawk" height="15px"></pinterest-link>
<facebook-link href="https://www.facebook.com/@bkawk" height="15px"></facebook-link>
<convoo-link href="https://www.convoo.me/@bkawk" height="15px"></convoo-link>
<snapchat-link href="https://www.snapchat.com/@bkawk" height="15px"></snapchat-link>
<github-link href="https://www.github.com/@bkawk" height="15px"></github-link>
<instagram-link href="https://www.instagram.com/@bkawk" height="15px"></instagram-link>
<dribbble-link href="https://www.dribbble.com/@bkawk" height="15px"></dribbble-link>
```

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
