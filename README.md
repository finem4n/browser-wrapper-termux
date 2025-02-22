# Achtung - archived
Moved to [my dotfiles repo](https://github.com/finem4n/dotfiles)

# browser-wrapper-termux
Simple shell wrapper for launching websites through termux android  
Why? Because I needed a way to launch websites in [newsboat](https://github.com/newsboat/newsboat).  
### Usage
1. Add `browser-wrapper.sh` to `PATH` in .bashrc/.zshrc.  
2. In .config/newsboat/config append:
```
browser browser-wrapper.sh
```

### Resources:
- https://github.com/pystardust/ani-cli
- https://developer.android.com/tools/adb#am
- https://gist.github.com/meramsey/b9c98032a34612a1a29f9fd2059156a5
