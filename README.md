jade-browser-runtime
============

A slightly modified version of the jade runtime, for use in the browser. Because the default runtime has node.js calls that break in the browser :(

### The errors look something like this

![screen shot 2013-05-22 at 10 39 58 am](https://f.cloud.github.com/assets/520550/547201/448daf62-c2bb-11e2-885e-c625602c0388.png)



They have the filename, line number, and JS error message, but not the actual template string. (because the template is already compiled)
