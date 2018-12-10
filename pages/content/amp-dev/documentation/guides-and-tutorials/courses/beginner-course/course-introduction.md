---
$title: Course Introduction
$order: 1
toc: true
---
[TOC]

## Who is this course for?

This course is designed for current developers who are struggling to build performant websites and for aspiring developers who are looking to build their first website. Additionally, this course is well-suited for anyone who is maintaining or working on an existing AMP site.

Throughout this and the following courses you will:

* Be introduced to the ways AMP pages differ from traditional “vanilla” websites
* Incrementally build a sample project using real AMP components and best practices
* Learn strategies for building modern websites (such as component-based development and reactive programming)

## Course Prerequisites

To get the most from these courses, you should have a basic understanding of HTML and CSS. It is enough to be able to recognize HTML and CSS and to be able to make minor additions and alterations to existing HTML and CSS as instructed to in the lessons. As you might already know, [HyperText Markup Language](https://html.spec.whatwg.org/multipage/) (HTML) is a document description language that lets us create content for the web. Teaching HTML is beyond the scope of this course. There are many great resources on the web if want to learn more about HTML, though. You could try taking a look at [this tutorial](https://learn.freecodecamp.org/responsive-web-design/basic-html-and-html5/) by freeCodeCamp, or you can try [this free course](https://www.udacity.com/course/intro-to-html-and-css--ud001) on Udacity!

## Follow the Code With Glitch

To complete the code examples included in these courses, we will be using [Glitch](https://glitch.com/). Glitch is an online code editor that lets you create and view web sites and server APIs without needing to install anything on your computer.

The Glitch code editor environment looks like this:

{{ image('/static/img/courses/beginner/image3.png', 1024, 768, caption='Glitch environment') }}

The **red** box above indicates the online editor where you will be actually typing all your HTML and CSS. The **green** box indicates the button that will take you to the live version of the page you are creating. The **yellow** box is a button that lets you create a copy of this project and edit it. The blue box indicates all the files that you have available. In the assets folder, you can find all of your images.

Let's start with a basic HTML page now. We have created an empty project on Glitch, containing a few images and some server code that you’ll need later, and an index file with a title and a single image.

Open [this](https://glitch.com/edit/#!/nosy-leech) project. Click the “Remix This” button on the top right. This will create a new project that you can now edit! This new project will be your own personal copy, and if you log into Glitch, it will be on your profile for you to edit however you want! You can continue to use this same editor for this and future trainings. Don’t worry though, each future training will also give you the opportunity to start with a reference version of the solution to that point.

It’s not necessary to use Glitch to complete these trainings, but some of the code required to complete the exercises is not discussed in these trainings but is contained in the Glitch samples. If you’d like to use another editor, you may still need to go into the Glitch samples to copy the CSS and server code into your local solution.

## Setting Up The AMP Validator

The AMP validator is a tool for detecting errors in our AMP pages. Writing valid AMP pages is an important part of getting the full performance benefits from using AMP. The validator can be accessed in two ways: via a Chrome extension, or by adding a hash parameter to our URL, so that our AMP page uses the built-in validator. For the purposes of this course, we suggest you use the Chrome extension, because it’s easier to use and more easily accessible while you build out your site.

* To install the Chrome extension, visit [this link](https://chrome.google.com/webstore/detail/amp-validator/nmoffdblmcmgeicmolmhobpoocbbmknc/related?hl=en).
* To enable the built-in AMP validator add `#development=1` at the end of your AMP page URL and open the developer console in your browser to see the results.

[tip type="note"]
Note: In this course we are using Glitch. To see the validator working you have to open your page in a new window to see it live. To do that, click the “Show Live” button on the top left. When the page is open, you’ll see the icon for the AMP validator light up, indicating that it thinks your page is trying to be an AMP page.

If you’re using the Chrome extension, look at the top right of your browser, just right of the address bar. You should see the AMP sign there. Click it!

If you want to use the built-in validator, add the hash to your URL like this:

For example, your URL 

`https://YOUR_PROJECT.glitch.me/` will become 

`https://YOUR_PROJECT.glitch.me/#development=1`
[/tip]

## What we'll build

Throughout this and the following two courses, you will build a website for Chico’s Cheese Bicycles Shop. Chico has developed a revolutionary bicycle made entirely out of cheese! Demand for the new bicycles is so high that Chico needs to get a website up as quickly as possible to handle orders and market their new products! When we’re finished with these courses, Chico’s site will look very much like this:

{{ image('/static/img/courses/beginner/image12.png', 311, 550, caption='Completed AMP page for this tutorial') }}

You can click on [this link](https://nice-consonant.glitch.me/) to see a live preview. Play around with the site. We have videos, embedded tweets, a login form, an image carousel, and ways to share our site on social media! Open the navigation menu by clicking on the icon made of three lines in the upper-left corner (also called a ‘hamburger menu icon’). Once the menu expands, click on the link to view the list of products. Notice how the list of products can be both sorted by price and filtered by category. Click on any of the products. Notice how more details about that product pop up on the screen?

This site is a collection of features we see on many sites online today. This site was built entirely using AMP, and over the course of these lessons, you’re going to build this site yourself as well.

<div class="prev-next-buttons">
<a class="button" href="{{g.doc('/content/amp-dev/documentation/guides-and-tutorials/courses/beginner-course/our-first-amp-page.md', locale=doc.locale).url.path}}"><span class="arrow-next">Let’s dive in!</span></a>
</div>