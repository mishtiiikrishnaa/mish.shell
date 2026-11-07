# mish.rainbow

an obsidian theme that goes with mish.fastfetch and mish.eza: same pastel rainbow, same typewriter feel.

## install
1. put this folder at `<your vault>/.obsidian/themes/mish.rainbow/` (it needs `theme.css` and `manifest.json`).
2. settings → appearance → themes → pick **mish.rainbow**.
3. install the community plugin **style settings** for the options (fonts, rainbow toggles, colours). the theme looks right without it, it just can't be tweaked.
4. leave settings → appearance → fonts empty, obsidian's own font boxes override the theme's.

## what you get
- ui in cm typewriter, notes in cm serif, headings in cm sans, all bundled (no install). other fonts are in the dropdowns.
- lowercase interface; notes, file names, folders, tags, headings and anything you type are left alone.
- rainbow titles (toggle), rainbow h1→h6 (on / soft / off), rainbow file path above notes (powerline pills / text / plain).
- rainbow gradient icons, a different turn of the gradient per icon. the gradient itself is drawn by mish.fastfetch / mish.eza; with neither enabled each icon gets one rainbow colour instead.
- thin rainbow scrollbars, rainbow hr, tag, link and code colours, light and dark mode.
- graph node, tag, attachment, unresolved, line and arrow colours from the palette, plus rainbow icons in its panel.

## graph: per-node rainbow
a theme can only set one colour per kind of node. for a rainbow across your notes, add groups in the graph's own settings (groups → new group) and use these hex colours:
pink `#ffa6c9`, peach `#ffd6a6`, yellow `#fff1a8`, green `#c9ffa6`, blue `#a6c9ff`, lilac `#c9b0ff`.

## fonts and licence
the bundled faces are latin modern (the tex users groups' version of computer modern, GUST font license), subset to latin and renamed "mish cm …". if the real cmu fonts are installed, choose "cmu (installed)" in the font dropdowns.
