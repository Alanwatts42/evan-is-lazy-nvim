# 💤 LazyVim
# Evan is Lazy and this is his Configuration for NeoVim

I'd be shocked if anybody else but me ends up reading this, so whoever you are, bless you. I hope my (NeoVim)[https://neovim.io/] configuration files are useful to you, they're certainly useful to me. 

I started by forking the LazyVim starter repository which can be found in the LazyVIm documentation. My previous configuration had gotten out of hand, to the point where I had forgotten what I had intended to do with half of the plugins I'd added to it, and I'd ripped so much of it off from popular dot files repositories I'd found in the first page or two of a StartPage or Google search in which I'd been looking for how to do X or Y with my NeoVim configuration using Lua, since I was (and largely still am) pretty unfamiliar, and therefore quite frightened by, Lua. I had gotten very comfortable with VimScript, and had gotten to a point where I knew how to get Vim to do pretty much everything I wanted it to do, and if something broke, I knew enough about my own configuration to be able to find the problem and fix it. 

Because I'm an idiot who can't leave well enough alone, and because I'm easily influenced by peer pressure (You are too, trust me), I decided to convert from VimScript over to Lua. However, what I discovered relatively early on during this process is that, as a programming language, Lua is extremely picky. In other words, you must get the structure and formatting correct, and not 99% correct, but the full 100%, or the whole thing breaks. When it works, it works great, but because it's so unforgiving, it can be difficult to want to make any changes knowing that even the smallest error in any part of the code will make your whole configuration stop working.

This might not seem strange if you're accustomed to it, but to put this in perspective (my perspective anyway), let me try and describe what I was accustomed to with a VimScript-based configuration, so you can appreciate why Lua seemed so brutal in comparison. Let's say I'm changing the mapping of a particular command like <leader r> for example. In a VimScript configuration, if I've made an error in that particular part of my configuration, when I save the config file I'm working on and open some other file in vim to see if my <leader r> command does what I want it to do, when I open the file, I won't be able to tell that I've made a mistake right away, because the file will still open normally, the file will show up with the theme I've set up in my configuration, and all of my other plugins and features will work fine, but when I try the <leader r> shortcut, either nothing will happen, or I'll get an error message depending on what kind of error I've made and where exactly the error happens to be within that particular line. In other words, the damage I'll have done to my experience using vim will be very limited and although if I've made a mistake in the wrong place, it might cause my whole configuration to break and stop working altogether, perhaps causing vim or neovim to throw the whole thing out and give me default vim with no line numbers, no syntax highlighting, and no theme, but in most cases, unless my mistake is particularly damning, the damage will be limited to part of the configuration where I've made the error, and might not actually have an effect on my experience unless and until I try to use the particular shortcut or plugin feature controlled by the part of the configuration where I've made the error. 














A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.
