# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview
This project is QR card component with a short description that highlight the importance of frontend challenges.

### Screenshot

![](./images/Screenshot%202025-08-27%20131458.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS3 custom properties
- Flexbox


### What I learned

Building this project has taught me that flexbox works on only the children of the parent element.For instance,initially,I was apply flexbox on the parent div of the qr code image and the brief description for I wanted the it to be positioned as in the model design but was'nt working rather on the qr code image and the text.So i decided to apply it on the body and it worked.So i inquired from chatgpt and it explained to me that flexbox works on children excluding the parent. 

 code snippets, see below:

```html
     <div class="card">
        <img class="card-image" src="./images/image-qr-code.png" alt="grcode">
        <h3>Improve your front-end  <br> skills by building projects</h3>
        <p> Scan the QR code to visit Frontend <br> Mentor and take your coding skills <br>to the next level </p>
      </div>
  
```
```css
    body{
     display: flex;
     flex-direction: column;
     justify-content: center;
     align-items: center;
     min-height: 100vh;
     background-color: hsl(212, 45%, 89%) ;
   }
```
 ### Continued development

In future projects,I will be focusing on how to group content accordingly in the html file to aid in effective and easy styling.



## Author

- Website - [Joyce Abbey](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/  yourusername)


## Acknowledgments

I am most grateful to Nathan Sodja (my mentor) for recommending frontend mentor to me.


