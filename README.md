# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨


**Answer**
--index.css

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>English Premier League</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <h1 id="main-heading">English Premier League 2025</h1>

  <p class="intro-text">Welcome to the official fan page of the EPL — the most exciting football league in the world!</p>

  <img src="epl-logo.jpg" alt="EPL Logo" class="styled-image" />

  <div class="content-box">
    <p>Follow your favorite teams like Manchester City, Liverpool, Arsenal, and Chelsea as they compete for glory this season. Get match highlights, player stats, and latest updates all in one place.</p>
  </div>

</body>
</html>



--style.css

/* ID Selector - Page Title */
#main-heading {
  color: #37003c; /* Premier League Purple */
  font-family: 'Georgia', serif;
  text-align: center;
  margin-top: 20px;
}

/* Class Selector - Intro Text */
.intro-text {
  font-size: 18px;
  color: #222;
  font-family: 'Arial', sans-serif;
  padding: 10px;
  margin: 10px;
  text-align: center;
}

/* Tag Selector - Body Styling */
body {
  background-color: #f3f3f3;
  margin: 0;
  padding: 0;
  font-family: 'Verdana', sans-serif;
}

/* Image Styling */
.styled-image {
  display: block;
  margin: 20px auto;
  width: 200px;
  border: 4px solid #37003c;
  border-radius: 12px;
  background-color: #fff;
}

/* Content Box Styling */
.content-box {
  border: 2px solid #0057b8; /* EPL blue */
  padding: 15px;
  margin: 20px;
  background-color: #e8f0fe;
  border-radius: 8px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
}

