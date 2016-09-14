# DEPRECATED

This repo is no longer required, nor is stemcell-sha1s.starkandwayne.com. https://bosh.io now
has sha1s for all stemcells being reported in.

As of 1900 UTC on Sept 14th, 2016, this repo and the associated website have stopped being updated.

# What was this?

This repo is a CI Pipeline + CF app that translates md5sums of stemcells to sha1s.

How to use it?

`curl http://stemcell-sha1s.starkandwayne.com/<stemcell-name>/<stemcell-version>`

Stemcell names are based of of the name of the tgz linked to by https://bosh.io/stemcells
