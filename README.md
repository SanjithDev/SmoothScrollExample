# Smooth Scroll Example
Create a React project if you haven't already, or use an existing project.

## Step 1 : Install the Smooth Scroll Package
`npm install smooth-scroll`

## Step 2 : Import the Smooth Scroll Package
`import SmoothScroll from 'smooth-scroll';`

## Step 3 : Initialize the Smooth Scroll in your Component
Insert this code within your parent function before the return statement.

```jsx
const scroll = new SmoothScroll('a[href*="#"]', {
    speed: 800,
    speedAsDuration: true,
  });
```
## Step 4 : Call the section using its href attribute.

```html
<section id="home">...</section>
<section id="about">...</section>
<section id="footer">...</section>

<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#footer">Footer</a>

```

### Note : Using `name=""` to call the section will not work with this package.
