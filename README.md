# Kevin Maroun — Personal Portfolio

INFR3120 Assignment 1

My portfolio introdcues me and shows examples of courcework that i have done at ontario tech
I am studying Technology Management at Ontario Tech University.

Live website: https://kevinmaroun07.github.io/kevin-portfolio/
Public repository: https://github.com/Kevinmaroun07/kevin-portfolio

## Pages and files

- index.html: This is my Home page wich has a short introduction and you can navagaite throughout the website.
- about.html: About Me page has a picture of me and also includes a introduction video.
- projects.html:Shows 4 projects that i have completed witg a title and a short description  
- contact.html: This is a form that allows you to input email and name
- styles.css: shows colours, gradients and element styling.
- full.css: layout for desktop.
- tablet.css: layout for tablet.
- smartphone.css: layout for phone 
- images/Pic.png.png: Childhood picture of me and is also used as video poster.
- videoportfolio.MP4: My introduction video.

The pages use HTML5 elements this includes the header, nav, article and footer.
Each page has navigation links to get to other pages.

## Question 2(a) responsive design

Each HTML page has a viewport tag so  the layout will adapt to the screen width. 
| Screen width | Stylesheet | Layout and reason |
| --- | --- | --- |
| 480px and below | smartphone.css | Full-width body and vertically stacked. This gives the links and content enough space on small screens. |
| 481px–959px | tablet.css | Body uses 95% of the available width. The Four navigation items share one row and the content is showen underneath. |
| 960px and above | full.css | Body uses 85% of the available width. Navigation floats on the left|

I followed the lecture examples by having Percentage
widths to allow the layout adjust within each range. Images and videos use
max-width: 100% and height at auto so they can fit smaller screens.

The layout uses floats and percentage widths. NOT flexbox.

Phone and tablet layouts = widths of 375px and 768px.

## Gradients — Question 2(b)

Both gradients are showen in styles.css and pops up on all four pages.

- Header: linear-gradient(#028090, #013a40). This changes vertically
  from teal at the top to dark teal at the bottom.
- Footer: linear-gradient(-45deg, #013a40, #028090). The -45deg value
  gives the gradient an angled direction.

## Colour scheme — Question 2(c)

I used a  teal palette. used adobe to do so and saved them together as a palette.

- #028090: Teal used in the gradients and navigation  state.
- #013a40: Dark teal used for navigation, headings and the submit button.
- #f4f9f9: Pale background around the website
- #ffffff: White article backgrounds and light text on dark areas.
- #222222: Dark  text.
- #cccccc: Light borders around articles.

I used teal colors to keep the pages consistent.The  White
areas separate the text from the coloured header and navigation.

Adobe colour tool: https://color.adobe.com/create/color-wheel

## Contact form

The form uses , an email input and a phone # input.
The phone pattern [0-9]{10} needs exactly ten digits, and
maxlength="10"
The form uses mailto with method="post" and enctype="text/plain",

Contact email: kevin.maroun@ontariotechu.net

## Testing

- All four HTML pages were checked using the W3C HTML validator.
- styles.css, full.css, tablet.css and smartphone.css passed CSS
  validation with no errors.
- Links on all four pages were checked using the W3C Link Checker.
- WAVE checks on all four pages showed zero errors, zero contrast
  errors and zero alerts before the introduction video was added.
- Spelling and grammar were reviewed with ChatGPT.
- The introduction video was tested in Chrome and on the
  deployed About page.
- Phone and tablet layouts were also checked in Chrome.


## Running and deployment

To view the project locally you can open index.html in a  browser.
Video playback was tested in Chrome.

The project was uploaded using Git commands, like git add,
git commit and git push.
The public repository is available through GitHub Pages.

## Sources and assistance

- INFR3120 Week1 slides and examples:
  HTML/CSS basics and gradients.
- INFR3120  Week3 Code.zip:
  semantic.html, form.html, video.html, responsive.html, fluid.css,
  full.css, tablet.css and smartphone.css.
-  style.css:
  styling reference.
-  Tutorial1A - Installing Git
- W3Schools HTML and CSS tutorials
  https://www.w3schools.com/html/
  https://www.w3schools.com/css/default.asp
- MDN Web Docs contributors, linear-gradient reference:
  https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/gradient/linear-gradient
  https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- Adobe: colour palette tool listed.
- ChatGPT: assistance with debugging and the introduction
  video script.

The photograph is of me as a child. But i used ai to enhance the quality of the original picture 