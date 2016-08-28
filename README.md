

# Gua-Vim


## Description

```
                                 ___           ___           ___
                                 /\__\         /\  \         /\  \
                                /:/ _/_        \:\  \       /::\  \
                               /:/ /\  \        \:\  \     /:/\:\  \
                              /:/ /::\  \   ___  \:\  \   /:/ /::\  \
                             /:/__\/\:\__\ /\  \  \:\__\ /:/_/:/\:\__\
                             \:\  \ /:/  / \:\  \ /:/  / \:\/:/  \/__/
                              \:\  /:/  /   \:\  /:/  /   \::/__/
                               \:\/:/  /     \:\/:/  /     \:\  \
                                \::/  /       \::/  /       \:\__\
                                 \/__/         \/__/         \/__/
                                                            ___
                                  ___                      /\  \
                                 /\  \        ___         |::\  \
                                 \:\  \      /\__\        |:|:\  \
                                  \:\  \    /:/__/      __|:|\:\  \
                              ___  \:\__\  /::\  \     /::::|_\:\__\
                             /\  \ |:|  |  \/\:\  \__  \:\~~\  \/__/
                             \:\  \|:|  |   ~~\:\/\__\  \:\  \
                              \:\__|:|__|      \::/  /   \:\  \
                               \::::/__/       /:/  /     \:\__\
                                ~~~~           \/__/       \/__/
```



## Screenshot

**molokai theme**
![](http://7xwh85.com1.z0.glb.clouddn.com/Gua-Vim%20screen%20shot.png)


## Setup

### 1. clone repo

```bash
git clone git@github.com:Desgard/Gua-Vim.git
```


### 2. setup Dependencies


#### 2.1 ctags and ag

```bash
# ubuntu
sudo apt-get install ctags
sudo apt-get install build-essential cmake python-dev  # YCM delay
sudo apt-get install silversearcher-ag

# macOS
brew install ctags
brew install the_silver_searcher
```

#### 2.2 Use Python

```bash
sudo pip install pyflakes
sudo pip install pylint
sudo pip install pep8
```

#### 2.3 Use Javascript - Optional

```bash
# install jshint and jslint to check the js syntax

# ubuntu
sudo apt-get install nodejs npm
sudo npm install -g jslint
sudo npm install jshint -g

# mac
brew install node
npm install jshint -g
npm install jslint -g
```


#### 3. Install

```shell
sh -x install.sh
```

## MIT License

Copyright (c) 2016 Desgard_Duan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
