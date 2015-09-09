# according-to-Jeffrey
All themes from Dayle Rees colour-schemes repo with changed LINE_SPACING to 1.5 and EDITOR_FONT_SIZE to 15 according to Be Awesome In PhpStorm tutorials by Jeffrey Way.
### Search and replace done with VIM
```
vim
:args *
:argdo %s/EDITOR_FONT_SIZE" value="\d"/EDITOR_FONT_SIZE" value="15"/ge
:argdo %s/EDITOR_FONT_SIZE" value="\d\d"/EDITOR_FONT_SIZE" value="15"/ge
:argdo %s/LINE_SPACING" value="\d\.\d"/LINE_SPACING" value="1\.5"/ge
:argdo update
:qa
```
