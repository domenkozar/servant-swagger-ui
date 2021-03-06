# servant-swagger-ui

> Servant support for yaml

[![Build Status](https://travis-ci.org/phadej/servant-swagger-ui.svg?branch=master)](https://travis-ci.org/phadej/servant-swagger-ui)
[![Hackage](https://img.shields.io/hackage/v/servant-swagger-ui.svg)](http://hackage.haskell.org/package/servant-swagger-ui)
[![Stackage LTS 5](http://stackage.org/package/servant-swagger-ui/badge/lts-5)](http://stackage.org/lts-5/package/servant-swagger-ui)
[![Stackage Nightly](http://stackage.org/package/servant-swagger-ui/badge/nightly)](http://stackage.org/nightly/package/servant-swagger-ui)

## Example

![example screenshot](https://raw.githubusercontent.com/phadej/servant-swagger-ui/master/screenshot.png)

Check [`example/Main.hs`](https://github.com/phadej/servant-swagger-ui/blob/master/example/Main.hs) for an example.

## Development

### Updating of bundled swagger-ui version:

- Extract `dist` directory of `swagger-ui` into `swagger-dist-&lt;version&gt;`
- move `index.html` into `index.html.tmpl`, do the diff, port the changes
- search replace the embbeded directory (in `Servant/Swagger/UI.hs`)
- test it works
