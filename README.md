# phantomjs
phantomjs compilations

https://bitbucket.org/ariya/phantomjs/downloads
This store the latest phantomjs compilations

Install
```shell
# Make the directory if it doesn't exist
$ mkdir -p $HOME/.phantomjs/2.1.1/x86_64-linux

# Download raw version. 
$ curl -L --retry 5 -O https://github.com/reesio/phantomjs/raw/master/phantomjs-2.1.1-linux-x86_64.tar.bz2

# In one pass, decompress bz2 and tar (-j). Place in $HOME/.phantomjs/2.1.1/x86_64-linux/ (-C), without top level directory (--strip-components 1)
$ tar xvjf phantomjs-2.1.1-linux-x86_64.tar.bz2 -C $HOME/.phantomjs/2.1.1/x86_64-linux/ --strip-components 1
```
