# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./Desktop.png)
![](./mobile.png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://github.com/Bally14/product-previw-card-solution.git)

## My process

#### The HTML Part

First I tried to dissect the different sections of the Layout.
To me, it seemed like having a container, then a card where 2 divs resides inside (foto and description) would be the way to go.

```html
<div class="container">
  <div class="card">
    <div class="foto">
      <img src="../images/image-product-desktop.jpg" alt="" />
    </div>
    <div class="foto-mobile">
      <img src="../images/image-product-mobile.jpg" alt="" />
    </div>
    <div class="description">...</div>
  </div>
</div>
```

#### The CSS Part

I honestly "googled" myself into an accurate CSS styling. Through try-and-error and 4 hours of reading whatever ressources I could find to get the Job done, I think I kind of nailed it.
The CSS part was very messy, so thats why i can't really explain what is going on and what kind of thought process I had while doing it so I would be more than thankful if someone reviewed it and gave me constructive feedback!

### Built with

- Html
- CSS

### What I learned

After a Basic understanding of HTML and CSS, I was able to use media query to make the layout responsive in a way that it would change depending on the view port width

```css
@media screen and (max-width: 600px) {
}
```

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Bally14)
