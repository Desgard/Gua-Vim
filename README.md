
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

# Gua-Vim


## Description

![](http://7xwh85.com1.z0.glb.clouddn.com/Gua-Vim%20screen%20shot.png)


## Screenshot

**molokai theme**



## Setup

### 1. clone repo

```bash
git clone git@github.com:Desgard/Gua-Vim.git
```


### 2. setup Dependencies


#### 2.1 ctags and ag
```
# ubuntu
sudo apt-get install ctags
sudo apt-get install build-essential cmake python-dev  # YCM delay
sudo apt-get install silversearcher-ag

# mac
brew install ctags
brew install the_silver_searcher
```

#### 2.2 Use Python

```
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
