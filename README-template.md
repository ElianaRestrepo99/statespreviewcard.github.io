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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

-company template de analyst.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/desktop.png.)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

-a complex process since I had difficulty making the mobile component, otherwise it was very pleasant to give color and luminosity to the image.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | Stats preview card component</title>

  <link rel="stylesheet" href="./style.css">
</head>
<body>

  <div class="container">
    <div class="wrapper">
      <div class="text-component">
        <h1 class="title">
          Get <span>insights</span>  that help your business grow.</h1>
        <p class="subtitle">  Discover the benefits of data analytics and make better decisions regarding revenue, customer 
          experience, and overall efficiency.</p>

          <div class="stat-box">
            <div>
              <p class="num"> 10k+</p>
              <p> companies</p>
            </div>

            <div>
            <p class="num"> 314+</p>
            <p> templates</p>
            </div>

            <div>
            <p class="num">12m+ </p>
            <p>queries</p>
            </div>
          </div>
      </div>

            <div class="img-component">
              <img src="./images/image-header-desktop.jpg" alt="">
          </div>


          </div>
          <div class="attribution">
            Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
            Coded by <a href="#">ElianaRestrepo99</a>.
          </div>
      </div>
    </div>


  </div>

 
</body>
</html>
```
```css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    font-family: 'Inter',sans-serif;
    min-height: 100vh;
    background: hsl(233, 47%, 7%);
    display: flex;
    align-items: center;
    font-size: 15px;
}

.container{
    max-width: 1020px;
    margin:  0 auto;
}

.wrapper{
    background-color: hsl(244, 38%, 16%);
    display: grid;
    grid-template-columns: 1fr 1fr;
    border-radius: 15px;
    overflow: hidden;
    margin: 2rem;
}

.img-component img{
    width: 100;
    height: 100;
    object-fit: cover;
}

.img-component{
    position: relative;
}

.img-component::after{
    position: absolute;
    content: '';
    height: 100%;
    width: 100%;
    left: 0;
    top: 0;
    background-color:hsl(277, 64%, 61%, 0.6);
}

.text-component{
    padding: 50px;
}

.title{
    color:  hsl(0, 0%, 100%);
    font-weight: 700;
    padding-bottom: 22px;
}

.title span{
    color:hsl(277, 64%, 61%);
}


.subtitle{
    color: hsla(0, 0%, 100%, 0.75);
    line-height: 1.8;
}

.stat-box{
    display: flex;
    justify-content: space-between;
    text-transform: uppercase;
    padding-top: 60px;
}

.stat-box p.num{
    color: hsl(0, 0%, 100%);
    font-size: 25px;
    font-weight: 700;
    margin-bottom: 7px;
}

.stat-box p{
    color: hsl(277, 64%, 61%, 0.6);
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
