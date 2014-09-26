# CompilerOptions

[![Build Status](https://travis-ci.org/sjkelly/CompilerOptions.jl.svg?branch=master)](https://travis-ci.org/sjkelly/CompilerOptions.jl)
[![Coverage Status](https://img.shields.io/coveralls/sjkelly/CompilerOptions.jl.svg)](https://coveralls.io/r/sjkelly/CompilerOptions.jl?branch=master)

This is a basic package for providing introsepction into Julia's compiler options.

## Use
#### ```code_coverage()``` → ::Bool
Returns `true` if Julia is counting exections of source lines.
Corresponds to the `--code-coverage={none|user|all}` or `--code-coverage` flag.

#### ```check_bounds()``` → ::Bool
Returns `true` if julia is emitting bounds checks.
Corresponds to the `--check-bounds={yes|no}` flag.

#### ```dump_bitcode()``` → ::Bool
Returns `true` if Julia is dumping bitcode. Corresponds to the ` --dump-bitcode={yes|no} ` flag.

### Additonal functions for v0.4

#### ```compile_enabled()``` → ::Bool
Returns `true` if Julia was run with compilation enabled. Corresponds to the `--compile={yes|no|all} ` flag.


## Credit
This package was kick started with the help of ihnorton, jakebolewski, and staticfloat.

* https://gist.github.com/staticfloat/93d7050a08ff7bb52373
* https://groups.google.com/d/msg/julia-users/TkYi6CJrSVE/L-ydZ67ujiUJ

## License
Available under the [MIT "Expat" License](http://en.wikipedia.org/wiki/MIT_License). See: [LICENSE.md](./LICENSE.md).

