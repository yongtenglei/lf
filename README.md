# Rey LF config

## Picture preview (Idea from [Luke Smith](https://lukesmith.xyz/))

The most important thing, `ueberzug` should be installed.

For picture preview you need get script `lfub`, you can find it from my [scripts](https://github.com/yongtenglei/scripts) repository. `lfub` provide an ueberzug environment for lf to use. Make sure the system can access `lfub` and use `lfub` to launch lf.

You could:

```zsh
alias lf="lfub"
```

Additionally, `cleaner` and `scope` are required, but they are here already.

`lfcd.sh` allows you change working directory when you strolling in lf, more detail, see [gokcehan/lf](https://github.com/gokcehan/lf).

## Key mapping

I'am a colemak user, the key mapping may strange for `QWERT` user, just remove some key mappings settings and change them for your preference, it's easy.

## Other Integration

use `rsync` for copy and cut.

use `fzf` for search files.

## More thing...

You can change or add directory shorthand `shorthandrc` for free, function `moveto` and `copyto` use it to offer convenience.
