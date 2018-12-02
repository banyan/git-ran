# git-ran

## Overview

Sometimes I want to use the last executed command as a git commit message.

```
cargo add foo
git ran # => git add . && git commit -m "cargo add foo"
```

## Installation

```
brew tap banyan/misc
brew install git-ran
```

## Caveats

currently only zsh is supported.

## License

MIT
