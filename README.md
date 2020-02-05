# spyder-cyberpunk-color-theme
A good old purple+cyan cyberpunk theme for Python syntax coloring in Spyder 

## Screenshots

![](https://i.imgur.com/6JyFeV3.png)
![](https://i.imgur.com/g3Ddqys.png)

## How to install

1) Look for your _spyder.ini_ file. Mine was at _~/.config/spyder-py3_ folder.
2) In this file, look for the ```[color_schemes]``` section.
3) At this section, add the theme name to the ```names``` list:

   ```ini
   names = ['emacs', 'idle', 'monokai', 'pydev', 'scintilla', 'solarized/dark',
   'solarized/light', 'spyder', 'spyder/dark', 'zenburn', 'cyberpunk_purpleblue']
   ```   
4) Append the theme colors in _cyberpunk_purpleblue.ini_ below the other themes' ones. For example:
   ```ini
   [color_schemes]
   names = ['emacs', 'idle', 'monokai', 'pydev', 'scintilla', 'solarized/dark',
   'solarized/light', 'spyder', 'spyder/dark', 'zenburn', 'cyberpunk_purpleblue']
   selected = cyberpunk_purpleblue
   emacs/name = Emacs
   emacs/background = #000000
   ...
   ...
   temp/background = #09162f
   temp/sideareas = #09162f
   cyberpunk_purpleblue/background = #09162f
   cyberpunk_purpleblue/currentline = #112b5d
   cyberpunk_purpleblue/currentcell = #0c1e40
   cyberpunk_purpleblue/occurrence = #423f4f
   cyberpunk_purpleblue/ctrlclick = #204a87
   cyberpunk_purpleblue/sideareas = #09162f
   cyberpunk_purpleblue/matched_p = #8ae234
   cyberpunk_purpleblue/unmatched_p = #ef2929
   cyberpunk_purpleblue/normal = ('#bfbbcc', False, False)
   cyberpunk_purpleblue/keyword = ('#0abdc6', False, False)
   cyberpunk_purpleblue/builtin = ('#db38a3', False, False)
   cyberpunk_purpleblue/definition = ('#0abdc6', True, False)
   cyberpunk_purpleblue/comment = ('#5b5b6f', False, True)
   cyberpunk_purpleblue/string = ('#b56cad', False, False)
   cyberpunk_purpleblue/number = ('#f08caa', False, False)
   cyberpunk_purpleblue/instance = ('#b56cad', False, True)
   cyberpunk_purpleblue/name = cyberpunk_purpleblue
   ```
5) Pick the theme in _Tools > Preferences > Syntax Coloring_
![](https://i.imgur.com/euZ15kd.png)


