# consoom
the fastest way to consoom plebbit

### deps
wget  
sxiv

### usage
`$ consoom {subreddit}`  
you can set the default one with `$BOARD` by editing the source

### sixel
`$ consoom-sixel {subreddit}`  
you must use a capable terminal emulator e.g. kitty

### sxiv dark theme
either edit the source (window.c):  
`122 bg = win_res(db, RES_CLASS ".background", "black");`  
or set it in .Xresources

### libreddit
host it by yourself or find one [here](https://github.com/spikecodes/libreddit#instances)
