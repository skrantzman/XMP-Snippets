# xmp-snippets README


[![](https://vsmarketplacebadge.apphb.com/version-short/SteveKrantzman.xmp-snippets.svg)](https://marketplace.visualstudio.com/items?itemName-SteveKrantzman.xmp-snippets) 
[![](https://vsmarketplacebadge.apphb.com/downloads-short/SteveKrantzman.xmp-snippets.svg)](https://marketplace.visualstudio.com/items?itemName-SteveKrantzman.xmp-snippets) 
[![](https://vsmarketplacebadge.apphb.com/rating-short/SteveKrantzman.xmp-snippets.svg)](https://marketplace.visualstudio.com/items?itemName-SteveKrantzman.xmp-snippets) 
[![](https://img.shields.io/badge/Dev--Community-XMP-orange.svg)](https://www.dnndev.com)

<p align="center"><img src="https://raw.githubusercontent.com/skrantzman/XMP-Snippets/master/XMP_Snippets_Logo.png" width="150" height="150" alt="XMP Snippets Logo"></p>
<br />

> __Reduce the time you spend on creating complex XMOD Pro forms and templates, as well as Form.X forms within XMP templates.  Author and edit XMP form and template .ascx files directly. The form and template editor built into XMP is a great tool, but you may prefer VS Code as your go-to HTML editor. Together they are a great combination - quickly write the bulk of your code in VS Code and fine tune it in the XMP editor.__

# XMP Snippets

XMP Snippets simply allows you to quickly scaffold simple to complex XMod Pro Templates and Forms. In addition there is also support for Form.X form controls as well. Currently there are 261 snippets for you to use, and it supports the direct editing of .ascx files.

XMP Snippets are very easy to use

* For XMP Template Controls start by typing __xt__, followed by the start of the desiered template control.
* For XMP Form Controls start by typing __xf__, followed by the start of the desiered form control.
* For Form.X Form Controls start by typing __fx__, followed by the start of the desiered Form.x control.
* For Direct Editing of XMP Template in ascx files start by typine ___xt__, folowed by the start of the desired template control.
* For Direct Editing of XMP Forms in ascx files start by typine ___xf__, folowed by the start of the desired template control.
* For Direct Editing of Form.x Forms in ascx files start by typine ___fx__, folowed by the start of the desired template control. 

## Benefits
There are many benefits to coding XMod Pro Templates and Forms in VS Code with XMP Snippets over the traditional method. A few are listed below:

* __All the benefits of the top rated code editor.__
* __Directly create and edit XMP form and template .ascx files.__
* __Code in VS Code and View in your browser side by side.__
* __Multiple Undos! Even undo past your last save as long as you have not closed the open file or VS Code.__
* __Easy Versioning, and can even use git.__
* __Quickly Scaffold projects in VS Code in one screen and copy and paste into the XMP Editor in another screen.__
* __Tab through each inserted control's properties to set their values.__


## Features

The XMP snippets are broken into three types.
1. Template Controls (xt or _xt)
2. Form Controls (xf or _xf)
3. Form.X Controls (fx or _fx)
    
> XMod Pro Templates and Forms, prefix with xt or xf accordingly. Then start to type the name of the desired XMod Pro control.

<p align="center"><img src="https://raw.githubusercontent.com/skrantzman/XMP-Snippets/master/XMP_Snippets_XMP_Features.gif"   alt="XMP Snippets XMP Features Animated GIF"></p>

<br />

> Form.X form controls in XMP Templates, prefix with fx. Then start to type the name of the desired Form.X control.

<p align="center"><img src="https://raw.githubusercontent.com/skrantzman/XMP-Snippets/master/XMP_Snippets_FormX_Features.gif"   alt="XMP Snippets Form.X Features Animated GIF"></p>

<br />

> Create and Edit XMP Form and Template ASCX files, prefix with _xf, _xt, or _fx. Then start to type the name of the desired Form.X control or template.

<p align="center"><img src="https://raw.githubusercontent.com/skrantzman/XMP-Snippets/master/XMP_Snippets_ASCX_Features.gif"   alt="XMP Snippets Form.X Features Animated GIF"></p>

## Requirements

No Requirements to create files.

Requirements to view files
* DNN instance running live or in dev environment. Open source and free [DNN Community Edition](https://www.dnnsoftware.com/community  "DNN Software Community Edition Page")
* XMod Pro module installed in DNN. No license required to run in dev environment [XMod Pro](https://www.dnndev.com  "XMod Pro Home Page")
* Optional - Form.X module installed in DNN. License Required [Form.X](http://reflectmediagroup.com/Products/XMod-Pro-Plugins/Details/prodid/18 "Form.X Home Page")

> To work with .ascx files you need to change the language mode of the files from "xml" to "html" or add the following to your VS Code settings json file: __"files.associations": {
    "*.ascx": "html"
    }__


## Known Issues

No known issues as of publish date

## Release Notes

__v 1.2.3__ 
- ### bug fix.
    - Reasigned ascx xmod:Template from _xf to _xt prefix.

__v 1.2.2__ 
- ### Added snippets and bug fix.
    - Added Section Comment snippet.
    - Fixed closing tag on SubmitCommands.

__v 1.2.1__ 
- ### Added snippets.
    - Added standard and ascx Join Functions

__v 1.2.0__ 
- ### Added Support for Direct Editing of XMP ASCX Files.
    - Added 52 _xt snippets for XMP template controls for ascx files.
    - Added 73 _xf snippets for XMP form controls for ascx files. 
    - Added &ensp;5 _fx snippets for Form.X form controls for ascx files. 
    - Added &ensp;1 _xp snippet for Token Replacement in XMP ascx files. 


