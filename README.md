Texmf
=====

Stores my collection of xelatex style files for layouts and components. 
To use, simply clone and link to your home directory.

```
> git clone https://github.com/stonier/texmf.git
> ln -s /path/to/clone/texmf ~/texmf
> texhash ~/texmf
```

Prior to running xelatex, you will need some fonts installed:

```
> sudo apt-get install ttf-linux-libertine ttf-dejavu ttf-liberation fonts-unfonts-extra fonts-unfonts-core
```
