# Class 41 - React 4

## Reading

- [Next.js - Dynamic Routes](https://nextjs.org/learn/basics/dynamic-routes)
    - Tutorial on how to implement dynamic routes within a NextJS application
- [Next.js - Deployment](https://nextjs.org/learn/basics/deploying-nextjs-app)
    - Tutorial on how to deploy project from GitHub to Vercel

## Videos

- [Optional: Next.js 10 is here](https://www.youtube.com/watch?v=JWCS5IdECVI)

## Bookmark and Review

- [Next.js - Static File Serving](https://nextjs.org/docs/pages/building-your-application/optimizing/static-assets)

## Reading Questions

### Explain the concept of dynamic routes in Next.js and how they differ from static routes.

    - Unlike static routes that are predefined paths within the web application, dynamic routes enable web pages to display different content based on the post ID
    - It uses a special syntax such as [id].js

>*Answer*

### Describe the process of deploying a Next.js application. What are the key steps involved, and what are some deployment platforms you can use?

    - Push all code updates to GitHub, import project into Vercel, and verify implementation settings prior to deployment
    - The reading specifically calls out Vercel as a deployment platform but other platforms are netlify, AWS and Heroku

### How does Next.js handle static file serving? Discuss the default folder structure for storing static assets and explain how to reference them in a Next.js application.

    - Input files into the public directory 
    - For HTML references, use a relative path to display the static file
    - For JavaScript references, assign the static file to a variable using a relative path then call the variable in a return statement or function

## Things I want to know more about

    - Are video or media files also stored in the public directory?

