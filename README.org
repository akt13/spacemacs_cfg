# spacemacs_cfg
spacemacs config file

## Installing Vterm
``` sh
git clone https://github.com/akermu/emacs-libvterm.git
mkdir -p build
cd build
cmake ..
make
```

Don't forget to first install libvterm in your system:
``` sh
brew install libvterm
```


or

``` sh
sudo apt-get install libvterm
```

then just add it to your dotspacemacs:

``` lisp
(push dotspacemacs-additional-packages
  '((vterm :location "/path/to/your/clone/of/emacs-libvterm")))
```

## UTF-8 configuration for shell

https://perlgeek.de/en/article/set-up-a-clean-utf8-environment
