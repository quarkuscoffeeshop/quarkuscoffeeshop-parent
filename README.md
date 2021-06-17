***NOTE***: This repository is deprecated

# Docs
Please see the Github Pages Site for complete documentation: [quarkuscoffeeshop.github.io](https://quarkuscoffeeshop.github.io)


# Parent

This project is the parent project for the Quarkuscoffeeshop Demo project.  It contains dependencies for the child projects:
* quarkuscoffeeshop-barista
* quarkuscoffeeshop-counter
* quarkuscoffeeshop-customermocker
* quarkuscoffeeshop-domain
* quarkuscoffeeshop-inventory
* quarkuscoffeeshop-kitchen
* quarkuscoffeeshop-testutils
* quarkuscoffeeshop-web

## Building

This pom can be installed to Maven Central with the following commands:

```shell script
export GPG_TTY=$(tty)
mvn deploy -P sonatype
```

_NOTE_: 
