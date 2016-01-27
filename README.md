# Lucid Tabs: An Atom Package

Adds color to the text of atom tabs, based off their name.

Right now, Lucid will attempt to match colors to tab titles with a wildcard expression. If a certain string is found anywhere in a tab title, a specific color will be applied. The intention is to make tabs a bit easier to organize based off your different types of scripts.

Basically, you get to differentiate among different tabs based off your own rules. Color them based off extension, or purpose. For example:

`.js` will match JavaScript files
`Service` will match your Services, like `ChatService`, `UserService`, etc.

More to come! I'd like to set up an actual configuration feature. Right now you need to edit the file `~/.atom/packages/lucid-tabs/styles/lucid-tabs.less` to change color and string matching rules.

# Alternatives
This module a modified version of version of [graemeboy/rainbow-tabs](https://github.com/graemeboy/rainbow-tabs) (thanks!).
If you need more power and customization, consider the [color-tabs](https://atom.io/packages/color-tabs) module combined with [color-tabs-regex](https://atom.io/packages/color-tabs). The main difference is that `color-tabs` is built to be configurable while Lucid is not (although it's expected that you will edit the source to suit your own purposes). Something else to consider is Lucid only uses LESS styles for customization, no JavaScript involved.

Bottom line is Lucid Tabs gives you more functionality out of the box, but options are limited.

--------------------------

Forked from graemeboy/rainbow-tabs (thanks!)

![A screenshot of rainbow extensions](https://raw.githubusercontent.com/nmai/lucid-tabs/master/resources/screenshot1.png)
