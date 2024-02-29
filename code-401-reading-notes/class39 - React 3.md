# Class 39 - React 3

## Reading

- [NextJs](https://nextjs.org/docs)
    - NextJS doc page with a getting started tutorial
- [React Context for Beginners](https://www.freecodecamp.org/news/react-context-for-beginners/)
    - React Context allows to pass down state to components without using props
    - Useful for passing data that does not change often
        - ex. theme data (light/dark mode), authentication data, location-specific data
    - Useful to avoid passing state to components that do not require knowledge of this data

## Videos

- [Why I'm using Next.js in 2020](https://www.youtube.com/watch?v=rtgbaKBhdkk)
    - Software engineer shares top 5 reasons why to use NextJS
- [Learn useContext In 13 Minutes](https://www.youtube.com/watch?v=5LrDIWkK_Bc)
    - Tutorial that compares and contrast using a functional component and class component with useContext hook

## Bookmark and Review

- [Next.js Examples](https://github.com/vercel/next.js/tree/canary/examples)

## Reading Questions

### What is React Context, and how does it help in managing state and data sharing in a React application?

    - React Context helps pass down data that does not change often to components without using props.
    - Useful for passing theme data, authentication data and location-specific data
    - Helps organize state data flow and avoids passing state to components that don't require knowledge of that data

### Explain the useContext Hook and how it can be used to access data from a React Context within a functional component.

    - useContext Hook enables functional components to access data from a React Context without needing to wrap in a Context Consumer (from ChatGPT)

### Describe the purpose of Next.js, and provide an example from the Vercel Next.js Examples reading on how it can be used to build a scalable web application.

    - Next.js provides server-rendered React applications as opposed to the traditional client-side rendered application 
    - Enables increased webpage performance, load only required code versus the entire webpage, built in support for CSS and Sass, and near-zero configuration designed to work out of the box

## Things I want to know more about

    - I don't quite understand useContext Hook. I'd like to see an example
