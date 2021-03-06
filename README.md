# Menu Creator
A Blender addon to quickly create custom menus for any Object.

This addon can be useful both for Blender users, to expose the properties in a handy and clean Menu, and for content creators who want to include a Menu to their models. Moreover, in the latter case, since the Menu is fully customizable, users of these models will also be able to furtherly customize the Menu without knowing anything about Python!

## Features
- create a menu for any Blender object (one for each Object you want)

![Prev2](https://i.ibb.co/Dw3sDLH/Eqh-COxv-Xc-AAqd1-H.jpg)

- plenty customization options (more to come)

![Prev1](https://i.ibb.co/mXdrYWg/Eqh-CLG3-Xc-AUYe3v.jpg)

- add all the properties you want to the menu simply right clicking on any property

- link properties so they always have the same value

- collection functionality: you can create a list of collections from which the menu will list the contained objects

- outfit functionality: as an extension of the collection functionality, it is possible to enable auto-masking of the objects listed in the menu. This means that you can define a Body object, and its mask modifiers will be activated when you show an Object in the collection list

## Installation
You can find the latest version in the [Releases page of this repository](https://github.com/Mustard2/MenuCreator/releases).

Alternatively, you can ownload the whole repository as a zip file (or clone it locally), and then install the .py file (**not the .zip file, you must unzip it and use the Python file!**).

## Instructions
- create a Menu clicking on an Object and initializing the Menu
- add properties simply right clicking on any Blender property, and clicking Add to the Menu (note that operators are not supported at the moment, and can not be added to the Menu)

![Right-click](https://i.ibb.co/V3F2x9w/Eqh-CQo-GXUAE9pad.jpg)

- to start editing the Menu, be sure to be in Edit Mode (check the Menu Edit Mode Enable in the Menu Creator settings)

- you can change the name and the icon of the properties in Edit Mode, clicking on the cogwheel

- you can link properties to the ones you already added. Just click on a property and use Link to Property

![Linked props](https://i.ibb.co/wN929LX/Cattura2.png)
![Linked props2](https://i.ibb.co/HNFVf15/Cattura3.png)

- you can create new sections in the Menu to get a cleaner list of the properties, clicking on the + button. You can choose the order of both sections and properties within the section

- to use the collection functionality, create a section and choose Collection Section (note that the type of the section can not be changed after the section has been created)

- to enable the global collection options and the Outfit functionalities, check the Section properties (the cogwheel near the Section name in Edit Mode)

![Right-click Collection](https://i.ibb.co/7CT96KK/Eqh-CUMKXAAEB36u.jpg)

- [check the video for the complete instructions](https://gofile.io/d/NPrmDS) (updated to version 0.0.1)

## FAQ

- *I shared a blend file to another person and he/she can't see the Menu*

All the users of these Menu should install this addon!

- *How can I add a property of an Object to the menu of another Object?*

By default, when you click on an Object, the addon will show the menu of the selected item. To pin the current Object Menu click on the Pin button on the first line (on the far left), and this will prevent the Menu to be changed when you select other Objects until you un-pin the Menu.

- *How can I show only one Object Menu, i.e. why does the Menu changes when I click on other Objects?*

This is the intended behaviour. To pin the current Object Menu click on the Pin button on the first line (on the far left), and this will prevent the Menu to be changed when you select other Objects until you un-pin the Menu.

- *I found an issue or I would like to suggest new functionalities*

You can open an Issue on GitHub (click on the Issue tab above). Please, try to be specific and include screenshots if possible.
