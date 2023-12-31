# Export extensions

## Powershell

```ps
code --list-extensions | % { "code --install-extension $_" }
```

## Bash

```bash
code --list-extensions | xargs -L 1 echo code --install-extension
```

# Import extensions

OUTPUT del comando anterior