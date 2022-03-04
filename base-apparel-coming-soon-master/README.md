# Frontend Mentor - Base Apparel coming soon page solution

This is a solution to the [Base Apparel coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot

![](/base-apparel-coming-soon-master/images/baseapparel.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- js
- scss

### What I learned

I learned a lot about focusing interactive elements and ensuring that they haev sematic markup. I'd like to pratice these more. As they kind of gave me a tough time.

```
//Form Validations
.container form{
    position: relative;
    display: block;
    width: 100%;
    height: 50px;
    margin: 0 auto; 
    outline: none;
   
}
.container form .error-icon {
    display: inline-block;
    position: absolute;
    top: 24%;
    right: 24%;
    display: none;

    @media (min-width: 375px) and (min-width:450px){
        display: inline-block;
        position: absolute;
        top: 24%;
        right: 26%;
        display: none;
         
    }
 
}

.container form.error .error-icon {
    display: block;
    color: red;
}
.container form.error .error-text {
    display: block;
    color: rgb(219, 1, 1);
    font-size: 1rem;
}
.container form.error input {
    border: 1px solid red;
}
.container form .error-text {
    position: absolute;
    top: 120%;
    left: 10%;
    font-size: var(--fs-base);
    display: none;
    
}

.container form input::placeholder {
    color: var(--desaturatedRed);
    opacity: .8;
}

```

### Continued development

I will continue to foucs on collaboration. I'm open to collaborate on projects. If you are interested let me know! 

### Useful resources

- [mdn web docs_](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Understanding_WCAG/Keyboard#clickable_elements_must_be_focusable_and_should_have_interactive_semantics) - This helped me to understand how important accessibility isa.



## Author

- Website - [Amario](https://www.linkedin.com/in/amario-jones/)
- Frontend Mentor - [@Qstar12](https://www.frontendmentor.io/profile/Qstar12)
- Twitter - [@jones_amario](https://twitter.com/jones_amario)



## Acknowledgments

@ https://github.com/Amani-dot


