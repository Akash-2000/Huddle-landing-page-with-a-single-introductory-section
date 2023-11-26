# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Violet: hsl(257, 40%, 49%)
- Soft Magenta: hsl(300, 69%, 71%)

## Typography

### Headings

- Family: [Poppins](https://fonts.google.com/specimen/Poppins)
- Weights: 400, 600

### Body

- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Weights: 400

## Icons

For the social icons, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com/)
- [IcoMoon](https://icomoon.io/)
- [Ionicons](https://ionicons.com/)




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;400;600;700&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap" rel="stylesheet">


  <title>Frontend Mentor | Huddle landing page with single introductory section</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
    .bodyStyle {
       background-image: url( './images/bg-desktop.svg' );
       background-color: hsl(257, 40%, 49%);
       margin: 0;
       padding:0;
    }
    .topStyle {
      background-image: url('./images/logo.svg');
      height: 150px;
      background-repeat: no-repeat;
      margin-top: 50px;
      margin-left: 20px;
    }
    .mainContent{
      flex: 2;
    }

    .firstmainContent{
      background-image: url('./images/illustration-mockups.svg');
      height: 100%;
      background-repeat: no-repeat;
    }
  </style>
</head>
<body class="bodyStyle">

  <div class="topStyle">
  </div>
  <div class="mainContent">
    <div class="firstmainContent"></div>
    <div class="secondmainContent"></div>
  </div>

  Build The Community Your Fans Will Love

  Huddle re-imagines the way we build communities. You have a voice, but so does your audience. 
  Create connections with your users as you engage in genuine discussion. 

  Register

  <footer>
    <p class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Your Name Here</a>.
    </p>
  </footer>
</body>
</html> 


