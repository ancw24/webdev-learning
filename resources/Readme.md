# Resources

## Free Books

### Eloquent JavaScript

A book about JavaScript, programming, and the wonders of the digital, that explains the basics as well as advanced topics. 

[eloquentjavascript.net](https://eloquentjavascript.net/)

------

## Tools

### Markdown

1. A free online markdown editor that can be used for collaborative markdown editing:  
   [hackmd.io](https://hackmd.io/)

### Visual Studio Code

1. A common default for **.gitignore** files:
   ```
   # Operating system files
   .DS_Store

   # Code editor files
   .vscode
   .idea

   # Common framework directories
   .log
   .cache
   .tmp
   log
   cache
   tmp

   # NPM package directory
   node_modules
   ```

### Chrome Extensions

#### WebMaker

An extension that works like CodePen, but locally and is useful to fiddle around with HTML, CSS, etc. when you're not connected to the internet. The results can be published on CodePen later, with only one click of a button.

[webmakerapp.com](https://webmakerapp.com/)

### Documentations

#### DevDocs

A resource to search in all kinds of documentations, that can be stored for offline usage, to speed up searching.

[devdocs.io](https://devdocs.io/)

#### Zeal

Similar to DevDocs, but a desktop application for Ubuntu, that stores the documentations on your computer, independent from the used browser.

Zeal is for Linux and Windows only. For Mac users  [Dash](https://kapeli.com/dash) an alternative.

[zealdocs.org](https://zealdocs.org/)

### Web-Fonts

#### Google Webfont Helper

The google webfont helper is a useful tool to generate the needed package to use one ore more google fonts on your own server, instead of loading them from the Google CDN server.

[google-webfonts-helper.herokuapp.com](https://google-webfonts-helper.herokuapp.com/fonts/exo?subsets=latin)

### Drawing Charts

#### Draw.io

A free online diagram software. You can use it as a flowchart maker, network diagram software, to create UML online, as an ER diagram tool, to design database schema, to build BPMN online, as a circuit diagram maker, and more.

[www.draw.io](https://www.draw.io/)

## Typing

#### The Typing Cat

The Typing Cat is a nice online trainer to level up your typing skills, which also supports to learn typing using HTML or JavaScript.

[thetypingcat.com](http://thetypingcat.com/)

#### Typing Games

A curated list of games that can be used to learn typing. Some of those games are really fun to play!

[games.sense-lang.org](http://games.sense-lang.org/EN.php)

### Fun

#### ASCII Text

An ASCII text generator that can be used to have some fun comments in your website's code, etc.

[patorjk.com](http://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20)

------

## JavaScript libraries

### Moment.js

Parse, validate, manipulate, and display dates and times in JavaScript.

[momentjs.com](http://momentjs.com/)

## Free public APIs

#### toddmotto's list

The Github user [Todd Motto](https://github.com/toddmotto) created a curated list of free and public APIs, that shows if an API needs authentication and if you need to register for an account to be able to use it.

[Public APIs](https://github.com/toddmotto/public-apis)

------

## Ubuntu Fixes

### NPM Error: No space left

If you get a message from Node / npm that not space is left on your device, run the following command in your terminal.

```bash
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```