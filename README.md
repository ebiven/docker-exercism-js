# About

This container will have the items necessary to run the tests for the
[Exercism.io](http://exercism.io/languages) JS, ECMAScript, and
CoffeeScript tracks.

# Using this container

In your .bashrc, .zshrc, or similar file include aliases for the
following commands:

```
alias node='docker run -it --rm -v "$PWD":"$PWD" -w "$PWD" ebiven/exercism-js node'
alias npm='docker run -it --rm -v "$PWD":"$PWD" -w "$PWD" ebiven/exercism-js npm'
alias bower='docker run -it --rm -v "$PWD":"$PWD" -w "$PWD" ebiven/exercism-js bower'
alias gulp='docker run -it --rm -v "$PWD":"$PWD" -w "$PWD" ebiven/exercism-js gulp'
alias coffee='docker run -it --rm -v "$PWD":"$PWD" -w "$PWD" ebiven/exercism-js coffee'
alias jasmine-node='docker run -it --rm -v "$PWD":"$PWD" -w "$PWD" ebiven/exercism-js jasmine-node'
```
