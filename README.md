# StyleGuideSiteExample
Implementing the practices listed in the style guide I am building

1. GENERAL-<br>
A. Uses HTTPS protocol, unless files are not available over it.<br>
B. 2 space indentation.<br>
C. Everything should be lowercase.<br>
D. Contains no trailing whitespaces.<br>
E. TODO marks action items.<br>
F. Comments must be used with hotfixes or quick fixes.  Create a bug ticket in not ready status to fix the code. Format should include quick summary, your name, ticket causing hotfix and ticket fixing hotfix.

2. HTML-<br>
  A. Use double quotes.<br>
  B. Use tags for their intended purposes as much as possible. Avoid unnessecary divs.<br>
  C. No JS or CSS in HTML files, keep markup, styling, and scripting seperate.<br>
  D. Minimize the number of stylesheets linked.<br>
  E. Use UTF-8 as encoding.<br>
  F. No entity references, with the exception of reserved words like <, &, and no-break.<br>
  G. Omit optionsl tags except head, body, and HTML. List of some <a href="https://meiert.com/en/blog/optional-tags-in-html-4/">here</a>.<br>
  H. Use HTML5<br>
  I. <a href="https://validator.w3.org/nu/">Check validity</a> of HTML code.<br>
  J. No inline styling permitted without a comment containting ticket causing the hotfix, the bug ticket to fix it later, name, and a short description.<br>
  K.Always declare !doctype html and meta charset="utf-8" and meta name="viewport" content="width=device-width, initial-scale=1.0" in all HTML documents. Use the lowercase to maintain lowercase consistency.<br>
  L. Use HTML as text/html not XHTML.<br>
  M. Only use .html, not .htm.<br>
  N. Do not close void elements (ex. br).<br>
  O. Check your tags for depreciation (ex. its now em & strong instead of i & b).<br>
  P. Do not use spaces on either side of the equals sign in attributes.<br>
  Q. Do not use the type attribute for scripts and stylesheets, unless not using CSS and JS. text/CSS and text/JavaScript are defaults.<br>
  R. Always use alternative contents (alts) for all multimedia, even if it doesn't need one. It helps the browser parse the page so imclude it and leave the quotes empty.<br>
  S. New line for every block, list, or table element and index each one. Indent child elements of block, list, or table elements.  If whitespace is an issue around li elements, this can go on one line.<br>
  T. Break long lines (wrap) with each continuation line indented 4 spaces from the original line.
  U. If you comment out but do not delete code, you must leave a comment.<br>
  V. Single line comments should be formatted with one space between the tag beginning and the content on both side.<br>
  W. Multi line comments should have the tag beginning on the first line, then move to a new indented line for the comment content, and then place the end of the tag directly below the last comment line with indentation in line with the opening tag.<br>

  
3. CSS-<br>
  A. Use single quotes<br>
  B. <a href="https://jigsaw.w3.org/css-validator/">Validate your css</a>.<br>
  C. No reuse of classes intended for other purposes.<br>
  D. Class and ID names describe what they do. Generic naming allowed when applicable<br>
  E. All words in ID and Class names should be seperated by a hyphen. No other characters allowed.<br>
  F. When implementing type selectors, only use element names with IDs and/or classes unless absolutely necessary.<br>
  G. Shorthand properties should always be used when possible.  This list changes but currently using background, font, margin, & border.<br>
  H. No leading 0's.<br>
  I. No units after 0 values.<br>
  J. Use 3 character hex color values when permitted.<br>
  K. Application specific prefixes in use if code base is large enough.<br>
  L. Declarations should be in alphabetical order unless its a vendor specific prefix, in which case use the first letter of the css property.<br>
  M. All block content indented.<br>
  N. Property names should have a space between colon and the value, and no other spaces, including between the value and end semi-colon.<br>
  O. Opening braces of a block should be on the same line as the selector with one space between them.  The closing brace of the block should be on the line directly below the last declaration and in line with the front of the block.<br>
  P. If a block has multiple selectors, each selector in the block should be on a new line with a comma following all but the last.<br>
  Q. Always one line break between rule blocks.<br>
  R. Nested CSS and any time important! is used there needs to be a comment directly above the top line of the block.<br>
  
4. JS-<br>
  A.
