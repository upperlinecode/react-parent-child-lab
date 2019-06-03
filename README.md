# React Parent-Child Lab

In this lab, you'll componentize a website mockup.

## Getting Started in CS50

1. Clone this repository using `git clone`
2. `cd` into the `react-parent-child-lab` folder
3. `npm install`
4. `npm start`
5. If the app compiles with no errors:
    1. click on the `localhost` link, or
    2. tap the `CS50 IDE` link in the header and choose `Web Server`
6. If the app compiles with errors, to view the live app:
    1. tap the `CS50 IDE` link in the header
    2. choose `Web Server`
7. If the app fails to compile, re-clone the repository

## To Do's

A designer at your agency has provided you with a mockup for a redesigned news site homepage. They were going for something that is part Instagram, part Facebook, part Medium.

For now, the team isn't worried about showing actual text in the mockup, so they've used some dummy text from [Hipster ipsum](https://hipsum.co/) and some placeholder images from [placeholder.com](https://placeholder.com/). Once everyone agrees on the layout, the developers and the backend database team will work on passing real text and images into the layout.

Your task is to convert the HTML code in `App.js` into functional components.

As you divide up the HTML mockup into components, here are a few things you'll want to remember:

- Remember to export the function from the component file (the child).
- Remember to import the child function into the appropriate parent component file.
- You can store the components in the same directory as `App.js`, or you can make a subdirectory, e.g. `Components/`, and store them all there (recommended), or you can make a more complex file structure. It may be best to start simple, and as the complexity of your app increases you can make a more complex file structure.
- It is best practice to make the function name match the component name so it's easier to keep track of which component belongs to which file.

You can go about this in whatever way you find easiest, but here are a few tips to help you get started:

- Look for repeated sub-units. If something is repeated, then it will probably benefit from being a child component to some parent element.
- Look for smaller and smaller sub-units that might be used in various different units. Try to be as efficient as possible so you're not creating two child components that return the exact same code.
- Consider using semantic (or meaningful) names for your components so another developer could inspect your code and understand the overall structure of the app.
