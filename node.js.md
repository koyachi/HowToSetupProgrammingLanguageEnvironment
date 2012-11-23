# Node.js

use nodebrew.

```
curl https://raw.github.com/hokaccha/nodebrew/master/nodebrew | perl - setup
```

add PATH to .zshrc or .bashrc
```
export PATH=$HOME/.nodebrew/current/bin:$PATH
```

reload .zshrc file
```
source ~/.zshrc
```

```
nodebrew install v0.9.3
nodebrew use v0.9.3
```

add these lines to .zshrc file to apply "nodebrew use" to current terminal.
```
# source nodebrew
if [[ -f ~/.nodebrew/nodebrew ]]; then
    export PATH=$HOME/.nodebrew/current/bin:$PATH
    nodebrew use v0.9.3
fi
```

# links
- http://nodejs.org
- https://npmjs.org
- http://d.hatena.ne.jp/Jxck/20120224/1330035058

