## /!\ WARNING!

I keep modifying these more or less daily so things might get broken. Don't blame me if it happens.
It's probably better to make copy of these to another location and just copy the parts you find most useful.

# Sublime Text 3 User Package (aka : my settings)

## Requirements:

- [Sublime Text 3](http://www.sublimetext.com/3)
- [Package Control](https://sublime.wbond.net/installation)


## Installation

Go to your Sublime Text 2 Packages directory (example on Mac):

    cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/

Clone the settings repository using the command below:

    git clone https://github.com/madsgraphics/ST3-User-package.git User

Install [Package Control](https://sublime.wbond.net/installation) by entering the following in the Sublime Text console:

    import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())


## Custom keyboard shortcuts

- `⌥ + ⇥` : Indent
- `⌥ + ⇧ + ⇥` : Unindent
- `⌥ + ctrl + ↓` : Goto Definition
- `⌥ + ctrl + u` : open URL in selected text
- `⌘ + ⌥ + :` + `⌘ + ⌥ + ↑` (sequence) : Fold code part
- `⌘ + ⌥ + :` + `⌘ + ⌥ + ↓` (sequence) : Unfold code part
- `ctrl + '` : Change quotes


## Extensions

_This section is out-of-date, need to update it :'(_

### Required extensions:

#### Theme

- Theme : [Aqua Theme](https://github.com/cafarm/aqua-theme) - ProKit flavour
- Font : [Source code Pro](http://blogs.adobe.com/typblography/2012/09/source-code-pro.html) - Light flavour

#### Essential tools

- [EditorConfig](https://github.com/sindresorhus/editorconfig-sublime)
- [GoldenRatio](https://github.com/roadhump/GoldenRatio)
- [Goto Documentation](https://github.com/kemayo/sublime-text-2-goto-documentation)
- [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements/)
- [SublimeCodeIntel](https://github.com/Kronuz/SublimeCodeIntel)
- [sublimeLinter](http://github.com/SublimeLinter/SublimeLinter)
- [SublimeTODO](https://github.com/robcowie/SublimeTODO)

### Suggested extensions:

#### General tools

- [Alignment](http://wbond.net/sublime_packages/alignment)
- [DocBlockr](https://github.com/spadgos/sublime-jsdocs)
- [Edit History](https://github.com/Stuk/sublime-edit-history)
- [Inc-Dec-Value](https://github.com/rmaksim/Sublime-Text-2-Inc-Dec-Value)
- [LinkOpener](https://github.com/NoxArt/SublimeText2-LinkOpener)

#### Code intelligence

- [BracketHighlighter](https://github.com/facelessuser/BracketHighlighter)
- [ChangeQuotes](https://github.com/colinta/SublimeChangeQuotes)
- [ColorHighlighter](https://github.com/Monnoroch/ColorHighlighter)
- [Dotfiles Syntax Highlighting](https://github.com/mattbanks/dotfiles-syntax-highlighting-st2)
- [LineEndings](https://github.com/SublimeText/LineEndings)
- [nginx](https://github.com/kvs/ST2Nginx)
- [WordHighlight](https://github.com/SublimeText/WordHighlight/)

#### Project management

- [Git](https://github.com/kemayo/sublime-text-2-git)
- [Gitignore](https://github.com/theadamlt/Sublime-Gitignore)
- [Modific](https://github.com/gornostal/Modific)

#### HTML

- [Emmet](https://github.com/sergeche/emmet-sublime) - ex-ZenCoding
- [HTML5](https://github.com/mrmartineau/HTML5)
- [HTMLAttributes](https://github.com/agibsonsw/HTMLAttributes)
- [Placeholders](https://github.com/mrmartineau/Placeholders)

#### CSS

- [Element Finder](https://github.com/keeganstreet/sublime-elfinder)
- [LESS](https://github.com/danro/LESS-sublime)
- [Hayaku](http://hayakubundle.com/)
- [Sass](https://github.com/nathos/sass-textmate-bundle)
- [SCSS](https://github.com/kuroir/SCSS.tmbundle)

#### JavaScript

- [Backbone.js](https://github.com/tomasztunik/Sublime-Text-2-Backbone.js-package)
- [CasperJS](https://github.com/n1k0/SublimeText-CasperJS)
- [CoffeeScript](https://github.com/jashkenas/coffee-script-tmbundle)
- [Grunt](https://github.com/tvooo/sublime-grunt)
- [jQuery](https://github.com/SublimeText/jQueryrake)
- [Nodejs](https://github.com/tanepiper/SublimeText-Nodejs)

#### Ruby

- [Rake](https://github.com/SublimeText/Rake)

#### PHP

- [CodeIgniter Utilities](https://github.com/roverwire/codeigniter-utilities)
- [Xdebug](https://github.com/Kindari/SublimeXdebug)

#### Drupal (yeah, I know :'( …)
- [Drupal](https://github.com/robballou/drupal-sublimetext)
- [Goto Drupal API](https://github.com/BrianGilbert/Sublime-Text-2-Goto-Drupal-API)

