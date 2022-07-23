# Class 11: Audio, Video, Images

Media makes a web app feel alive and dynamic. Media content also enhances accessibility by delivering content by the different senses.

## Video and Audio Content

<!-- Questions:
  
  1.Explain how the ability to use video and audio on the web has evolved since the early 2000s.
  2.Describe the use of the src and controls attributes in the <video> element.
  3.Why is it important to have fallback content inside the <video> element?
  4.Write a very short story where <audio> and <video> are characters.

 -->

 1.Before HTML5 audio and video had to be embedded by plugins like Flash.
 2.The `src` (source) attribute contains a path or address to the media
 3.Controls give users the ability to control the video like play/pause, FF/RW, etc...
 4.Video and audio both have a story to tell, so long as they have the right sources. And you don't want them to start rambling, so make sure you have a way to stop them with some controls.

## A Complete Guide to Grid

 <!-- Questions:
  
  1.How does Grid layout differ from Flex?
  2.Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

  -->

  1.The primary difference is that flexboxes are one-dimensional
  2. A *Grid container* is the parent of all grid items and is the element where `display` lives. *Grid lines* are the dividing lines that build the grid, and *grid items* are the children of the grid container, where the content occurs.

## Responsive Images

<!-- Questions: 

  1.Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
  2.Define the following <img> attributes srcset and sizes. Write an example of how they are used.
  3.How is srcset more helpful for responsive images than CSS or JavaScript?

 -->

 1.Could reduce bandwidth for people on slower or metered connections like mobile data
 2. Both are choices of properties to be chosen by the user agent to load a page dynamically.`srcset` is a set of srcs separated by commas for possible image choices. `sizes` gives a comma-separated list of sizing options.
 3.CSS and JS preload images before adjusting to page, while `srcset` "chooses" an appropriate source before preloading. It saves load.

### Bookmark and Review

  -[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

  -[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

  -[CSS Tricks](https://css-tricks.com/)

  -[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

  -[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

### Things I Wish Knew More About
