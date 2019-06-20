# bash-improvement

## explain `#!/bin/bash`
- [why](http://tldp.org/LDP/Bash-Beginners-Guide/html/sect_01_01.html) ? 

## explain `echo Script: $(basename "$0")`
- what is the meaning of *`* here?
- what is the meaning of $(expression) inside bash?
- what is the meaning of basename here?
- do you know what is `$#`?
- how to get input for shell script?
- is there a way to interactive with user?
- how to get execution context for shell?

## explain `set -e`

## explain `[ -z "$( brew ls --versions findutils )" ] && brew install findutils`
- what is the `[]`?
- what is the `-z`?
- what is `brew ls --versions findutils`?
- what is `findutils`?
- what is `&&` here?

## explain `READLINK="greadlink"`
- how to use the variable?
- what's the basic type in bash script?
- can I use the variable from another script file?

## explain `cd ..`

## explain `export BUILD_ENV=${1:-development}`
- what is `${1:-development}`?
- what is export?

## explain `source ${ASSERT_VAR_SCRIPT} BUILD_ENV`
- what is `source`?
- what is `exit 1`?

## explain `SCRIPT_DIR="$( cd "$( dirname "${BASH_SOURCE[0]}" )" >/dev/null 2>&1 && pwd )"`
- 

## command set
- set
- basename
- uname
- brew
- findutils
- coreutils
- dirname
- greadlink / readlink
- pwd
- export
- source
- exit
- pushd / popd
