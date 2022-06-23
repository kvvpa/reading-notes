
# Structure Web Pages with HTML

##### 6/23/22 - Code 102 - Day Four

## Wireframes

When I created the website for [CapCity Presents](https://capcitypresents.com), I used a software called Balsamiq 3 to create a [wireframe](https://github.com/kvvpa/capcitypresents/blob/master/design/IA.pdf), so I have a very basic level of experience with it already. Among the topics covered today, we're reading about Wireframes; their purpose and best practices.

* Wireframes are a low-fidelity sketch of a digital interface used by user experience designers to plan a website.
* The purpose of a wireframe is to help plan how everything is laid out on the screen before worrying about code or other styling choices.
* Wireframes can be designed with paper and pen, or with specialized software, or many times both. Paper and pen (or marker and whiteboard) are very easy to quickly revise during the early stages of a design.
* Wireframes provide something for end users to test prior to the heavy work of implementation.
* Sometimes the wireframing process is quick and straight forward, while other projects may require multiple stages: sketch, wireframe, hi-definition wireframe, visual, code, etc.
* Some wireframe tools mentioned are UXPin, InVision, Wireframe.cc, and Balsamiq.
* It's important to do research and understand the needs of the project prior to beginning work on a wireframe.
* It's important to understand the flow of which pages lead to where and how so the user has the best possible experience interacting with the page.
* Be willing to collaborate and play around with the designs to best meet the needs of the project.
* After feedback from the first prototype, you can start developing higher fidelity and more detailed prototypes.
* Three key principles to a good wireframe:
  * Clarity - Answers the questions of what the page is about and what can be done with it
  * Confidence - Easy navigation and clear calls-to-action instills confidence in the user
  * Simplicity - Not too much information so as to be distracting to the purpose of the project

## Basic HTML

* `<p> </p>` - paragraph tags
* `<strong>` - provides emphasis
* `<img src='[image path]' alt='[image description]'>` - embeds image with description
* `<h1> </h1>` - headings numbered by priority, up to `<h6> </h6>`
* `<ul> </ul>` - unordered list
* `<ol> </ol>` - ordered list
* `<li>` - list items
* `<a href='[URL]'>[link text]</a>` - anchor tag with a hyperlink attribute

### Anatomy of HTML Document
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>[page title]</title>
  </head>
  <body>
    <img src="[image path]" alt="[image description]">
  </body>
</html>
```

## Semantics

Semantics is about the meaning of code, what role parts have, and making logical sense of a page's structure. It is also important for accessibility, as these things need to be defined for assistive devices such as screen readers.

In HTML, an `<h1>` element is semantic because it identifies the highest priority heading on the page. This continues on with `<h2> <h3> <h4>` etc. Semantics is especially important in HTML because it is designated to the structure of a documents as opposed to CSS which deals with the styling and appearance.

[Table of Contents](https://kvvpa.github.io/reading-notes/)