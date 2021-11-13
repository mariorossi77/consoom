# consoom
consoom plebbit a sxiv $1 at a time

### deps
wget  
sxiv

### usage
`$ consoom {subreddit}`  
you can set the default one with `$BOARD` by editing the source

### dark theme
either edit the source (window.c):  
`122 bg = win_res(db, RES_CLASS ".background", "black");`  
or set it in .Xresources

### libreddit
host it by yourself or find one [here](https://github.com/spikecodes/libreddit#instances)
