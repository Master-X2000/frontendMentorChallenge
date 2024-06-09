# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)


## Overview
An amazing challenge, almost never thought I will be able to complete it but I eventually did and it made me learn a lot of new things and i'm eger to get more challenges.
### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content


### Links

- Solution URL: [github.com/master-x2000/frontendMentorChallenge](https://your-solution-url.com)
- Live Site URL: [https://master-x2000.github.io/frontendMentorChallenge/](https://your-live-site-url.com)

## My process

  - I created my html code grouping the data in the most sutable maner for a good parent and child relationship,

  - linked my html code to my style sheet, imported my font into my style sheet and did some regular css resets.

  - Stated my variables and styled my body with a display of flex in my media quary, to ensure a responsive design layout.

  - Styled my report summary data with a display of flex also in my media quary, to make the result and summary info to have their respective left and right position.

  - Styled the result section also with a display of flex, creating the gradient background, also making use of a section of div to create my circle and applying a display of flex to the circle to place the text in the center of the circle.

  - Styled my summary section using a display of flex, also using a display of flex to style the individual result for the spacing. 

  - Making use of a data attribute to change the color of the background, stroke of the svg and text of the individual data from the results.

  -finally styled my button applying the color and the hover effect.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
          <div class="summary-item" data-item-type="accent-3">
            <div class="flex-group">
              
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M7.5 10h5M10 18.333A8.333 8.333 0 1 0 1.667 10c0 1.518.406 2.942 1.115 4.167l-.699 3.75 3.75-.699A8.295 8.295 0 0 0 10 18.333Z"/></svg>

              <h3 class="summary-item-title">
                Verbal
              </h3>
            </div>
              <p class="summary-score">
                
                <span>61</span> / 100
              </p>
            
          </div>
```
```css
@font-face {
    font-family: 'HankenGrotesk';
    font-display:swap;
    font-weight:100 900;
    src: url('assets/fonts/HankenGrotesk-VariableFont_wght.ttf')
    format('truetype');
}
```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Mastering my grid layouts and making use of the "data" attribute in HTML.

### Useful resources

- [Example resource 1](https://youtu.be/KqFAs5d3Yl8?si=LDuiA7Z8HvQzUw-e) - This helped me for my layouut. I really liked this pattern but I will use flex going forward.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Odezime Excel](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Thanks a lot "Kevin Powell". Your tutorial was a relly big help but althought, I still like flexbox after all, all you have to do is flex.
