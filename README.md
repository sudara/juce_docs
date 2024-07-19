# JUCE DOCS

## Goals

* Maintains URL compatibility with docs.juce.com
* Should not break due to GitHub Actions updating images, packages, etc
* Should have as little custom setup as possible. No magic incantations in scripts. As close to vanilla Doxygen as possible.


## Building locally on macOS

```
brew install graphviz doxygen
doxygen Doxyfile
```
