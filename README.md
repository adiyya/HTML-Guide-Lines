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
