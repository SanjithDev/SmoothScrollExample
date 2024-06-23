# Smooth Scroll Example
First Create a react project if you haven't did already or use existing project

## Step 1 : Install the Smooth Scroll Package
`npm install smooth-scroll`

## Step 2 : Import the Smooth Scroll Package
`import SmoothScroll from 'smooth-scroll';`

## Step 3 : Initialize the Smooth Scroll in your Component
```jsx
const scroll = new SmoothScroll('a[href*="#"]', {
    speed: 800,
    speedAsDuration: true,
  });
```
## Step 4 : Use the ID to href
```html
<section id="home">...</section>
<section id="about">...</section>
<section id="footer">...</section>

<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#footer">Footer</a>

```

### Note : only href="#" will work for this package. name="" won't work
