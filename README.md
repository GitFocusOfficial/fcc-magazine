# Learn CSS Grid by Building a Magazine

CSS Grid gives you control over the rows and columns of your webpage design.

In this course, you'll build a magazine article. You'll learn how to use CSS Grid, including concepts like grid rows and grid columns.

## Step 1

Begin with your standard HTML boilerplate. Add a `DOCTYPE` declaration, an html element specifying this page is in English, a `head` element, and a `body` element.

Add a `<meta>` tag with the appropriate `charset` and a `<meta>` tag for mobile responsiveness within the `head` element.

## Step 2

Add a `title` element with the text `Magazine`, a link element for the `https://fonts.googleapis.com/css?family=Anton%7CBaskervville%7CRaleway&display=swap` font stylesheet, a `link` for the `https://use.fontawesome.com/releases/v5.8.2/css/all.css` FontAwesome stylesheet, and a `link` for your `./styles.css` stylesheet.

Your font stylesheet will load three separate fonts: `Anton`, `Baskervville`, and `Raleway`.

## Step 3

Within your `body`, create a `main` element. Then in that element, create a `section` with a `class` set to `heading`.

## Step 4

Within your `.heading` element, create a `header` element with the `class` set to `hero`.

In that element, create an `img` element with the src set to `https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png`, the alt set to `freecodecamp logo`, and the `class` set to `hero-img`.

The `loading` attribute on an `img` element can be set to `lazy` to tell the browser not to fetch the image resource until it is needed (as in, when the user scrolls the image into view). As an additional benefit, lazy loaded elements will not load until the non-lazy elements are loaded - this means users with slow internet connections can view the content of your page without having to wait for the images to load.

Give your new `img` element a `loading` attribute set to `lazy`.

## Step 5

After your `img` element, add an `h1` element with the `class` set to `hero-title` and the text set to `OUR NEW CURRICULUM`, followed by a `p` element with the `class` set to `hero-subtitle` and the text set to `Our efforts to restructure our curriculum with a more project-based focus`.

## Step 6

Your image currently takes up a lot of space. To better see what you are working on, add a `width` attribute to the `img` element, with a value of `400`.

You will remove this later on when you have worked on the CSS.

## Step 7

After your `header` element, create a `div` with the `class` set to `author`.

Within that `div`, create a `p` element with the `class` set to `author-name` and give it the text `By freeCodeCamp`. Wrap the `freeCodeCamp` portion in an `a` element with the `href` set to `https://freecodecamp.org`, and the `target` set to `_blank`.

Below that, add a second `p` element with the class `publish-date` and the text `March 7, 2019`.

## Step 8

The `Referer` HTTP header contains information about the address or URL of a page that a user might be visiting from. This information can be used in analytics to track how many users from your page visit freecodecamp.org, for example. Setting the `rel` attribute to `noreferrer` omits this information from the HTTP request. Give your `a` element a `rel` attribute set to `noreferrer`.

## Step 9

Below your `.author` element, create a new `div` element with the class `social-icons`.

Add five `a` elements within that new `div`, and give them the following `href` attributes.

- The first `a` element should have an `href` set to `https://www.facebook.com/freecodecamp`.

- The second `a` element should have an `href` set to `https://twitter.com/freecodecamp`.

- The third `a` element should have an `href` set to `https://instagram.com/freecodecamp`.

- The fourth `a` element should have an `href` set to `https://www.linkedin.com/school/free-code-camp`.

- The fifth `a` element should have an `href` set to `https://www.youtube.com/freecodecamp`.

## Step 10

Within each of your new `a` elements, add an `i` element and give them the following classes:

- Your first i element should have the class `fab fa-facebook-f`

- Your second `i` element should have the class `fab fa-twitter`

- Your third `i` element should have the class `fab fa-instagram`

- Your fourth `i` element should have the class `fab fa-linkedin-in`

- Your fifth `i` element should have the class `fab fa-youtube`

## Step 11

Below your `.heading` element, create a new `section` element with the `class` set to `text`. Within that, create a `p` element with the `class` set to `first-paragraph` and the following text:

