# git-ran

## Overview

Sometimes I want to use the last executed command as a git commit message.

```
yarn add foo
git ran # => git add . && git commit -m "yarn add foo"
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
