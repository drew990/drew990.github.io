# Code Refactor Starter Code

Module 1 challenge is to look at Horiseon code and refactor it to be optimize and fix a few mistakes that were made in the code.

### Live URL

https://drew990.github.io/

![Screen Shot](https://drive.google.com/file/d/1q9yvLtLBr-E-i7HxrJfotschDO8-7nR7/preview)

#

## Description

Horiseon is a website that offers optimization your website for search engines. For better ranking and bring attraction to businesses websites. Horiseon has a problem of their own though where their code needs to be refactored and optimize to bring it up to accessibility standards, a structure semantic HTML elements, a concise descriptive title, and many more. Below, we'll be talking about those changes.

# Changes to index.html and style.css

## Title

Title was originally "website" so it was rename into the company's name as well shows where the user where they are at on the website. So "Home | Horiseon" put in its place.

## Header

### index.html

The header part of the website was using a div to define it but since there already a `header` semantic, the div was replace with `<header>`. The class `header` was also remove and was restyle in the style.css section.

### style.css

Instead of needing a class, I change header into a default so that anytime `header` is put in the code, it'll automatically recogonize how to style it.

## Content

### index.html

All images were missing an alt attribution so to make sure they still met accessibility standards, they had alts put in place where it should have been.

Each section was originally div as well and they were replace with `<section>`

search engine optimization didn't have a proper id to it so the link in the nav bar wasn't working properly. So I fixed it by putting in the ID.

## Benefits

### index.html

Since benefits can be define as a aside section, the div that was originally in its place then replace with `<aside>`. Images also have the same problem where they are missing alt attribution so now they have alts where they should have been.

## Footer

### index.html

Last but not least, just like the same problems with `header`, and `aside`, theirs already a `footer` semantic so the div was replace with `<footer>`

# Authors

Andrew Banagas
