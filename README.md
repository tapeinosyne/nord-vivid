# vivid nord

A [Nord](https://www.nordtheme.com/) theme for the [vivid](https://github.com/sharkdp/vivid) `LS_COLORS` generator.

You may preview it like so:

```bash
vivid preview <( curl -f https://raw.githubusercontent.com/tapeinosyne/nord-vivid/master/nord.yml )
```

## Installation

Download `nord.yml` and generate a `LS_COLORS` template, storing it at a path of your choice.

```bash
vivid generate <( curl -f https://raw.githubusercontent.com/tapeinosyne/nord-vivid/master/nord.yml ) \
>> ~/.config/vivid/themes/nord.ls_colors
```

Then, read the template into `LS_COLORS` and export the variable from your shell's source files, e.g. `~/.zshrc`.

```bash
export LS_COLORS=$(< ~/.config/vivid/themes/nord.ls_colors )
```
