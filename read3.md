## What Are JavaScript Templates?

JavaScript templates are a method of separating HTML structure from the content contained within. Templating systems generally introduce some new syntax but are usually very simple to work with.

## When Should We Use JavaScript Templates?
As soon as we find ourselves including HTML inside JavaScript strings we should be starting to think about what benefits JavaScript templates could give us. Separation of concerns is of utmost importance when building a maintainable codebase, so anything which can help us achieve this should be explored. In front-end web development this is epitomized when separating HTML from JavaScript.


## mustache.js
Mustache is a multi-language, logic-less templating system. The mustache.js implementation is just one of many. So once we’re used to the (very simple) syntax, we can use it in a variety of programming languages.

### Key Points
9kb file size (small)
Simple
No dependencies
No logic
No precompiled templates
Programming language agnostic


## Basic concepts of flexbox

The Flexible Box Module, usually referred to as flexbox, was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities.

The two axes of flexbox
When working with flexbox you need to think in terms of two axes — the main axis and the cross axis. The main axis is defined by the flex-direction property, and the cross axis runs perpendicular to it.

### The main axis is defined by flex-direction, which has four possible values:

row

row-reverse

column

column-reverse

The flex container
An area of a document laid out using flexbox is called a flex container. To create a flex container, we set the value of the area's container's display property to flex or inline-flex. As soon as we do this the direct children of that container become flex items. As with all properties in CSS, some initial values are defined, so when creating a flex container all of the contained flex items will behave in the following way.

Items display in a row (the flex-direction property's default is row).
The items start from the start edge of the main axis.
The items do not stretch on the main dimension, but can shrink.
The items will stretch to fill the size of the cross axis.
The flex-basis property is set to auto.
The flex-wrap property is set to nowrap.