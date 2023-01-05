# Quiz 2 - Expenses chart page solution

This is a solution to the [Expenses-chart page Quiz 2 challenge]

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


## Overview

### The challenge

Users should be able to:

- View the bar chart and hover over the individual bars to see the correct amounts for each day
- See the current day's bar highlighted in a different colour to the other bars
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page
- **Bonus**: See dynamically generated bars based on the data provided in the local JSON file

### Screenshot

![image](https://user-images.githubusercontent.com/114371881/210704758-6b9e48a4-63eb-4cbb-a947-20e75bc8301d.png)

### Links

- Solution URL: [https://github.com/ShaanGunwani/expenses-chart-page-main]
- Live Site URL: [https://shaangunwani.github.io/expenses-chart-page-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- React - JS Library
- Next.js -  React framework
- [Styled Components](https://styled-components.com/) - For styles



### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<section class="bottom">
        <h1>Spending - Last 7 days</h1>
        <canvas id="myChart"></canvas>
        <div class="divider"></div>
        <div class="totals">
          <div class="this_month">
            <p>Total this month</p>
            <h2>$478.33</h2>
          </div>
          <div class="last_month">
            <p>+2.4%</p>
            <p>from last month</p>
          </div>
```
```css
.last_month p:first-child {
  font-weight: 700;
  color: var(--Dark-brown);
}
.last_month p:last-child {
  color: var(--Medium-brown);
}
```
```js
  const titleTooltip = (e) => `$${e[0].formattedValue}`;
  const labelTooltip = (e) => "";
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development
I want to refine and continue more on the JQuery and the React JS library and I will try to focus on these topics in the future projects. 

### Useful resources

- [Example resource 1]([https://www.example.com](https://www.w3schools.com/js/js_intro.asp)) - This helped me gain extra knowledge regarding javascript. I really liked this website and I will always use this website and read through it to gain more knowledge regarding the topics I will learn later on in more classes to come.
- [Example resource 2]([https://www.example.com](https://www.w3schools.com/react/default.asp)) - This is an amazing website. It helped me learn a little bit of react and for me to immplement it on this quiz. 

## Your Detail 

- FullName - [Shaan Kishore Gunwani]
- StudentID - [2602176982]
- BINUS Email - [shaan.gunwani@binus.ac.id]


