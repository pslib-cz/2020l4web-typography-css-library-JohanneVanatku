# Typography CSS library
**Author:** *Johanne Vaňátků*
## Demo
You can check the demo [here](JohanneVanatku.github.io)
## Description
This CSS library is intended as a stylesheet for webpages. It includes styling for different headers, lists, tables, images including float and full site width images and simple navigation.
## Implementation
copy and paste following links in the head tag of your website:
```html
<link rel="stylesheet" href="./style.css">
<link rel="stylesheet" href="./fonts.css">
```
## Usage
for a hidden menu in smaller resolutions, use this code in your html:
```html
    <nav>
            <ul id="nav">
                <a href=""><li>nav</li></a>
                <a href=""><li>nav</li></a>
                <a href=""><li>nav</li></a>
                <a href=""><li>nav</li></a>
                <a href=""><li>nav</li></a>
            </ul>
            <a href="#nav" class="navActivator">menu</a>
        </nav>
```
library uses these tags:
* .capOnHover for caption that will appear on image on hover
* .pCitation for big centered messages
* .floatLeft and .floatRight for images that will float on either side
* .tableTopHead for table headings on top of the table
* .tableSideHead for table headings on the side of the table
* .tableCorner for a specific style of an empty corner between table headings
* .pageTitle for the title of the page
* .footerContainer for a specific style of the page footer

