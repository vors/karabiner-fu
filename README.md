# karabiner-fu
Customizations for https://github.com/tekezo/Karabiner

## private.xml

Customizations are done thru `private.xml`.
It's located under

```
~/Library/Application Support/Karabiner/private.xml
```

## New options

### Remote desktop
This option is based on the stock option


> Change command key to control key in Remote Desktop.
>  + Change command-tab to alt-tab.
>  + Send Windows key event when you pressed the command key alone.

And adds a couple of tweaks:

- Narrows remapping only to the **actual remote session window** (see [Karabiner#632](https://github.com/tekezo/Karabiner/issues/632))

- Disables Ctrl + TrackPad for zoom-in zoom-out.
I found expirience annoying, when you scroll with two-fingers and hit `Cmd+Tab` to change a window.

- Change Functional Keys to F1...F12

### Terminal

- Remaps `Cmd+R` to `Ctrl+R` to enable reverse-search in bash/fish. 

Also, if you use fish, you may want to take a look at [fzf](https://github.com/junegunn/fzf) for reverse-command search. 
