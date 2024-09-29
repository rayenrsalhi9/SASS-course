* when compiling :
=>  css file doesn't contain the variable name: it contains its value
(instead of '$main_color' we find '#111111')

* there are global variables & local variables
(like in javacript & css)

* when re-declaring a global variable inside a selector with another value, and you want the next selectors to take this changed value instead of the global value
=>  add '!global' after the local variable

* to use variables when import :
=>  @use './variables-file/colors' as *;
=>  colors.$main_color (like in objects in JS)

* we can use variables in media queries too