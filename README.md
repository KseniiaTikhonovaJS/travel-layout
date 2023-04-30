# Project "travel-layout"

## Review
* Introduction
* Installation and usage
* Figma
* Description

### Introduction

Educational project "travel-layout", adaptive layout.
Building layout according to the layout in Figma;
When building an adaptive layout, I started from the screen sizes: 320, 768, 1024 and 1280 pixels (according to the layout).
The site must display correctly in Firefox, Google Chrome or Yandex Browser;

### Installation and usage

1. Clone the repository to your local machine using the following command:

```
git clone https://github.com/KseniiaTikhonovaJS/travel-layout.git
```

2. Choose "Open with Live Server" from context menu on the item "index.html"

3. To use "travel-layout", you will need to install extension "Live Server" for Visual Studio. 

### Figma

* https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-mobile?node-id=28503%3A0

### Description:

In this project work, I used the following **technologies:**
* building grids: Flexbox layout and Grid Layout;
* positioning and advanced semantics of the HTML language;
* naming classes according to the rules of BEM and building the file structure of the project according to the rules of Nested BEM;
* connecting styles in a separate file;
* using Perfect Pixel to meet requirements: "element widths and padding differ from layout by no more than 30px at breakpoints: 1280px, 1024px. And 10px at breakpoints: 768px, 320px";
* all links and clickable elements have a hover state of :hover.

To **build an adaptive** layout, I applied:
* relative sizes of blocks and text elements;
* optimization of fonts for devices with different resolutions;
* the calc() function for uniform site behavior between given breakpoints in the layout;
* Meta tags for correct page scaling;
* media queries.
