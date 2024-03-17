# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![fourcard feaure](https://github.com/babybhavani/FourCardFeature/assets/152834101/7d44f97e-c06b-4b67-b0c4-e756a2171358)


### Links

- Solution URL: [https://babybhavani.github.io/FourCardFeature/]([https://babybhavani.github.io/FourCardFeature/](https://babybhavani.github.io/FourCardFeature/))
- Live Site URL: [https://babybhavani.github.io/FourCardFeature/](https://babybhavani.github.io/FourCardFeature/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- VS-code
  
### What I learned

- CSS Grid Templates✨
    - As a begiinner, I've learnt about the basic alignment of grid templates. In addition with I've grabbbed the knowledge in things like dense properties for rows and columns.
- Grid column templates
  - Used to divide the container into vertical parts
- Grid template rows
  - used to divide the bix into horizontal parts
- Grid items alignment🤞
    - As a designer it is neccessary to learnt about the alignments of the grid Items.
  - Learned about
      - grid-column
      - grid-row
      - grid-area
      - justify-content
      - align-items
      - justify-self
- Items sizing💎
  - It is important to make the grid layout appearance beautiful✨.
  - minmax()-used to set the carad or inner items to a minimum length and maximum length.
  - fitcontent() used to fit the content.


To see how you can add code snippets, see below:

```html

  <section class="container">
      <section class="headings-container">
        <h1 class="top-heading">Reliable, efficient delivery</h1>
        <h1 class="middle-bold-heading"> Powered by Technology </h1>
        <h3  class="bottom-heading"> Our Artificial Intelligence powered tools use millions of project data points
          to ensure that your project is successful
        </h3>
      </section>
        <section class="card card1">
          <h1 class="card-heading">Supervisor</h1>
          <p class="card-bio"> Monitors activity to identify project roadblocks </p>
          <img src="images\icon-supervisor.svg" alt="supervisior" class="card-img">
        </section>
        <section class="card card2">
          <h1 class="card-heading"> Team Builder
          </h1>
          <p class="card-bio"> Scans our talent network to create the optimal team for your project</p>
          <img src="images\icon-team-builder.svg" alt="Team Builder" class="card-img">
        </section>
        <section class="card card3">
          <h1 class="card-heading"> Karma
          </h1>
          <p class="card-bio">
            Regularly evaluates our talent to ensure quality
          </p>
          <img src="images\icon-karma.svg" alt="Karma" class="card-img">
        </section>
        <section class="card card4">
          <h1 class="card-heading"> Caluculator
          </h1>
          <p class="card-bio">
            Uses data from past projects to provide better delivery estimates
          </p>
          <img src="images\icon-calculator.svg" alt="Caluculator" class="card-img">
        </section>

    </section>
  
```
```css
.container {
    padding: 10px;
    background-color: hsl(0, 0%, 98%);
    display: grid;
    grid-template-rows: repeat(5, 1fr);
    gap: calc(1rem + 1vw);
    justify-content: center;
    align-items: center;
}

```

### Continued development
It can be developed with the corresponding html pages linked to it. I am willing to add that features to my project.

### Useful resources

- [CSS GRID](https://cssgrid.io/) - This helped me for alignment of grid items reason. I really liked this pattern and will use it going forward.
- [MDN reference](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout/Basic_concepts_of_grid_layout) - This is an amazing article which helped me finally understand Grids in CSS. I'd recommend it to anyone still learning this concept.

## Author
- Frontend Mentor - [@babybhavani](https://www.frontendmentor.io/profile/babybhavani)


## Acknowledgments

I'd like to convey my thanks to [CSS Grid](https://cssgrid.io) by wes bos. I like the way of teaching presentation. I am going forward to complete remaining courses.


### Happy Coding 💻✨.
