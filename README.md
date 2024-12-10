# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)
![](/solutionImages/Desktop1.JPG)
![](/solutionImages/Desktop2.JPG)
![](/solutionImages/Desktop3.JPG)
![](/solutionImages/Desktop4.JPG)
![](/solutionImages/Mobile1.JPG)
![](/solutionImages/Mobile2.JPG)
![](/solutionImages/Mobile3.JPG)
![](/solutionImages/Mobile4.JPG)
![](/solutionImages/Mobile5.JPG)
![](/solutionImages/Mobile6.JPG)
![](/solutionImages/Mobile7.JPG)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid primary, but with several flexbox rows
- Mobile-first workflow

### What I learned

I wanted to use grid exclusively, and I tried a variety of ways to display the grid initially with a 12 column responsive based on W3 Schools, but I ended up with this grid area layout instead incorporating the flexbox elements in a few rows because it seemed to make more sense.

```html of one flexbox structure.
	<div class="item flexcontainer item4" style="margin-top: 50px;">
  		<img src="images/logo-google.png" class="flexitem item4a">
		<img src="images/logo-ibm.png" class="flexitem item4b">
		<img src="images/logo-microsoft.png" class="flexitem item4c">
		<img src="images/logo-hp.png" class="flexitem item4d">
		<img src="images/logo-vector-graphics.png" class="flexitem item4e">
  	</div>
```
```css
.flexcontainer {
	display: flex;
  flex-direction: column;
	align-items: center;
  gap: 50px 0px;
  }

.flexitem {
	max-width: 250px;
	width: 100%;
	height: auto;
  margin: 5px;
	flex: "0 1 125px";
}

@media only screen and (min-width: 768px) {

  .flexcontainer {
    flex-direction: row;
	  justify-content: space-evenly;
	  width: 100%;
   }

   	.flexitem {
	  max-width: 150px;
	  width: 100%;
	  height: auto;
    margin: 5px;
	  flex: "0 1 125px";
  }
}
```


### Continued development

I think spending some more time in looking at Grid to get this responsive instead of incorporating flexbox would be something I'd like to investigate. Also my CSS file seems a little haphazardly put together, so I like to spend more time making that look pretty.

### Useful resources

- [Example resource 1](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is my favorite CSS Flexbox resource.
- [Example resource 2](https://css-tricks.com/snippets/css/complete-guide-grid/) - This is my go to CSS Grid resource. 
I also used Google and ChatGPT to help me figure out a few things with why some of the code wasn't working properly.






