# HTML For Programmers - Linkedin Learning

Course by Emma Bostian &rarr; www.linkedin.com/learning/html-for-programmers

Repo &rarr; https://github.com/linkedinlearning/html-for-programmers-4360013

---

## Notes
## \<div\> VS \<span\>
They are generic containers that allow you to logically group content

```<div>``` is for block level grouping

```<span>``` is for inline level grouping

## Examples:
You can use ```<span>``` if you want to change a color for one element in a line.

### Let's change the Country to the color "blue"
```
  <img src="../assets/img.png" alt="nice image">
  <h3>  Persons Name  </h3>
  <p>  City, <span style="color:blue"> Country </span></p>
  <button>  Add Friend  </button>
```

If you have multiple cards like this you can group each one of them in a ```<div>``` to be easier to apply styles later.
### Let's create blocks
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
- A head section: ```<head>```
- A body section: ```<body>```
  
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

## Landmark Elements
```
  <body>

    <nav> Navigation Bar  </nav>
    <aside> Side Bar </aside>
    <main> Main part of the page </main>
    <footer> Bottom part of the page </footer>

  </body>
```
## Header

```
<h1> </h1>  to  <h6> </h6>
```

### Examples
---
<h1>H1</h1> 
<h2>H2</h2> 
<h3>H3</h3> 
<h4>H4</h4> 
<h5>H5</h5> 
<h6>H6</h6>

---

## Paragraph
``` 
<p> This is a paragraph </p>
```

## Forms
```
<form> </form>
```

Sections to submit informations. Forms commonly used with 2 atributes: **action** and **method**
- Action: URL that will process the form submission.
- Method: the "http" method the form will be submitted with.

## Media Elements
```
<img />

<audio> </audio

<video> </video>
```

## Including CSS

### External Style Sheet
```
<head>
  <link rel="stylesheet" href="./styles.css">
</head>
```

### Embedded CSS
```
<head>
  <style>
    h1 {
      color: blue;
    }
  </style>
</head>
```

### Inline Styles
```
<h1 style="color: blue">Title</h1>
```

## Including JavaScript

### External Script
```
<body>
  <script type="text/javascript" src="./index.js"> </script>
</body>
```

### Embedded JavaScript
```
<body>
  <script>
    function alertUser(){
    ...
    }
  </script>
</body>
```

## Assets Used
- <a href="https://www.freepik.com/free-vector/find-person-job-opportunity_8063764.htm#query=avatar&position=1&from_view=keyword&track=sph">Image by studiogstock</a> on Freepik
