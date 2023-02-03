# inochi-creator-mimetype
i have adhd so instead of opening the example models in [inochi creator](https://github.com/Inochi2D/inochi-creator) and actually learning anything, i made a filetype association so i could open .inx files from my file manager

# install
put thing in the new place

`x-inx.xml` -> `~/.local/share/mime/packages`

then `update-mime-database ~/.local/share/mime`

verify newly installed mimetype:

```bash
xdg-query filetype path/to/file.inx
# result should be 'application/x-inx'
# NOT 'application/octet-stream'
```

put other thing in the other new place

`inochi-creator.desktop` -> `~/.local/share/applications`

then `update-desktop-database ~/.local/share/applications`

enjoy opening .inx files from your browser or file manager
