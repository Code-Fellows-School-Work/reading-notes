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
1. What is a real world use case for the ```alt``` attribute being used in a website?
- It's useful for individuals who have trouble seeing or it can be helpful for those with slow internet speeds
2. How can you improve accessibility of images in an HTML document?
- Add attributes like alt to provide a detailed explaination of the text, use descriptive file names and annotate images with figues and/or captions 
3. Provide an example of when the ```figure``` element would be useful in an HTML document.
- ```figure``` element is useful when paired with ```figcaption``` in order to group an image with it's descriptive content so help with accessibilitiy
4. Describe the difference between a ```gif``` image and an ```svg``` image, pretend you are explaining to an elder in your community.
- Gif images are good for small animations like flipbooks but they don't store a lot of detail whereas svg images enable more detail in an image and are great for detailed illustrations
5. What image type would you use to display a screenshot on your website and why?
- The best image format depends on the website's needs however a png file is typically preferred for website images because it stores images at a higher quality than other formats

## [Using Colors in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)
- Everything in HTML can have color applied such as text, fonts, background, etc.
- Ways to select color are hexadecimal, RGB or HSL 
- ```HWB``` function is similar to HSL except selects whiteness and blackness via percentage
- There are several factors to consider when choosing color such as color compaitability, color accessibility and personal style/preference. Find a balance between the three

## [Styling HTML Text Elements](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)
- Fonts can be modified to include font styles, color and size
- Find the proper balance when choosing font characteristics to ensure it aligns with website design, personal preference and accessibility

### Questions

1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
- Background color is like a blank white sheet of printer paper and foreground color is when you take crayons and color sections areas of the printer paper. So the webpage color is the background and all the content and it's color on the webpage is the foreground.
2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
- I would recommend visiting an online color pallette website to help choose complimentary colors for their website. Then we can select areas of the website of significant importance and use color to help those areas standout 
3. What should you consider when choosing fonts for an HTML document?
- Find the proper balance when choosing font characteristics to ensure it aligns with website design, personal preference and accessibility
4. What do ```font-size```, ```font-weight```, and ```font-style``` do to HTML text elements?
- Font size increases of decreases the side of font, font weight sets how bold text is and font style enables italized font
5. Describe two ways you could add spacing around the characters displayed in an ```h1``` element.
- ```<letter-spacing>``` increases the amount of space between characters and ```<word-spacing>``` increases the amount of space between words

## Things I want to know more about
- Adding gradients to a webpage background and shadows along the border of an image
