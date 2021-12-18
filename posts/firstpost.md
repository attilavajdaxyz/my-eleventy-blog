---
title: This is Cat-Photo-App
description: This is a post on the Cat-Photo-App I learned to make at freeCodeCamp.
date: 2021-12-18
tags:
  - another tag
layout: layouts/post.njk
---
This is a Cat-Photo-App I learned to make at freeCodeCamp [Cat-Photo-App](https://www.freecodecamp.org/learn/responsive-web-design/basic-css/use-an-id-attribute-to-style-an-element)

## Section Header

It would be cool to add related atomic UX knowledge to this page. Perhaps about prototyping, ideation, research. Moving beyond the cliche, making variations, writing denotations and connotations. I don't know how to embed the actual app, perhaps with njk.

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css" />

<style>
  h2 {
    font-family: Lobster, monospace;
  }
  p {
    font-size: 16px;
    font-family: monospace;
  }
  .red-text {
    color: red
  }
  .smaller-image {
    width: 100px;
  }
  .thick-green-border {
    border: 10px solid green;
    border-radius: 50%;
  }
  .silver-background {
    background-color: silver;
  }
  #cat-photo-form {
    background-color: green;
  }
  
 
</style>

<h2 class="red-text">CatPhotosApp</h2>
<p class="red-text">Click here to view more <a href="#">cat photos</a>.</p>
<img class="thick-green-border smaller-image" src="https://s3.amazonaws.com/freecodecamp/relaxing-cat.jpg" alt="Cute orange cat lying on its back" />
<div class="silver-background">
<p>Three things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Three things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
</div>
<form id="cat-photo-form" action="https://www.freecodecamp.com/cat-photo-app/form-submit">
  <label for="indoor">
    <input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</input></label>
  <label for="outdoor">
    <input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</input></label>
  <br />
  <label for="lazy">
    <input id="lazy" type="checkbox" name="personality" value="lazy" checked> Lazy</input></label>
  <label for="loving">
    <input id="loving" type="checkbox" name="personality" value="loving"> Loving</input></label>       
  <label for="energetic">
    <input id="energetic" type="checkbox" name="personality" value="energetic"> Energetic</input></label>
  <br />
  <input type="text" placeholder="cat photo URL" />
  <button type="submit" required>Submit</button>
</form>
```
