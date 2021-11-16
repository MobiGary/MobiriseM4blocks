# Changelog

All notable changes to this project will be documented in this file.

## Version 4.2 - MobiGaryExtension-v4.2.mbrext (2021-NOVEMBER-16)
- Various cog options are availabe to make settings of both blocks quicker to apply and provide flexibility for those Mobirise builder users who are not so comfortable editing HTML & CSS. 

  - <b>BLOCK 1: "MobiGary Configurable Mobirise Bootstrap Menu" - v3.6.</b><br>
    - Unchanged in this release.
     
  - <b>BLOCK 2: "MobiGary Configurable Mobirise Bootstrap Floating Contact Form" - v1.8 for witsec Mailform Extension v12.x</b><br>
    - Added 2 new slider controls to the gear icon for the file upload button text (if file upload enabled). These 2 new settings "Button Text Padding Top" & "Button Text Padding Bottom" enable fine control of the top and bottom padding of the "Choose File(s)" text actually on the upload button.<br>
    ![alt text](https://github.com/MobiGary/MobiriseM4blocks/blob/main/assets/images/upload-btn-txt-padding.jpg)
    ![alt text](https://github.com/MobiGary/MobiriseM4blocks/blob/main/assets/images/upload-btn.jpg)
    - Set the font family in CSS for the File Upload Button Text to "font-family: Arial, Helvetica, sans-serif". This resolves an issue seen in Mobirise M5 themed projects which use a font with long tails on lower case letters such as the letter "f" in the "Calligraffirri" font.    
    - **Prerequisites**: This version of the floating button/form is only compatible with witsec mailform extension release version 12 (or higher) [URL here https://witsec.nl/extension-mailform.html]

**Download**: https://github.com/MobiGary/MobiriseM4blocks/raw/main/MobiGaryExtension-v4.2.mbrext

## Version 4.1 - MobiGaryExtension-v4.1.mbrext (2021-NOVEMBER-10)
- Various cog options are availabe to make settings of both blocks quicker to apply and provide flexibility for those Mobirise builder users who are not so comfortable editing HTML & CSS. 

  - <b>BLOCK 1: "MobiGary Configurable Mobirise Bootstrap Menu" - v3.6.</b><br>
    - Added "Menu Top Margin on scroll sticky px" gear icon option for users who wish to have a gap appear above the menu when scrolled if “MM Sticky” and “Menu Top Margin on scroll sticky px” are configured. The default for “Menu Top Margin on scroll sticky px” is 0 so no gap is shown by default when “MM Sticky” selected.
    - Fixed a menu transparency issue. If "MM transparent" is enabled the menu will be transparent before it is scrolled. Once scrolled it will then use the opacity setting configured in "MM BG Opacity" slider.
    - Fixed an issue regarding menu background color if "MM Collapsed" is selected. The "MM BG Color" configuration is now used for collapsed menus in addition to non-collapsed menus.
    - Fixed an issue regarding social icon alignment (if icons enabled) when menu has "MM Collapsed" selected.
 
    
  - <b>BLOCK 2: "MobiGary Configurable Mobirise Bootstrap Floating Contact Form" - v1.7 for witsec Mailform Extension v12.x</b><br>
    - Added 4 new slider control settings to the gear icon which enables fine control of the font used for input fields and the file upload button (if enabled). These are contained in the existing "Form font sizes and weights" section of the gear icon: "Input Field Text Size", "Input Field Text Weight", "File Upload Text Size" & "File Upload Text Weight"
    - **Prerequisites**: This version of the floating button/form is only compatible with witsec mailform extension release version 12 (or higher) [URL here https://witsec.nl/extension-mailform.html]



## Version 4.0 - MobiGaryExtension-v4.0.mbrext (2021-OCTOBER-23)
- Various cog options are availabe to make settings of both blocks quicker to apply and provide flexibility for those Mobirise builder users who are not so comfoprtable editing CSS. 

  - <b>BLOCK 1: MobiGary Configurable Mobirise Bootstrap Menu v3.5.</b><br>
    - Modified menu block HTML to allow a link from the menu icons (if enabled) to close the mobile hamburger menu correctly if the link is to a block on the page. Previously, in mobile hambuger mode, a link to a block on the page from an icon in the menu would correctly skip to the block specified, but would not close the menu itself. This icon DIV was originally intended to link to external resources only (e.g. for social media) so this was not an issue if only used for an external URL. 
    
  - <b>BLOCK 2: MobiGary Configurable Mobirise Bootstrap Floating Contact Form v1.6 for witsec Mailform Extension v12.x</b><br>
    - Modified the wording in the floating block if "reCAPTCHA Terms" is enabled in the gear icon. The wording now matches the exact requirements specified by google should you wish to hide the recaptcha v3 badge in witsec mailform site settings. Further information URL here: https://developers.google.com/recaptcha/docs/faq - "I'd like to hide the reCAPTCHA badge. What is allowed? section"
    - Prerequisites: This version of the floating button/form is only compatible with witsec mailform extension release version 12 (or higher) [URL here https://witsec.nl/extension-mailform.html]


## Version 3.9 - MobiGaryExtension-v3.9.mbrext (2021-OCTOBER-01)
- Various cog options are availabe to make settings of both blocks quicker to apply and provide flexibility for those Mobirise builder users who are not so comfoprtable editing CSS. 

  - <b>BLOCK 1: MobiGary Configurable Mobirise Bootstrap Menu v3.4.</b><br>
    - Unchanged in this release.

  - <b>BLOCK 2: MobiGary Configurable Mobirise Bootstrap Floating Contact Form v1.5 for witsec Mailform Extension v12.x</b><br>
    - Moved the JavaScript that controls the loading and closing of the floating form out of the block HTML to a JS plugin. This avoids any accidental changes (or deletion) to the JavaScript if users are editing the block HTML
    - Prerequisites: This version of the floating button/form is only compatible with witsec mailform extension release version 12 (or higher) [URL here https://witsec.nl/extension-mailform.html]

## Version 3.8 - MobiGaryExtension-v3.8.mbrext (2021-SEPTEMBER-19)
- Various cog options are availabe to make settings of both blocks quicker to apply and provide flexibility for those Mobirise builder users who are not so comfoprtable editing CSS. 

  - <b>BLOCK 1: MobiGary Configurable Mobirise Bootstrap Menu v3.4.</b><br>
    - Unchanged in this release.

  - <b>BLOCK 2: MobiGary Configurable Mobirise Bootstrap Floating Contact Form v1.4 for witsec Mailform Extension v12.x</b><br>
    - **UPDATED FOLLOWING THE RELEASE OF WITSEC MAILFORM V12**
    - File Upload Option - added new "File Upload" gear icon option to match new feature available in witsec mailform v12 (release version)
    - File Upload Option - added X & Y gear icon positioning for the new file upload button so it can be finely adjusted as required in the different Mobirise M4 and M5 themes. Unfortunately different themes makes a "one size fits all" alignment difficult, so adding the sliders seems the best approach.
    - File Upload Option - added various file upload button styling options. 
    - Floating Button Positioning - modified X and Y axis positioning gear icon sliders to allow in increments of 1px rather than 5px (in previous version) to allow even greater positioning flexibility of the floating button.
    - Floating Form Positioning - modified X and Y axis positioning gear icon sliders to allow in increments of 1px rather than 5px (in previous version) to allow even greater positioning flexibility of the floating form.
    - Advanced - added new "Advanced" section of gear icon which contain a new option "Show Message Topic" which is a "select" type field. To customize the contents of the select options presented, usage of a code editor is required to edit the block HTML. This is why it has been placed in an "Advanced" category as not all users will have a code editor or be comfortable making those changes. The new option is OFF by default.
    - General - reordered some of the gear icon options to tidy things up and make it easier to spot particular groups of settings.
    - HTML changes - set bottom padding on each main field "pb-1" instead of "pb-2" (in previous version) to bring fields slightly closer together and therefore use less screen real-estate.
    - Prerequisites: This version of the floating button/form is only compatible with witsec mailform extension release version 12 (or higher) [URL here https://witsec.nl/extension-mailform.html]

## Version 3.7 - MobiGaryExtension-v3.7.mbrext (2021-AUGUST-10)
- Various cog options are availabe to make settings of both blocks quicker to apply and provide flexibility for those Mobirise builder users who are not so comfoprtable editing CSS. 

  - <b>BLOCK 1: MobiGary Configurable Mobirise Bootstrap Menu v3.4.</b><br>
    - Unchanged in this release.

  - <b>BLOCK 2: MobiGary Configurable Mobirise Bootstrap Floating Contact Form v1.3 for witsec Mailform Extension v11.x</b><br>
    - Changed block help to correct code for launching floating form from an iconfont (it previously had a missing double quote).
    - Added extra option in block help to show how to launch floating form from a regular Mobirise Builder link "..." option.
    - Changed z-index of floating button to 5001 from 5000 so it is always on top of floating form (which is set to 5000) if they overlap.
    - Added an extra line of code to togglefade javascript (which opens and closes the floating form) to prevent the web browser initiating a "back to top" action on the page when form launched under certian situations.


## Version 3.6 - MobiGaryExtension-v3.6.mbrext (2021-AUGUST-01)
- Various cog options are availabe to make settings of both blocks quicker to apply and provide flexibility for those Mobirise builder users who are not so comfoprtable editing CSS. 

  - <b>BLOCK 1: MobiGary Configurable Mobirise Bootstrap Menu v3.4.</b><br>
    - Made block ready for when Mobirise releases live versions of its Bootstrap 5 builder and bootstrap 5 based themes (curently 5.3.15 beta with "Mobirise 5" or "GlassM5"). Several HTML and CSS changes.
    - NOTE: This bock currently has an incompatibility with the hamburger menu X (to close menu) not showing correctly when menu is open in hamburger menu in the new bootstrap 5 themes (e.g. 5.3.15 beta with "Mobirise 5" or "GlassM5"). The hamburger Menu still opens correctly but does not show the X as previously. Issue is also evident in the standard sandard Mobirise 5 menu. Issue reported to Mobirise and they have subsequently fixed the issue in 5.3.16 beta fo the Mobirise 5 theme, but unfortunately the issue remains for the Glass M5 theme.

  - <b>BLOCK 2: MobiGary Configurable Mobirise Bootstrap Floating Contact Form v1.2 for witsec Mailform Extension v11.x</b><br>
    - Made block ready for when Mobirise releases live versions of its Bootstrap 5 builder and bootstrap 5 based themes (curently 5.3.15 beta with "Mobirise 5" or "GlassM5"). Several HTML and CSS changes for "button form launch", "button form toggle fade" (new JavaScript in block and extra CSS) and "floating form X close icon position" (extra CSS) to allow all to work correctly with new Mobirise bootstrap 5 based themes. These bootstrap 5 based themes no longer use jQuery in latest beta and also inherit some CSS setings differenty from style.css than previously. Tested in builder v5.3.15 beta. This 1.2 verion is compatible with the older M4 themes that use jQuery and the newer M5 bootstrap 5 themes that do not use jQuery.
    - NOTE: witsec will be releasing a updated v12 of his mailform in the near future that does not use any jQuery.


## Version 3.5 - MobiGaryExtension-v3.5.mbrext (2021-APRIL-17) 
- Various cog options are availabe to make settings of both blocks quicker to apply and provide flexibility for those Mobirise builder users who are not so comfoprtable editing CSS. 

  - <b>BLOCK 1: MobiGary Configurable Mobirise Bootstrap Menu v3.3.</b><br>
    - Unchanged in this release.

  - <b>BLOCK 2: MobiGary Configurable Mobirise Bootstrap Floating Contact Form v1.1 for witsec Mailform Extension v11.</b><br>
    - Several changes to deal with inconsistencies inherited  in a few Mobirise themes that caused formatting issues to such items as buttons, iconfont, padding and margins.
    - Added new submit button and field text padding options on the gear icon slider.
    - It requires the witsec mailform v11 ((https://witsec.nl/extension-mailform.html) as a prerequisite.


## Version 3.4 - MobiGaryExtension-v3.4.mbrext (2021-APRIL-16)
- This is the initial release of the MobiGary Configurable Mobirise Blocks Extension with multiple blocks included. In previous versions (v3.3 and earlier) the extension only had the one menu block. Various cog options are availabe to make settings of both blocks quicker to apply and provide flexibility for those Mobirise builder users who are not so comfoprtable editing CSS. 

  - <b>BLOCK 1: MobiGary Configurable Mobirise Bootstrap Menu v3.3.</b><br>
    - This is the same version of the menu that previously was stored here: https://github.com/MobiGary/Mobirise-Configurable-Bootstrap-Menu. It has not changed in this v3.4 release extension but it is now in an extension with multile blocks (rather than being and extension just for the MobiGary Menu block).

  - <b>BLOCK 2: MobiGary Configurable Mobirise Bootstrap Floating Contact Form v1.0 for witsec Mailform Extension v11.</b><br>
    - The first version of the configurable floating block that requires the witsec mailform v11 ((https://witsec.nl/extension-mailform.html) as a prerequisite.

## Hstorical changelog details for the MobiGary Configurable Mobirise Bootstrap Menu prior to v3.4 when it was an singe block extension in its own separate Github repository
-  Historical changes for the MobiGary Configurable Menu are detailed in the old changelog: https://github.com/MobiGary/Mobirise-Configurable-Bootstrap-Menu/blob/master/CHANGELOG.md

