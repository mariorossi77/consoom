# consoom
the fastest way to consoom plebbit
edit:  
i just realized there is already a similar tool  
https://github.com/Bugswriter/redyt  
nice to see you can use json instead of html

### deps
wget  
sxiv

### usage
`$ consoom {subreddit}`  
you can set the default one with `$BOARD` by editing the source

### sixel
`$ consoom-sixel {subreddit}`  
you must use a capable terminal emulator e.g. st (sixel branch)

### sxiv dark theme
either edit the source (window.c):  
`122 bg = win_res(db, RES_CLASS ".background", "black");`  
or set it in .Xresources

### libreddit
host it by yourself or find one [here](https://github.com/spikecodes/libreddit#instances)
