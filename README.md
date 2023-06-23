# HTML For Programmers - Linkedin Learning

Course by Emma Bostian &rarr; www.linkedin.com/learning/html-for-programmers

Repo &rarr; https://github.com/linkedinlearning/html-for-programmers-4360013

---

# Notes
## \<div\> vs \<span\>
Div and span are generic containers that allow you to logically group content

### \<div\> is for block level grouping
### \<span\> is for inline level grouping

## Examples:
You can use \<span\> if you want to change a color for one element in a line.

### Let's change the Country to the color "blue" like this:
```
  <img src="../assets/img.png" alt="nice image">
  <h3>  Persons Name  </h3>
  <p>  City, <span style="color:blue"> Country </span></p>
  <button>  Add Friend  </button>
```

### If you have multiple cards like this you can group each one of them in a \<div\> to be easier to apply styles later
```
<!-- Person 1 -->

  <div>
    <img src="../assets/img.png" alt="nice image">
    <h3>  Persons Name </h3>
    <p>  City, <span style="color:blue"> Country </span></p>
    <button>  Add Friend  </button>
  </div>

<!-- Person 2 -->

  <div>
    <img src="../assets/img.png" alt="nice image">
    <h3>  Persons Name </h3>
    <p>  City, <span style="color:blue"> Country </span></p>
    <button>  Add Friend  </button>
  </div>

<!-- Person 3 -->

  <div>
    <img src="../assets/img.png" alt="nice image">
    <h3>  Persons Name </h3>
    <p>  City, <span style="color:blue"> Country </span></p>
    <button>  Add Friend  </button>
  </div>
```

## Basic HTML
Consists of 3 parts
- Information about the HTML version
- A head section: \<head\>
- A body section: \<body\>
  
```
<!DOCTYPE html>
<html lang="en">

  <head>
    Metadata that is not displayed in the browser
  </head>

  <body> 
    Document`s content that is visible in the page
  </body>

</html>
```