>Example Code
>
>Soon the freeCodeCamp curriculum will be 100% project-driven learning. Instead of a series of coding challenges, you'll learn through building projects - step by step. Before we get into the details, let me emphasize: we are not changing the certifications. All 6 certifications will still have the same 5 required projects. We are only changing the optional coding challenges.

## Step 12

Create another `p` element below your .`first-paragraph` element, and give it the following text:

>Example Code
>
>After years - years - of pondering these two problems and how to solve them, I slipped, hit my head on the sink, and when I came to I had a revelation! A vision! A picture in my head! A picture of this! This is what makes time travel possible: the flux capacitor!

## Step 13

Add a third `p` element at the end of your `.text` element, and give it the following text:

>Example Code
>
>It wasn't as dramatic as Doc's revelation in Back to the Future. It just occurred to me while I was going for a run. The revelation: the entire curriculum should be a series of projects. Instead of individual coding challenges, we'll just have projects, each with their own seamless series of tests. Each test gives you just enough information to figure out how to get it to pass. (And you can view hints if that isn't enough.)

## Step 14

After the three `p` elements within your `.text` element, create a `blockquote` element. Within that, add an `hr` element, a `p` element with the `class` set to `quote`, and a second `hr` element.

Give the `.quote` element the text `The entire curriculum should be a series of projects`.

## Step 15

Below your `blockquote` element, add another `p` element with the following text:

>Example Code
>
>No more walls of explanatory text. No more walls of tests. Just one test at a time, as you build up a working project. Over the course of passing thousands of tests, you build up projects and your own understanding of coding fundamentals. There is no transition between lessons and projects, because the lessons themselves are baked into projects. And there's plenty of repetition to help you retain everything because - hey - building projects in real life has plenty of repetition.

## Step 16

Create a fifth `p` element at the end of your `.text` element, and give it the following text:

>Example Code
>
>The main design challenge is taking what is currently paragraphs of explanation and instructions and packing them into a single test description text. Each project will involve dozens of tests like this. People will be coding the entire time, rather than switching back and forth from "reading mode" to "coding mode".

## Step 17

Create one final `p` element at the end of your `.text` element and give it the following text:

>Example Code
>
>Instead of a series of coding challenges, people will be in their code editor passing one test after another, quickly building up a project. People will get into a real flow state, similar to what they experience when they build the required projects at the end of each certification. They'll get that sense of forward progress right from the beginning. And freeCodeCamp will be a much smoother experience.

## Step 18

Below your `.text` element, create a new `section` element and give it a `class` of `text text-with-images`. Within that, create an `article` element with a `class` set to `brief-history`, and an `aside` element with the `class` set to `image-wrapper`.

## Step 19

Within your `article` element, create an `h3` element with the `class` set to `list-title` and the text of `A Brief History`. Below that, create a `p` element with the text `Of the Curriculum`. Then create a `ul` element with the class `lists`.

## Step 20

Within your `ul` element, create six `li` elements. Add an `h4` element with a class set to `list-subtitle` and a `p` element to each of your `li` elements.

Then give the `h4` and `p` elements the following text content, in order, with each `h4` using what's on the left side of the colon, and each p using what's on the right:

- `V1 - 2014`: `We launched freeCodeCamp with a simple list of 15 resources, including Harvard's CS50 and Stanford's Database Class.`

- `V2 - 2015`: `We added interactive algorithm challenges.`

- `V3 - 2015`: `We added our own HTML+CSS challenges (before we'd been relying on General Assembly's Dash course for these).`

- `V4 - 2016`: `We expanded the curriculum to 3 certifications, including Front End, Back End, and Data Visualization. They each had 10 required projects, but only the Front End section had its own challenges. For the other certs, we were still using external resources like Node School.`

- `V5 - 2017`: `We added the back end and data visualization challenges.`

- `V6 - 2018`: `We launched 6 new certifications to replace our old ones. This was the biggest curriculum improvement to date.`

## Step 21

Within your `aside` element, create two `img` elements, a `blockquote` element, and a third `img` element. Give the `blockquote` element a `class` set to `image-quote`.