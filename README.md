# Confirmation Email


## HTML Files

There are two _static_ HTML files:

1. `confirmation.html` - the source file for changes
2. `confirmation-inline.html` - the same as above with inlined CSS in order to improve render support in Outlook. 

You can use IDE or web tooling to inline the CSS after making changes to the source template.

## Images

The image folder `/img` contains the images required for the template to look right. In reality these would be served dynamically for the studio site the confirmation concerns. 


## Useful information

1. The Session Details tables are duplicated in the code for better mobile support. The desktop table shows by default and the mobile table has inline `display: none;`. There is a media query to switch them at < 600px viewport.
2. There is a `.brand` class that would need adjusting per studio in order to get the emails to match the studio site brand.
