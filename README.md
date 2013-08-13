Photoshop for Web Design
======================

Materials for Photoshop for Web Design, developed by [Zoe Rooney](http://zoerooney.com) for Girl Develop It - Philadelphia. Template forked from [Intro to Web Concepts](https://github.com/girldevelopit/gdi-intro-web-concepts).

The course is meant to be taught in a single 2.5 hour workshop. 

## Suggested course description is below:

Photoshop is one of the most popular tools out there for web design. In this course, you'll learn how designers and front-end developers use Photoshop as part of their workflow. If you've ever wondered if you're making the most use of Photoshop when you're designing, or if you're creating files that are optimal for making the transition to development, this course is for you.

In this workshop, we'll cover:

* Setting up and saving your Photoshop workspace for web work (including units, tools & shortcuts)
* Tips and tricks for setting up your files for pixel-perfection
* Organizing your files and working with layers
* Working with graphics in a way that optimizes "code-ability"
* Slicing and saving for the web

You'll walk away a Photoshop-for-web-design power-user, with lots of tricks, efficiencies, and shortcuts at your fingertips for your next site project.

This course is open to all proficiency levels - we may reference some basic HTML and CSS concepts but we won't be writing any code. No prior experience with Photoshop is necessary, although this class will still benefit users who are experienced working with Photoshop but not as familiar with using it to design for the web.

*Required Software:* Photoshop

With a free Creative Cloud membership, you can download a 30-day trial version of Photoshop - https://creative.adobe.com/plans - just make sure you've downloaded (and preferably opened) Photoshop prior to the class so you're certain it's fully installed and working on your computer!

## Theme customization

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});