# iTerm2
Minimal iTerm2 for Apple Silicon (M1 M2 M3 M4)\
Tested on Mac Mini M4 (2024)



Prerequisites
- [Homebrew](https://brew.sh/) 
- [Oh My Zsh](https://ohmyz.sh/)
- [iTerm2](https://iterm2.com/)
- [iTerm2 — Snazzy theme](https://github.com/sindresorhus/iterm2-snazzy)
- [zplug (zsh plugin manager)](https://github.com/zplug/zplug)
- [pure prompt](https://github.com/sindresorhus/pure)

1. Install iTerm2 with brew:
```
brew install --cask iterm2
```

2. iTerm2 Preferences:

Appearance > General > Theme: Minimal

3. Install iTerm2 — Snazzy theme
```
(curl -Ls https://raw.githubusercontent.com/sindresorhus/iterm2-snazzy/main/Snazzy.itermcolors > /tmp/Snazzy.itermcolors && open /tmp/Snazzy.itermcolors)
```

Most important: 
```
export ZPLUG_HOME=/opt/homebrew/opt/zplug
```

TBC


[Source](https://medium.com/airfrance-klm/beautify-your-iterm2-and-prompt-40f148761a49)
