# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](/images/my-solution.png)


### Links

- Solution URL: [My Solution](https://github.com/limeiscool/Testimonials-grid-section)
- Live Site URL: [Live Solution Site](https://limeiscool.github.io/Testimonials-grid-section/)

## My process

Mobile-First Approach Heavy use of CSS Grid.

### Built with

- CSS custom properties
- minimal Flexbox
- Heavy use of CSS Grid
- Mobile-first workflow

### What I learned

The use of Grid-template-areas really helped this challenge become alot easier, once i understood it putting it to use was fairly easy.

```.grid-container {
    grid-template-areas: 
    'one one two three'
    'four five five three';
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
  }
  ```

### Continued development

careful planning and sometimes best to scrap an idea if its creating more problems then solutions, trying a new aproach you may realize you completly overthought the challenge the first time and maybe even a few more times after that. However with a mind set that it can be done, you learn alot! Turns out my knowledge of Grid wasnt as good as i thought and spent alot of time having to review grid, i was unable to understand how to span across 2 columns or rows properly without thing getting really messed up. However with the video linked below helped me gained a better understanding. 

### Useful resources

- [resource 1](https://www.youtube.com/watch?v=rg7Fvvl3taU) - Helpful video for breaking down CSS grid using this Challenge as an example!

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@limeiscool](https://www.frontendmentor.io/profile/limeiscool)

## Acknowledgments

Huge shout out to Kevin Powell from linked video above for his approach with grid-template-areas i used.
