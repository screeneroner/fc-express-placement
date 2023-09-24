This is a copy of the [Express Placement](https://wiki.freecad.org/Macro_Express_Placement) documentation from the main FreeCAD macros repository.

# Description

Express Placement is a FreeCAD GUI addon. It allows quick editing of the X, Y, Z placement coordinates for the currently selected object.

# Difference and benefits

[![Standard in red and Express in green](standard_vs_express.png "Standard in red and Express in green")](https://www.buymeacoffee.com/screeneroner)

One double click to edit object placement instead of four sequential clicks - '''you may work 4 times faster!'''

## Standard FreeCAD Placement (in red)

The standard FreeCAD built-in editor requires many additional mouse clicks before you actually start parameter editing, especially when using parametric expressions to position your object:

1. Click on the Base/Placement item in the Property view to unfold the Placement tree.
2. Click on the Position branch to unfold the X, Y, Z coordinates fields.
3. Click on the desired coordinate to make the expression editing icon visible.
4. Click the expression editing icon, which is so small that it may be a challenge to hit it. <br>Alternatively, press the "=" key on the keyboard. This may take even longer than clicking the icon.
You must repeat these clicks when you select another object. Again and again...

## Express Placement (in green)

The Express Placement macro creates a special panel for you. You may dock this panel to any suitable place. It shows three rows with X, Y, Z coordinates. These coordinates contain values and expression fields. They are available for editing with just one double click.

# Installation

## Addon Manager

Find [Express Placement](https://wiki.freecad.org/Macro_Express_Placement) in FreeCAD Addon Manager and install it.

## Direct Launch of Express Placement

You may download and use Express Placement addon immediately in your FreeCAD:

1. Download the express-placement.FCMacro file and place it in the User Macros folder inside your FreeCAD installation folder.
2. Execute it directly from the FreeCAD main menu Macro / Macros / User Macros.

## Installing Express Placement Toolbar Button

To have an ability to quickly switch on the Express Placement table, you may place a button to quickly execute this macro and bring up the Express Placement table:

1. Download the Express Placement.FCMacro file and place it in the User Macros folder inside your FreeCAD installation folder.
2. Select the Express Placement macro in the User Macros panel, invoked from the FreeCAD main menu Macro / Macros / User Macros.
3. Press the Toolbar button and follow the Walkthrough dialog to place the Express Placement button in the desired location in the FreeCAD toolbars.

# Usage

Just run the Express Placement macro directly or via the toolbar button, and you will see a new docked property window in your FreeCAD UI. You may drag it to any allowed place in the UI and close any time you won't need it. Next time when it will be required again - run the macro or press the toolbar button again to bring up the Express Placement window.

When you decide to change the placement of the selected object, just double-click on the desired cell in the Express Placement window and type a new value or edit the existing one. The new value will be directly written to your model. 

<br><hr><i>If you find this add-on useful and feel it's worth treating me to a couple-triple coffee cups in recognition of my work, at any time you may do it via [https://www.buymeacoffee.com/screeneroner ☕&nbsp;Buy&nbsp;me&nbsp;a&nbsp;coffee]</i>
