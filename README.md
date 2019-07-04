# bash-improvement

## explain `#!/bin/bash`
- [why](http://tldp.org/LDP/Bash-Beginners-Guide/html/sect_01_01.html) ? 

## explain `echo Script: $(basename "$0")`
- [what is the meaning of $(expression) inside bash?](https://www.gnu.org/software/bash/manual/html_node/Command-Substitution.html)
- [do you know what is `$0`?](https://www.tldp.org/LDP/abs/html/othertypesv.html) 
- [some special Parameters](https://www.tldp.org/LDP/abs/html/internalvariables.html#APPREF)
- [is there a way to interactive with user?](https://ryanstutorials.net/bash-scripting-tutorial/bash-input.php)

## explain `set -e`
https://www.gnu.org/software/bash/manual/html_node/The-Set-Builtin.html

## explain `[ -z "$( brew ls --versions findutils )" ] && brew install findutils`
- [what is the \[ -z "$( brew ls --versions findutils )" \]?](https://www.gnu.org/software/bash/manual/html_node/Bash-Conditional-Expressions.html)
- what is `&&` here?

## explain `READLINK="greadlink"`
- [what's the basic type in bash script?](http://www.tldp.org/LDP/abs/html/untyped.html)
- can I use the variable from another script file?

## explain `cd ..`

## explain `export BUILD_ENV=${1:-development}`
- what is `${1:-development}`?
- what is export?

## explain `source ${ASSERT_VAR_SCRIPT} BUILD_ENV`
- what is `source`?
- what is `exit 1`? The value returned by a command to its caller. The value is restricted to eight
                    bits, so the maximum value is 255.

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
