# Sign Editor
A web-based editor for digital street signage  
Designed and developed by Daniel Darnell  
Written in JavaScript, HTML, CSS, and PHP  
*The source code for this product is proprietary and cannot be made public. This README only provides non-proprietary details about the product for informational purposes.*

## About
This web-based editor allows customers to remotely control several different models of digital road signs in the field. The editor can access any sign from anywhere, in all major browsers.  
  
The editor is written in vanilla JavaScript, with an interface designed in HTML and CSS. Sent messages are communicated to signs in the field through a PHP backend on the server, which then connects to the sign controller wirelessly. The editor supports multiple messages per sign, multiple sign styles (pixel array, monospaced, line spaced), kerning, leading, different fonts, and several common default messages.
  
The editor is currently in use by hundreds of individual customers, local municipalities, state departments of transportation, and police departments.

## Screenshots
*Sign Editor displaying "Hello, world!" in a bolded font:*  
<img src="/img/page1.png" width="550px">  
  
*Sign Editor displaying "This text blinks!" in a normal font with blinking enabled:*  
<img src="/img/page2.png" width="550px">  
  
*Sign Editor displaying "You can justify text too" in a normal font justified to the left:*  
<img src="/img/page3.png" width="550px">  
  
*Sign Editor displaying "KERN" in a short font with wide kerning:*  
<img src="/img/page4.png" width="550px">  
  
*Sign Editor sending stored pages to sign in the field:*  
<img src="/img/page1-sending.png" width="550px">
