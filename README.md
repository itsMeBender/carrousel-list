# \<carrousel-list\>

An animated vertical rotating list of items. It's part of my bigger project 'magic mirror'. 
Just to show some movement to mimic some activity on screen.  

If you have a list of 'm' items to show, but you have only room for 'n' items. 
Then this element based on Polymer ^1.0.0 will handle that for you.  
Carrousel items are nicely animated every 's' seconds, to show you a new item from the list.

```
<carrousel-list show="2" seconds="10">
    <carrousel-list-item>Hi, this is the first item</carrousel-list-item>
    <carrousel-list-item><p>This is a next one</p></carrousel-list-item>
    <carrousel-list-item><img src="my-image.png" width="64" height="64"></carrousel-list-item>
    <carrousel-list-item><div><span>Another</span> <span>one</span></div></carrousel-list-item>
</carrousel-list>
```


# Build with Polymer 1

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

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

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
