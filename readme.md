# BDL - Webpage - 01: Website programming basics
**Yesterday**
- Collaborating with GitHub
- Review branching and merging
- Pull requests and Code review
- Conflicts
   - you are in main local 
   - checkout to tom branch 
   - add / commit /push
   - make a pull request 
       - if merged
       - then 
       - git checkout main
       - git pull origin main
       - git checkout tom
       - if you want to update tom with the last update from local main
           - git merge main

**TODAY**
- Websites
- Basic HTML & CSS
- Making a simple form
  


- every website is based on three fundamental 
  - HTML: structure
  - css : style 
  - JavaScript: advanced & dynamic functionality
  



# html
  - Everything start from html
  - <html> tag
    - <head></head> 
      - contains invisible elements that describe the document
        - title of the page
        - style element
    - <body></body>  
      - contains visible elements , they are nested 
  - closing </html> 


```html
<html>
  <head><title>My Title</title>
  
  <style>
/* `the style rules go here` */

  </style>
  
  </head>

  <body>
    <h1>This is the heading 1 element</h1>

    <p>Paragraph element ()</p> 

    <img src='url goes here' alt="some text" >  <!-- src and , action , method , style .... are attribute -->



</body>
</html>
```


## CSS

- Completely different from HTML 😊
- Made up of "rules"
  

``` css

/* selector {

  property : value
} */

p {

color :  orange

}

#someID {

background-color : black

}

.someClass {

font-size: 2rem 

}

a:hover{
  background-color : yellow
}

```

- css has many different selectors
- css has many different properties 
- css has many different kind of values 
