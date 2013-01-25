# KUATO CLI

Repo for the Kuato command line script, formatted for publishing as an npm module.

`npm install -g kuato`

This package installs the command line script for kuato, which builds a grunt-based static site scaffold. See https://github.com/cemckinley/kuato for scaffold repo and usage.

Node, npm, compass, and grunt need be installed at the global (command line) level to use kuato. NOTE: kuato is built based on the latest stable grunt 0.3.x release, which doesn't use the upcoming 0.4 grunt-cli package with local grunt install. Grunt is assumed to be installed globally, kuato does not create a local version of grunt in your project.

