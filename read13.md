### HTML5 Storage
it’s a way for web pages to store named key/value pairs locally, within the client web browser

the data we stored persists even after you navigate away from the web site and its never transmitted to the remote web server

### Access the HTML5 Storage
first we should detect if the browser support it or not using : ``` function supports_html5_storage() { try { return 'localStorage' in window && window['localStorage'] !== null; } catch (e) { return false; } }
methods can be used in database
'setItem(“key”,”value”)'
'removeItem(“key”)'
'getItem(“key”)'
'clear()'
### data type supported

strings

Booleans

integers

floats

Forms

### Action attribute
The action attribute defines where the data gets sent.

### Method attribute
The method attribute defines how data is sent.