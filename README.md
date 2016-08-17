![icon](https://dl.dropboxusercontent.com/u/8178/focus-icon.png)
# focus-tab

Hack to improve focus by disabling alt-tab in OSX

![Screenshot](https://dl.dropboxusercontent.com/u/8178/focus.gif)

## Requirements

* [Alfred 3](http://www.alfredapp.com/)
* [Karabiner](https://pqrs.org/macosx/keyremap4macbook/)


## Setup

* Install workflow in alfred
* Add contents of private.xml into your Karabiner private.xml file and reload it. 
* Create two different Karabiner profiles. In the first, do not enable the 'focus-tab' feature, but do it in the second one.

### More info

![Enabled feature](https://dl.dropboxusercontent.com/spa/6f6p31rqk1cfe43/kzqb96nw.png)
![Profiles](https://dl.dropboxusercontent.com/spa/6f6p31rqk1cfe43/4kaqk_3x.png)

* More information about private.xml [here](https://pqrs.org/macosx/keyremap4macbook/xml.html.en)
* More about multiple profiles [here](https://pqrs.org/osx/karabiner/document.html.en#profiles)

## Usage

Toggle alt-tab functionality by activating alfred, typing 'focus' and pressing enter.

## Tips

* Don't use it all the time, or your brain will start finding ways to work around it.
* Use alfred to assign shortcuts for applications you planning to use while in alt-focus. I use `option+a` for Emacs and `option+s` for my browser, then I just use these to switch between apps.
* If you really need to switch to another app, use alfred to quickly raise the application window.
* Put the applications you planning to use in full-screen mode.
