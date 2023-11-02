# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

The below is the responsive mobile view of the project
![](./screenshots/mobile%20view%20image.PNG)


The below is the responsive desktop view of the project
![](./screenshots/desktop%20view%20image.PNG)



## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Screen Reader Accessibility
- Mobile-first workflow

### What I learned

- I was practice using figure element along with figcaption.

```html
<figure>
  <img src="./images/image-qr-code.png" alt="qr code image" title="Scan this code to watch nothing happen" width="576" height="576" loading="lazy">
  <figcaption>This is a QR Code Image</figcaption>
</figure>
```

- I was able to practice working on responsive images.
- I was able to practice the use of placing elements off-screen to aid visually impaired users via the use of CSS position property. That way, i was able to move the figcaption element off-screen while still leaving it in the document flow for it to easily be read.

```css
figcaption {
  position: absolute;
  left: -1000px;
}
```

### Continued development

- This was quite a simple project to execute. I didn't add javaScript to it now but could do so in the future if an idea comes to mind.


### Useful resources

- [Link to Mr. Dave Gray's Youtube Channel](https://www.youtube.com/@DaveGrayTeachesCode) - His videos can turn you to a full stack web developer.
- [Link to Mr. Dave Gray's CSS Tutorial](https://www.youtube.com/watch?v=n4R2E7O-Ngo) - This is an 11hrs video that can help you understand CSS better. It is about 11hrs long. Take your time.
- [Link to freeCodeCamp Youtube page](https://www.youtube.com/@freecodecamp) - This is a rich repository of knowledge. I found Mr. Gray here.

## Author

- email address - [idemudiamahie23@gmail.com]
- Twitter - [@mahie_id](https://twitter.com/mahie_id)

## Acknowledgments

- My deepest appreciation goes to Mr. Dave Gray whose tutorial videos has helped build my foundation in web development.
- I am also grateful to GMT Software whose coding bootcamp has given me environment and community of like-minded individuals to grow.
