# Class 11 - Audio, Video, Images

## [Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
- Prior to HTML media elements, videos and audio were rendered using plug-ins like Flash and Silverlight
- Nowadays HTML has replaced those old plug-ins
- Embedding video is similar to embedding images
- Fallback content is an alternative to the media content

### Questions
1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
- Video and audio previously used browser plug-ins like Flash and Silverlight in order to render media content however those plug-ins had security and accessibility issues and have been replaced with native HTML solutions
2. Describe the use of the ```src``` and ```controls``` attributes in the ```<video>``` element.
- ```src``` is the source that contains the path to the video content and ```controls``` allows the user to control medial playback
3. Why is it important to have fallback content inside the ```<video>``` element?
- In case the media content is unable to render on the webpage, then it's an alternative to the media content
Write a very short story where ```<audio>``` and ```<video>``` are characters.
- ```audio``` and ```video``` had a goal to buy a new home. After many years of working in the developer factory, they saved enough money and decided to buy a fixer-upper single-family home in html land. The house was filled with bugs and security issues, but ```audio``` and ```video``` were commited to finding their forever home and decided to purchase. They bought from a nice couple called ```Flash``` and ```Silverlight``` and learned they planned to move somewhere far away to be never seen again. In the end, ```audio``` and ```video``` were happy with their purchase and they fixed the home's previous bugs and security issues

## [Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- Grid is a two-dimensional layout that solves one-dimensional problems that float and flexbox does not solve
- Use CSS code ```display: grid``` and use ```grid-template-columns``` and ```grid-template-rows``` to modify grid size
- This article has great grid examples using html markup with css writeup to grid appearance on webpage

### Questions
1. How does Grid layout differ from Flex?
- Grid is two-dimensional allowing to arrange content in both rows and columns whereas flex is one-dimensional and arranges content in either one row or one column
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
- Grid container is the direct parent of grid elements and defines the grid area
- Grid item are child elements of a grid and they are positioned and aligned within the grid container
- Grid line are horizontal or vertical lines that divide content within the grid

## [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
- Responsive images enable adaptive image size adjustments within the html webpage based on the size of the screen the user is using
- Resolution switching provides multiple options for an images and allows the brower to choose the appropriate one
- ```srcset``` allows the browser to choose between which image size to you
- ```sizes``` provides the browser a recommendation for which image to use

### Questions
1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
- Reduce data transfer bandwidth which can result in faster loading times
2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.
- ```srcset``` allows the browser to choose between which image size to you
- ```sizes``` provides the browser a recommendation for which image to use

   - < img src ="image.jpg"

   - srcset ="image.jpg 2x, image.jpg 3x" 

   - sizes="(max-width:600px) 100 vw, (max-width: 1024px) 50vw">

        - 2x and 3x tells the browser to use either this image for this resolution density or the other

        - images up to 600 pixels use 100% viewport and images between 601-1024px use 50% viewport

3. How is srcset more helpful for responsive images than CSS or JavaScript?

- Reduces browser workload by conducting all the decision-making within the html webpage as opposed to rendering a separate file 

## Additional Resources

## [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

## [Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)

## Things I want to know more about

- Are there any advantages of using CSS or JavaScript to do the same thing and choose image size for browser optimization?