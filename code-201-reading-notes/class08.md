# Class 08 - CSS Layout

## [Flexbox](https://web.dev/learn/css/flexbox/)
- Flexbox layout model is designed for one-dimensional content
- Enables a bunch of different sized elements to be displayed using the best and optimal layout
- For ex. a sidebar that is on the right side will break to a new line if the web page size is reduced
- Main axis are set by the ```flex-direction``` property

### Questions

1. Flexbox is designed for one-dimensional content. Explain what this means.
- It focuses on arranaging and aligning elements along a single axis either left to right or top to bottom enabling websites to dynamically adjust the position of it's content
2. Explain the difference between the main axis and cross axis.
- Flex items move as a group in the direction along the main axis and the direction perpendicular to the main axis is called the cross axis
3. How can using certain properties of flexbox negatively impact accessibility?
- Reversing the flow of items as opposed to maintaining it's normal left-to-right visual display may cause things like screen readers to incorrectly state content out of order.

## [Flexbox Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- To begin using flexbox, use the ```display: flex``` value on the parent element in the CSS file
- That causes the element to become a flex container
- By default, flex will display as a block element but the value ```display: inline-flex``` to behave like an inline element
- ```flex-direction``` specifies the direction of the main axis and defaults to ```row```
- ```flex-wrap``` can help mitigate cramped content by allowing squeezed content to flow and continue in a separate row
- ```flex-direction``` and ```flex-wrap``` can be shorthanded to ```flex-flow```

### Questions
1. What are some advantages of using flexbox over float?
- It's a responsive design that dynamically adjusts to the size of the content. It's easier to use and more predictable than using float.
2. How does this topic connect with your long term goals?
- Flexbox will be helpful for polishing my digital resume. Currently the resume looks barebones and potentially does not appear optimized on different viewing platforms, but using flexbox will ensure that I maintain a polished and organized appearance where the content does not appear crowded and stacks nicely on the page.

## Additional Resources

## [More Flexbox Layout](https://web.dev/learn/css/layout/)

## Things I want to know more about
- What are some additional properties to control and use flexbox?
- Can I use flexbox for a grid?
