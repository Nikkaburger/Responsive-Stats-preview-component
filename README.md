# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

This is a solution to the [Stats Preview component challenge on Frontend Mentor]

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshot.jpg)


### Links

- Solution URL: (https://github.com/Nikkaburger/Responsive-Stats-preview-component)
- Live Site URL: (https://unique-gelato-fb9a87.netlify.app)

## My process

Responsive design using mobile first  workflow, HTML and CSS

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learnt how to add color overlay to an image and adjust the opacity using section tags and styling the section in css.

```html
<body>
    <div class="main">
        <div class="container">
            <h1>
                Get <span class="keyword"> insights</span> that help your business grow.
            </h1>
            <p>
                Discover the benefits of data analytics and make better decisions regarding revenue, customer experience, and overall efficiency.
            </p>
            <div class="box">
            <div class="carousel">
                <h2>10k+</h2>
                <p class="feed">
                    Companies
                </p>
            </div>
            <div class="carousel">
                <h2>314</h2>
                <p class="feed">
                    Templates
                </p>
            </div>
            <div class="carousel">
                <h2>12M+</h2>
                <p class="feed">
                    Queries
                </p>
            </div>
            </div>
        </div>
        <section class="webimage"> 
            <figure>
            <!-- <img src="images/image-header-desktop.jpg" alt="image"> -->
            </figure>
        </section>
    </div>
</body>
```
```css
body {
    font-family: 'Lexend Deca', sans-serif;
    overflow-x: hidden;
    margin: 0px;
    width: 100%;
}

.main {
    width: 335px;
    height: 100%;
    margin: 50px 20px;
    border-radius: 10px;
    display: flex;
    flex-direction: column-reverse;
}


.container {
    background-color: hsl(244, 38%, 16%);
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    width: 275px;
    padding: 30px;
    align-items: center;
    justify-content: center;
    border-top-left-radius: 0px;
    border-top-right-radius: 0px;
}

.webimage {
    width: 100%;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    height: 250px;
    background-image: url("../images/image-header-mobile.jpg");
    background-size: cover;
    background-position: center;
    border-bottom-right-radius: 0px;
    border-bottom-left-radius: 0px;
}

.webimage figure {
    background-color: hsl(277, 81%, 29%);
    width: 100%;
    opacity: 0.7;
    height: 100%;
    border-bottom-left-radius: 0px;
    border-bottom-right-radius: 0px;
    border-top-right-radius: 10px;
    border-top-left-radius: 10px
}

.webimage figure img{
    width: 100%;
}

.box {
    display: flex;
    flex-direction: column;
    margin-top: 30px;
}

.carousel {
    padding-bottom: 20px;
}

.feed {
    color: hsla(0, 0%, 100%, 0.6);
    font-size: 12px;
    margin-top: 5px;
    text-transform: uppercase;
    font-family: 'Inter', sans-serif;
    padding-right: 0px;
}

h1 {
    color: hsl(0, 0%, 100%);
    font-size: 28px;
    font-weight: 700;
    text-align: center;
    font-family: 'Inter', sans-serif;
}

h2 {
    color: hsl(0, 0%, 100%);
    font-size: 20px;
    font-family: 'Inter', sans-serif;
    margin: 0px;
    text-align: center;
}

.keyword {
    font-size: 28px;
    font-family: 'Inter', sans-serif;
}

p {
    font-size: 16px;
    color: hsla(0, 0%, 100%, 0.75);
    margin-top: 30px;
    font-family: 'Inter', sans-serif;
    text-align: center;
}
    
}
```

### Continued development

My focus is on mastering modern web design techniques through continuous learning, experimentation, and a willingness to adapt to the ever-changing web landscape. 
By focusing on responsive design using, HTML5, CSS3, JavaScript, and PHP, to be adequately equipped to create visually stunning and user-friendly websites. Embrace new technologies, stay curious, and push the boundaries of my creativity to unlock endless possibilities in the world of web development. 


### Useful resources

- [#CSSMediaQuery](https://courses.webdevsimplified.com) - This helped me to understand and fix media query for the mobile version of my design, the tutorial was direct and explanatory. I really liked this pattern and will use it going forward.
- [#HTMLFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand the functionality of #HTML5 tags. I'd recommend it to anyone still learning this concept.
-[#CSSTutorialFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand CSS tags, syntax and their functionalities. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Oluwaseun Akeju](https://www.fluxverge.com)
- Frontend Mentor - [@nikkaburger](https://www.frontendmentor.io/profile/nikkaburger)
- Twitter - [@fluxverge](https://www.twitter.com/fluxverge)

## Acknowledgments

Special thanks to Almighty God for the completion of this task, my profound gratitude to Dave Gray, Omolade Sunday, Akinola Akeem and Webdevsimplified for their immense contributions.
