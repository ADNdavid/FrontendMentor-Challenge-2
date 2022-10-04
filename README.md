# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/qr-code-component-using-css-grid-khjw2jlY1c)
- Live Site URL: [GitHub](https://adndavid.github.io/FrontendMentor-Challenge-2/)

## My process

### Built with

- CSS custom properties
- CSS Grid

### What I learned

- Use the properties **grid-template-areas** and **grid-area** to center a tag that contains the card.

```css
.container{
    display:grid;
    grid-template-areas:
        ". . ."
        ". card ."
        ". . .";
    }
.item {
    grid-area: card;
    }
```

- Use **Semantic Tags** in HTML structure.

## Author

- GitHub - [@ADNdavid](https://github.com/ADNdavid)
- Frontend Mentor - [@ADNdavid](https://www.frontendmentor.io/profile/ADNdavid)
- LinkedIn - [Anderson Sepúlveda](https://www.linkedin.com/in/adndavid/)

## Acknowledgments

Thank you to everyone who will provide feedback on Frontend Mentor.