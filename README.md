# What is this?

This repo is a CI Pipeline + CF app that translates md5sums of stemcells to sha1s.

How to use it?

`curl http://stemcell-sha1s.starkandwayne.com/<stemcell-name>/<stemcell-version>`

Stemcell names are based of of the name of the tgz linked to by https://bosh.io/stemcells
