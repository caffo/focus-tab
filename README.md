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

![Profiles](https://dl.dropboxusercontent.com/spa/6f6p31rqk1cfe43/4kaqk_3x.png)
![Enabled feature](https://dl.dropboxusercontent.com/spa/6f6p31rqk1cfe43/kzqb96nw.png)

More information about private.xml [here](https://pqrs.org/macosx/keyremap4macbook/xml.html.en).
More about multiple profiles [here](https://pqrs.org/osx/karabiner/document.html.en#profiles)

## Usage

Toggle alt-tab functionality by activate alfred and issuing 'focus'.
