# Covfefe
Covfefe is a Python machine learning library that implements exactly one semi-stable API call:

```
dict <- covfefe.analyze(fd)
````
Where _fd_ is a valid file descriptor.

The return value is a _dict_ object containing semantic information on the nature of _fd_.

That's it. Really.**

** Expect that dict to contain the output of many kinds of analysis. Object detection and localization, license plate reading, theme tags, thought vectors, and anything we can cram into a dictionary really.
