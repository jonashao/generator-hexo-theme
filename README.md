
# hexo theme generator for yeoman
---
It's used to quickly scaffold a theme for hexo. The theme it creates is fully functional and has no design. That part is up to you!

# Features
---
It creates all of the necessary files you need to make your own theme.

You will be prompted for:
+ the theme name
+ hexo plugins directory (yes/no)
+ Bower packages (yes/no)
+ EditorConfig file (yes/no)
+ JSHint file (yes/no)

# Install
---
```sh
npm install -g generator-hexo-theme
```

# Use
---
Navigate to the directory you want to place the theme project in.
```sh
mkdir mytheme
cd mytheme
yo hexo-theme
```

Then goto your hexo project's `_config.yml` and switch the `theme` propery to what you have named it.

# Resources
---
hexo static site generator [hexo.io](http://hexo.io)
Yeoman scaffolding tool [yeoman.io](http://yeoman.io)
Bower package manager [yeoman.io](http://bower.io)
EditorConfig [editorconfig.org](http://editorconfig.org)