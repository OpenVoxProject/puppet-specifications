Puppet Language Specifications
===

The Puppet Programming Language Specification is a specification of the Puppet Programming
Language. The first published release of this specification specifies the language version 4.

The version 4.0.0 is the first version of the specification (this to make it harmonize
with the 4.0.0 release of Puppet). From that point, the intention is to keep the
same specification version even if the minor version of the implementation changes (i.e.
for other reasons that the specification has changed). When a specification change is made,
it *may* skip several numbers to again harmonize with the Puppet implementation version number.

Until Puppet 4.0 was released, there was just the "current" and "future" implementations
of the language. As time goes on it will be impossible to use only those words as their meaning
is relative to a particular release of puppet (the future in 3.6 is not the same as the future in 3.7, and again not the same as current in 4.0) - hence the need for a separate version of the
specification.

The [Puppet Project][1] is the reference implementation of the specification.

Index
---

* [Introduction][2] - terminology and EBNF grammar
* [Modus Operandi][3] - overview of the runtime (loading, start-point, order of execution)
* [Types, Values and Variables][4] specification of types, values and variables
* [Naming and Scoping][5] - specification of names, scopes, and references
* [Lexical Structure][6] - specification of the textual aspects of the Puppet Language
* [Expressions][7] - specification of all non catalog expressions in the language
* [Catalog Expressions][8] - specification of all expressions related to catalog production
* [Expression Precedence][9] - specification of the precedence of expressions / operators
* [Puppet Functions][14] - functions in the puppet language
* [Deprecation][10] - specification of deprecated constructs
* Models
  * [Puppet Extended S-Expression Notation (PN)][17] - specification of the PN format
* Plan Extensions
  * [Apply Expression][18] - an expression to capture a manifest block and apply it on remote nodes
* General
  * [Settings and Options][13] - specification of settings and options
  * [Puppet Installation Layout][15] - specification of Puppet related files on disk

[2]:intro.md
[3]:modus-operandi.md
[4]:types_values_variables.md
[5]:names.md
[6]:lexical_structure.md
[7]:expressions.md
[8]:catalog_expressions.md
[9]:expression_precedence.md
[10]:deprecations.md

[11]:func-api.md
[12]:plugin-api.md
[13]:settings.md
[14]:puppet-functions.md
[15]:file_paths.md
[16]:resource_types.md
[17]:../models/pn.md
[18]:apply.md

[1]:http://www.github.com/puppetlabs/puppet
