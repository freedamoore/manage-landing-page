## My solution to the below Frontend Mentor challenge

For my solution I've used Semantic HTML, CSS3 and vanilla JS.

CSS Grids and Flexbox in combination with media queries were used for the responsive layout.

On mobile screens the testimonials section turns into a carousel. This was achieved using `flex: 0 0 100%;` in CSS to make one testimonial dominate the screen and then adding a javascript onClick event listener to navigate between testimonials.

# Frontend Mentor - Manage landing page

![Design preview for the Manage landing page coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges allow you to improve your skills in a real-life workflow.


## The challenge

Your challenge is to build out this landing page and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- See all testimonials in a horizontal slider
- Receive an error message when the newsletter sign up `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly
