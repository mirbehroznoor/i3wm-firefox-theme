# i3wm-firefox-theme

The theme is checked on Ubuntu 20.4 LTS with i3wm

It is a customized version of [Firefox i3wm Theme](https://github.com/aadilayub/firefox-i3wm-theme) & a bit of code is from [Slick-Fox](https://github.com/Etesam913/slick-fox). 


![](i3wm-firefox-theme-1.png)

![](i3wm-firefox-theme-2.png)


# Installation 


### Mozilla firefox directory  

* Go to url: `about:support`

* In section `Applicaton Basics` look for `Profile Directory` and click on the `Open Directory`

### Chrome Folder

* Once in directory look for the folder `chrome` if there is no such directory, create one, Manually __OR__ Use Terminal:

```
mkdir -p chrome
```
### userChrome.css File

#### 1. First Way

* Go to the directory `chrome/` and create the file `userChrome.css`

* Copy and Paste the contents of userChrome.css

#### 2. Second Way

* `git clone https://github.com/mirbehroznoor/i3wm-firefox-theme`

* Paste the `userChrome.css` file in `chrome/` folder

### Firefox permission:

* Go to url `about:config`

* Search for `toolkit.legacyUserProfileCustomizations.stylesheets` set it to __TRUE__

* Restart the Firefox to enjoy your new theme

# Keys

* `Ctrl l` or `F6` slides down the navigation bar with url selection

# Advice

   Remember there are no __one-size-fits-all__ theme 

   Have Fun Experimenting 
