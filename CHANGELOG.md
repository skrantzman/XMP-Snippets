# Change Log
All notable changes to the "xmp-snippets" extension will be documented in this file.

## Unreleased
- Add support for user requests as they are evaluated.

## [1.2.62]
- ### Fixed Errors in ControlDataSource controls by adding / to closing tags.

## [1.2.61]
- ### Fixed Errors in Form.X fx:AddButton and fx:EditButton template contorls.

## [1.2.60]
- ### Add Token Snippets for xmp and aspx files (22 new snippets total).
    - Added the following token types for both xmp (copy and paste), and aspx (direct editing) file types. Most tokens snippets have selectable value tab stops.
        * Cookie
        * DateAdd
        * Data Parameter
        * Form Parameter
        * Join
        * Module
        * Page
        * Portal
        * Request
        * URL
        * User

## [1.2.53]
- ### Update.
    - Updated "Value" reference in _xt snippets from [[Token Name ]] to correct aspx style reference <%#Eval("Values")("Token Name")%>, which displays as [[Token Name]] in XMP Editor.

## [1.2.52]
- ### Bug fixes.
    - Fixed missing "/" in closing DetailDataSource tags. 
    - Moved both DetailDataSource and ListDataSource tags from xf, _xf to xt and _xt
    - Fixed missing Display= in xmod:Redirect tags

## [1.2.51]
- ### Added Snippets and bug fixes.
    - Fixed _xf Form snippet. Added closing slash in a text control that was throwing an error. 
    - Added _xf Basic Form snippt
    - Added Separate _xf snippets for AddForm, AddSuccess, EditForm, and EditSuccess templates

## [1.2.5]
- ### Added Snippets and bug fixes.
    - Added xf Output Parameter snippet
    - Added fx and _fx snippets for SilentPost, SqlCommand, and Twillo actions.
    - Fixed both the _fx fx:Addbutton and _fx fx:EditButton controls - missing runat="server"

- ### bug fix.
    - Added 'runat="server"' to _fx FormX InLine Edit Form Template_ascx

## [1.2.4]
- ### bug fix.
    - Added 'runat="server"' to _fx FormX InLine Edit Form Template_ascx

## [1.2.3]
- ### bug fix.
    - Reassigned ascx xmod:Template from _xf to _xt prefix.

## [1.2.2] - 02/15/2019 
- ### Added snippets and bug fix.
    - Added Section Comment snippet.
    - Fixed closing tag on SubmitCommands.

## [1.2.1] - 02/14/2019 
- ### Added snippets.
    - Added standard and ascx Join Functions

## [1.2.0] - 02/13/2019
- ### Added Support for Direct Editing of XMP ASCX Files.
    - Added 52 _xt snippets for XMP templates controls for ascx files.
    - Added 73 _xf snippets for XMP forms controls for ascx files. 
    - Added  5 _fx snippets for Form.X form controls for ascx files. 
    - Added  1 _xp snippet for Token Replacement in XMP ascx files.  

## [1.1.0] - 02/11/2019
- ### Added Support for Tab Stops.
    - After inserting controls via a snippet, you can now tab through the control's properties to set their values.

## [1.0.1] - 02/9/2019
- ### Bug fixes.

## [1.0.0] - 02/8/2019
- ### Initial release.
    - Contains 128 snippets for XMP Template, XMP Form and Form.X Controls.
      - 52 xt snippets for XMP templates controls.
      - 70 xf snippets for XMP forms controls.
      -  6 fx snippets for Form.X form controls.