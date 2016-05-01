

# CherryPy

[![Join the chat at https://gitter.im/cherrypy/cherrypy](https://badges.gitter.im/cherrypy/cherrypy.svg)](https://gitter.im/cherrypy/cherrypy?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Welcome to the GitHub-repository of CherryPy! 
[CherryPy](http://cherrypy.org/) is a pythonic, object-oriented HTTP framework.


### Table of contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Help](#help)
    - [I don't understand the documentation](#i-dont-understand-the-documentation)
    - [I have a question](#i-have-a-question)
    - [I have found a bug](#i-have-found-a-bug)
    - [I have a feature request](#i-have-a-feature-request)
    - [I want to discuss CherryPy, reach out to the developers, or other CherryPy users](#i-want-to-discuss-cherrypy-reach-out-to-the-developers-or-other-cherrypy-users)
- [Documentation](#documentation)
- [Installation](#installation)
  - [Pip](#pip)
  - [Source](#source)
- [Development](#development)
  - [Contributing](#contributing)
  - [Testing](#testing)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Help

What are my options if I feel I need help? 

### I don't understand the documentation
While CherryPy is one of the easiest and most intuitive frameworks out there, the prerequisite for understanding the [CherryPy documentation](http://docs.cherrypy.org/en/latest/) is that you have a general understanding of Python and web development.<br />

So if you have that, and still cannot understand the documentation, it is probably not your fault. [Please create an issue](https://github.com/cherrypy/cherrypy/issues/new) in those cases.<br />

### I have a question
If you have a question and cannot find an answer for it in issues or the the [documentation](http://docs.cherrypy.org/en/latest/), [please create an issue](https://github.com/cherrypy/cherrypy/issues/new).<br />
Questions and their answers have great value for the community, and a tip is to really put the effort in and write a good explanation, you will get better and quicker answers. 
Examples are strongly encouraged.

### I have found a bug 
If no one have already, [create an issue](https://github.com/cherrypy/cherrypy/issues/new).
Be sure to provide ample information, remember that any help won't be better than your explanation. 

Unless something is very obviously wrong, you are likely to be asked to provide a working example, displaying the erroneous behaviour.

<i>While this might feel troublesome, a tip is to always make a separate example that have the same external requirements as your project.<br />
<b>It is great for troubleshooting</b> those annoying problems where you don't know if the problem is at your end or the components'.<br />
And you can then easily fork and provide as an example.<br />
You will get answers and resolutions way quicker, also, many other open source projects require it.</i>

### I have a feature request
[Good stuff! Please create an issue!](https://github.com/cherrypy/cherrypy/issues/new)
(features are more likely to be added the more users they seem to benefit)

### I want to discuss CherryPy, reach out to the developers, or other CherryPy users
[The gitter page](https://gitter.im/cherrypy/cherrypy) is good for when you want to talk, but perhaps doesn't feel that the discussion has to be indexed for posterity.

# Documentation

* The official user documentation of CherryPy is at: http://docs.cherrypy.org/en/latest/
* Tutorials are included in the repository: https://github.com/cherrypy/cherrypy/tree/master/cherrypy/tutorial
* A general wiki at(will be moved to github): https://bitbucket.org/cherrypy/cherrypy/wiki/Home 
* Plugins are described at: http://tools.cherrypy.org/

# Installation

To install CherryPy for use in your project, follow these instructions:

## Pip

```sh
pip install cherrypy
```
or (for python 3)
```sh
pip3 install cherrypy
```

## Source

Change to the directory where setup.py is located and type (Python 2.6 or later needed):
```sh
python setup.py install
```

# Development

## Contributing

Please follow the [contribution guidelines](https://github.com/cherrypy/cherrypy/blob/master/CONTRIBUTING.txt).
And by all means, [absorb the Zen of CherryPy](https://bitbucket.org/cherrypy/cherrypy/wiki/ZenOfCherryPy). 

## Testing
* To run the regression tests, just go to the cherrypy/test/ directory
  and type:
```sh
nosetests -s ./
```
* To run individual tests type:
```sh
nosetests -s test_foo.py
```