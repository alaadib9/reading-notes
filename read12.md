## EJS partials

Partials come in handy when you want to reuse the same HTML across multiple views. make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in.

In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by '<% %>' delimiters
## Some Notes
define partials files
Including a partial in EJS.use '<%- include( PARTIAL_FILE ) %>'