Texmf
=====

Stores my collection of xelatex style files for layouts and components. 
To use, simply clone and link to your home directory.

```
> git clone https://github.com/stonier/texmf.git
> ln -s /path/to/clone/texmf ~/texmf
> texhash ~/texmf
```

These are for running xelatex, so make sure that is installed along with some fonts that
the style files make use of:

```
> sudo apt-get install texlive-xetex kile
> sudo apt-get install fonts-unfonts-core fonts-unfonts-extra fonts-linuxlibertine texlive-fonts-extra ttf-dejavu ttf-liberation
```
