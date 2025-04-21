# Frontend Mentor - Ricky's QR code Component Solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

I first started off with the HTML making sure I got all my containers in placed, then moved onto the CSS and placing everything within the center of the viewport, and added all the background-colors in order for me to have a better view of the 'White Card Container' in center and for better sizing. I tried to approach it from my own understading at first, and input as much as I could in order for me to really get into the notion of figuring it out by myself, instead of always following or looking at hints. 
### Screenshot

<img src="./Mobile Design .png"/>
<img src="./Desktop Design.png"/>

## My process

HTML: This part of the code was very easy and simple addition of classes in order to group for better positioning and sizing. Started with a flex-container, then card class, and finally a text class (more on this in the 'What I learned' section). 

CSS: This part of the code I started with the body, flex-container(i.e., centering it within the viewport), img, card container, and then the text (more on this in the 'What I learned' section). 


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow 
- Mobile-second workflow

### What I learned

The learning curve: 
- The spacing on margin-left and margin-left for mobile design 
- I overshot the actual size and made it way bigger than the actual design
- Image sizing
- The font-size on the paragrpah of 15px; I added 40px because 15px was to small
- added way more than what I needed within the .card container

I ended looking at the <a href="https://www.youtube.com/watch?v=5BBYPntB-GY&list=PLcZZlEf3w738Bv45a8yI_iIv2OGx_JLvz&index=12" target="_blank">Mr Coder's code example</a> that was a part of his Day 11 challenge. 

After reviewing his code, I realzied that the solution to my problem was easier then I expected: 

- The spacing only required a: 
margin: 0 1em; (top/right , bottom/left) which was targeting the sides.

- The sizing of the overall QR Code was because I was focusing on the design itself that I didn't realize how close to the edges I were. 

I notice this after I looked at the Preview.jpg which shows the overall shot of the QR Code, and lead me to another realization: 

- My image was within the .card container so I didn't need to specifically size the image, which could lead to unreposiveness I think?

Anyways, Mr Coder address this by giving a max-width of 360px and making the image 100%, in return, the image ends up sizing iteself with whatever sizing the parent container has (i.e., the card container). 

- I put different font-sizes for all tags but it became difficult once I started playing around with the card sizing

Mr Coder only put 15px font-size for the .card container and that was it. It made sense becasue the tags like h1, or p have different font-sizing and relly I overlooked at first getting the correct sizing which led me to my last problem :

- The .text class was something I didn't consider as I was trying to space the spacae bwetween the header and parargraph with line-height and margin. Disrupting the flow of the card and not taking the box-border into consideration.

Mr Coder added a .text container keeping the h1, and p as child elements. This targeted the spacing between the image and text and the paragraph and bottom of the card. All that was left was a h1 padding-bottom of 15px. 

- I also had a display: flex with a flex-direction: column to line up the image with the tags but:

It was unecessary because the flow of the content was already flowing like a a column, so deleting this part didn't effect the outcome. As a matter of fact, nothing changed once I deleted it- it was jsut extra useless code. 


### Continued development

I'm going to continue working on the padding, margin, and understanding the flow of the content. Although these are very east concepts to understand, while coding, sometimes I overthing the process and forget the flow of the tags. I will aslo focus on keeping my code clear and simple and making sure it makes sense in order to repeat code and not put code that isn't necessary. 


## Author

- Website - [https://rarroyoharo.com](https://www.your-site.com)
- Frontend Mentor - [@RiickyRiick](https://www.frontendmentor.io/profile/RiickyRiick)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Again Check out Mr Coder's YouTube Channel, I will defintely continue using his coding examples when I get stuck on a project. Thanks again Mr Coder!
(https://www.youtube.com/watch?v=5BBYPntB-GY&list=PLcZZlEf3w738Bv45a8yI_iIv2OGx_JLvz&index=12) 
