We have a few recomendation on how to write bash scripts.

1. Include shebang line like `#!/bin/bash`
1. Set strict mode with `set -euo pipefail` in the beginning. More about it described here [Use Bash Strict Mode](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
1. Run [shellcheck](https://github.com/koalaman/shellcheck) tool and aim to fix produced warning and errors. 

