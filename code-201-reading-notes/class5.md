# Class 05 - Images, Colors, Text

## [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- To add an image, use the ```<img>``` element along with ```src``` attribute (URL for image or file path location) and ```alt attribute``` (descriptive accessibility)
- Best practice is to host images on website instead of linking image via URL
- Ensure proper media licenses are abided to avoid copyright
- ```width``` and ```height``` are attributes that resize an image
- ```title``` attribute as a caption during a mouse hover-over

## [Media Format Recommendations](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#common_image_file_types)
- Pictures are available in multiple formats and choose the right format depending on the webpage needs

### Questions
1. What is a real world use case for the alt attribute being used in a website?
- It's useful for individuals who have trouble seeing or it can be helpful for those with slow internet speeds
2. How can you improve accessibility of images in an HTML document?
- Add attributes like alt to provide a detailed explaination of the text, use descriptive file names and annotate images with figues and/or captions 
3. Provide an example of when the figure element would be useful in an HTML document.
- ```figure``` element is useful when paired with ```figcaption``` in order to group an image with it's descriptive content so help with accessibilitiy
4. Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
- Gif images are good for small animations like flipbooks but they don't store a lot of detail whereas svg images enable more detail in an image and are great for detailed illustrations
5. What image type would you use to display a screenshot on your website and why?
- The best image format depends on the website's needs however a png file is typically preferred for website images because it stores images at a higher quality than other formats