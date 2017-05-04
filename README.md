[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/itsMeBender/carrousel-list)

# A carrousel of vertical rotating elements

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="carrousel-list.html">
    <link rel="import" href="carrousel-list-item.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<carrousel-list show="3" seconds="5">
<carrousel-list-item>This is a list of 6 elements (rows)</carrousel-list-item>
<carrousel-list-item>Only three are displayed</carrousel-list-item>
<carrousel-list-item>The list scrolls down</carrousel-list-item>
<carrousel-list-item><img src="demo/bender.png" alt="bender" width="64" height="64"></carrousel-list-item>
<carrousel-list-item>A new row appears on top</carrousel-list-item>
<carrousel-list-item>The last of the list fades away</carrousel-list-item>
</carrousel-list>
```

# Introduction

An animated rotating vertical list of items. It's part of my bigger project 'magic mirror'. 
Just to show some movement to mimic some activity on screen.  

If you have a list of 'm' items to show, but you have only room for 'n' items. 
Then this element will handle that for you.  
Carrousel items are nicely animated every 's' seconds, to show you a new item from the list.

# Specifications

* Animate a vertical list of elements by rotating the content in a loop.
* Allow full control of the content and lay-out of the list-elements.
* Control the number of visible elements.
* Control the interval of element refreshment.
