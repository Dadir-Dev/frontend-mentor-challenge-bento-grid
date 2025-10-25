# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help me improve my coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Bento grid solution](#frontend-mentor---bento-grid-solution)
  - [Table of contents](#table-of-contents)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [🔧 Built With](#-built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

1. **Desktop Design**
   - Grid layout(irregular grid layout) with 8 grid-items arranged in 4 columns and 3 rows
   - The 1st and it's lower grid-item(bottom-left) will be in one grid container
   - The other 6 grid-items will be in another grid container
   - Different font-sizes and background-color
2. **Mobile Design**
   - Stacked single-column layout
   - Same content but rearranged in different order

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./design/bento-grid-mobile-design.png)
![](./design/Desktop-design.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Dadir-Dev/frontend-mentor-challenge-bento-grid)
- Live Site URL: [Add live site URL here](https://unrivaled-pie-acf5af.netlify.app/)

## My process

### 🔧 Built With

- Semantic **HTML5**
- **CSS Grid**
- **Responsive design**
- **VS Code** and **Live Server**
- **Git + GitHub**

### What I learned

- Mastered **complex grid template areas** for intricate layouts
- Implemented **responsive grid structures** without compromising design integrity
- Learned to manage grid areas across multiple breakpoints
- Used **grid-auto-rows and grid-auto-columns** for consistent sizing
- Used **strategic breakpoints** (1024px, 768px, 540px) for optimal user experience
- Created a **professional footer** with CSS Grid and Flexbox

Here’s a small snippet I’m proud of 👇

```css
.bento-grid {
  max-width: 1400px;
  margin: 1rem;
  display: grid;
  grid-auto-columns: 1fr;
  grid-auto-rows: 75px;
  gap: 2rem;
  grid-template-areas:
    "box1 box2 box2 box3"
    "box1 box2 box2 box3"
    "box1 box2 box2 box3"
    "box1 box2 box2 box3"
    "box1 box5 box6 box3"
    "box4 box5 box6 box3"
    "box4 box5 box6 box3"
    "box4 box7 box8 box8"
    "box4 box7 box8 box8"
    "box4 box7 box8 box8";
}
```

## Author

- Frontend Mentor - [Dadir-Dev](https://www.frontendmentor.io/profile/Dadir-Dev)
- GitHub - [Dadir-Dev](https://github.com/Dadir-Dev)
- LinkedIn - [Abdikadir Mohammed](https://www.linkedin.com/in/abdikadir-mohammed-54717318b/)
