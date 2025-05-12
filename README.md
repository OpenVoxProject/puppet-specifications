Puppet Specifications
===

This repository contains specifications for [the project Puppet][1], and related technologies.

The goal of this repository is that an independent implementation could follow this specification and fully support any Puppet Modules functional under an existing implementation.

Semantic Versioning
---
The specifications contained in this repository follows semantic versioning with the following semantics:

* The micro version contains corrections, clarifications of the specification. All implementation
  of the specification that are compliant with the same minor version are also compliant with
  all micro versions of the same minor version.
* The minor versions contains changes that are non breaking. But an implementation that
  is compliant with a previous minor versions is not automatically compliant with all future
  minor versions for the same major version.
* The major versions contains changes that are breaking. An implementation that is compliant
  with an earlier major version can not be compliant with a major specification change. (It may
  offer compliance with multiple versions of the specification via the use of feature flags).

Index
---

* [Puppet Language Specification][2] - specification of the Puppet Domain Specific Language
* [Puppet Module Ruby APIs][3] - the Ruby APIs provided to module authors for extensibility and advanced capabilities
* General
  * [Settings and Options][4] - specification of settings and options
  * [Puppet Installation Layout][5] - specification of Puppet related files on disk

[2]:language/README.md
[3]:ruby_api/README.md

[4]:language/settings.md
[5]:file_paths.md

[1]:http://www.github.com/puppetlabs/puppet
