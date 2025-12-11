# Theme for [oh-my-zsh](https://ohmyz.sh/)

## Installation

Add below to your `.zshrc`.

```
ZSH_THEME="zero"
```

### If you using [Chezmoi](https://www.chezmoi.io/)

You can add below to your `.chezmoiexternal.toml`

```toml
[".oh-my-zsh/custom/themes/zero.zsh-theme"]
    type = "file"
    url = "https://raw.githubusercontent.com/ZocketZero/zero-zsh-theme/main/zero.zsh-theme"
    refreshPeriod = "168h"
```

and run

```bash
chezmoi -R apply
```

### Download `zero.zsh-theme`

And move into `.oh-my-zsh/custom/themes`.
