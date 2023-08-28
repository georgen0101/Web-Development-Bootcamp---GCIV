# My notes from the section

## CSS Display

### Challenge 1

```html
<!DOCTYPE html>
<html>
  <!-- 
  TODO
1. By changing only the display property of the CSS make all 3 squares line up horizontally like in goal1 image.
-->

  <head>
    <title>CSS Display Property Example</title>
    <style>
      p {
        color: white;
      }

      .red {
        display: inline-block;
        width: 200px;
        height: 200px;
        background-color: red;
      }

      .green {
        display: inline-block;
        width: 200px;
        height: 200px;
        background-color: green;
      }

      .blue {
        display: inline-block;
        width: 200px;
        height: 200px;
        background-color: blue;
      }
    </style>
  </head>

  <body>
    <h1>CSS Display Property</h1>
    <p class="red">Red Paragraph</p>
    <p class="green">Green Paragraph</p>
    <p class="blue">Blue Paragraph</p>
  </body>
</html>
```

![Alt text](./assets/images/c1.png)

### Challenge 2

```html
<!DOCTYPE html>
<html>
  <!-- 
  TODO
2. Change only the display property to make all 3 squares line up vertically like in goal2 image. 
-->

  <head>
    <title>CSS Display Property Example</title>
    <style>
      p {
        color: white;
      }

      .red {
        display: block;
        width: 200px;
        height: 200px;
        background-color: red;
      }

      .green {
        display: block;
        width: 200px;
        height: 200px;
        background-color: green;
      }

      .blue {
        display: block;
        width: 200px;
        height: 200px;
        background-color: blue;
      }
    </style>
  </head>

  <body>
    <h1>CSS Display Property</h1>
    <p class="red">Red Paragraph</p>
    <p class="green">Green Paragraph</p>
    <p class="blue">Blue Paragraph</p>
  </body>
</html>
```

![Alt text](./assets/images/c2.png)

## CSS Float

### Example

```html
<!DOCTYPE html>
<html lang="en">
  <!-- TODO
1. Make both paragraph elements wrap around the image.
2. Use Float to move the cat div to the left and the dog div to the right.
3. Use clear to make the footer go below both the cat and dog div. -->

  <head>
    <meta charset="UTF-8" />
    <title>CSS Float</title>
    <style>
      div {
        display: inline-block;
        width: 40%;
      }

      p {
        font-size: 2em;
      }

      img {
        float: left;
      }

      .cat {
        background-color: aquamarine;
        float: left;
      }

      .dog {
        background-color: coral;
        float: right;
      }

      footer {
        text-align: center;
        background-color: blueviolet;
        clear: both;
      }
    </style>
  </head>

  <body>
    <div class="cat">
      <h2>CatCSS</h2>

      <img src="cat.jpeg" alt="cat in a box" />
      <p class="first-paragraph">
        Nap all day cat dog hate mouse eat string barf pillow no baths hate
        everything but kitty poochy. Sleep on keyboard toy mouse squeak roll
        over. Mesmerizing birds. Poop on grasses licks paws destroy couch
        intently sniff hand. The dog smells bad gnaw.
      </p>
    </div>
    <div class="dog">
      <h2>DogCSS</h2>
      <img src="dog.jpeg" alt="dogs in a box" />
      <p class="second-paragraph">
        Heckin good boys and girls long woofer big ol wow very biscit long
        woofer heck what a nice floof, long doggo noodle horse vvv very taste
        wow. Very taste wow many pats aqua doggo he made many woofs pupperino,
        puggo doing me a frighten.
      </p>
    </div>

    <footer>Copyright. This is the footer</footer>
  </body>
</html>
```

![Alt text](<CleanShot 2023-08-28 at 13.23.08.png>)

## Responsive Websites

> Making websites look good on all screen sizes.

### Responsiveness

See how the different methods work.

- Media Queries
- CSS Grid
- CSS Flexbox
- Bootstrap Framework

## Media Queries

```html
<!DOCTYPE html>
<html lang="en">
  <!-- 
TODO: Change the background color for each device
[lightsalmon] Mobile Devices: 319px — 480px
[powderblue] iPads and Tablets: 481px — 1200px
[limegreen] Laptops: 1201px — 1600px
[seagreen] Desktops: 1601px and more
-->

  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, minimum-scale=1"
    />
    <title>Media Query</title>
    <style>
      body {
        background-color: aquamarine;
      }

      @media (min-width: 319px) and (max-width: 480px) {
        body {
          background-color: lightsalmon;
        }
      }

      @media (min-width: 481px) and (max-width: 1200px) {
        body {
          background-color: powderblue;
        }
      }

      @media (min-width: 1201px) and (max-width: 1600px) {
        body {
          background-color: limegreen;
        }
      }

      @media (min-width: 1601px) {
        body {
          background-color: seagreen;
        }
      }
    </style>
  </head>

  <body></body>
</html>
```

![Alt text](<CleanShot 2023-08-28 at 14.53.40.gif>)

## Web Design Agency Website

> Focused in practicing what we learn in this section.

Use flex?
floats
display
