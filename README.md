# polyglot
Download information for jupyter kernels in one place, TL;DR style.

*currently for OSX users, code blocks are meant to be ran in the command line*
## Python
### python3.5
1. `python3 -m pip install ipykernel`
2. `python3 -m ipykernel install --user`
  
### python2.7
1. `python2.7 -m pip install ipykernel`
2. `python2.7 -m ipykernel install --user`

## Javascript
### IJavascript
1. locally: `npm install ijavascript`
2. globally: `sudo npm install -g ijavascript`

## R
### IRKernel
1. install R:
    - install [homebrew](http://brew.sh/)
    - `brew tap homebrew/science`
    - `brew install Caskroom/cask/xquartz`
    - `brew install r`
2. Start an R console:
    - `install.packages(c('repr', 'IRdisplay', 'evaluate', 'crayon', 'pbdZMQ', 'devtools', 'uuid', 'digest'))`
    - `devtools::install_github('IRkernel/IRkernel')`
    - `IRkernel::installspec()`
    
## Ruby
### IRuby
1. If you don't have ruby, install that!
    - I recommend installing using [rbenv]( https://github.com/rbenv/rbenv)
2. `brew install libtool autoconf automake autogen`
3. `gem install rbczmq`
4. `gem install iruby`

## Julia
### IJulia
1. [Download Julia](https://s3.amazonaws.com/julialang/bin/osx/x64/0.5/julia-0.5.0-osx10.7+.dmg)
2. Open the Julia console by clicking on the application icon
3. At the prompt, type:
    `Pkg.add("IJulia")`
  
