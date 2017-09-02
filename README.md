# HTML-Guide-Lines
## form has fields without LABEL elements or TITLE attributes. ##
  Screen readers use LABEL elements or TITLE attributes to describe form fields to non-sighted users. Without these, forms are very hard to use with a screen reader. Forms designed to be completed online shall allow people using assistive technology to access the information, field elements, and functionality required for completion and submission of the form, including all directions and cues.
## BUTTON element is empty and has no programmatically determined name. ##
  A programmatically determined name allows screen readers to tell the user what the control does. To add a name do one of the following:
    1. Add text between the BUTTON start and end tags.
    2. Add a TITLE attribute.
    3. Add an ARIA-LABELLEDBY attribute (not supported in all screen readers).
    4. Add an ARIA-LABEL attribute (not supported in all screen readers).
## Use LABEL elements for each data entry field to show what data is expected. ##
  Make sure each INPUT field has an associated LABEL describing the field.
## The 'button' role is unnecessary for element 'button'. ##
## Each A element must contain text or an IMG with an ALT attribute. ##
  Add text to the link, or ALT text if the link contains an image. If there is no link text or the ALT text is blank, screen readers have nothing to read, so read out the URL instead.
## Each A element must contain text or an IMG with an ALT attribute. ##
  Add text to the link, or ALT text if the link contains an image. If there is no link text or the ALT text is blank, screen readers have nothing to read, so read out the URL instead.
## This link is broken. The SRC or HREF is an empty string. ##
  HREF="" or SRC="" can cause unexpected effects such as traffic spikes or cookie corruption, and causes JavaScript error events to fire on Firefox.
## Users should be able to quickly look at each link and tell where it goes. ##
  Don't use generic link labels like "click here" or "read more" because they're hard to tell apart when users scan a page.
## No TITLE attributes found for the frames ##
  Add a TITLE attribute to each FRAME and IFRAME element (e.g. TITLE="Main Content"). Without a TITLE some screen readers read out the FRAME filename, which is usually meaningless.
  IFRAMEs with no title cause problems in:

    1. JAWS 14 and 15 with Firefox (the frame SRC filename is read instead)
    2. VoiceOver on OSX 10.9 (a meaningless title like "Frame twelve" is read out)
 ## The 'frameborder' attribute on the 'iframe' element is obsolete. Use CSS instead. ##
  Dont use 'frameborder' for 'iframe'. The equivalent of frameborder in css is border: 0px;. Add it to your iframe in css.
