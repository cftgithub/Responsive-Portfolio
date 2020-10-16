# Responsive-Portfolio
### Purpose:
To demonstrate my ability to modify a non-responsive layout to a mobile-responsive layout using the pre-determined set of instructions below.
### Instructions
1. Copy the contents of `Basic-Portfolio` (your first homework solution) and paste the mentioned files into `Responsive-Portfolio`.

1. Inside your `Responsive-Portfolio` folder, find your `styles.css` file. You will write your media queries at the bottom of `styles.css`.

1. Use three `@media screen` tags, each with one of these `max-width`s: `980px`, `768px` and `640px`.

   * You use `980px` because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.

   * `768px` is about the width of a tablet and `640px` is about the width of a phone in landscape.

1. Make the layout match the following:

   * `index.html`: [980px](Images/980-index.jpg), [768px](Images/768-index.jpg), [640px](Images/640-index.jpg)

   * `portfolio.html`: [980px](Images/980-portfolio.jpg), [768px](Images/768-portfolio.jpg), [640px](Images/640-portfolio.jpg)

   * `contact.html`: [980px](Images/980-contact.jpg), [768px](Images/768-contact.jpg), [640px](Images/640-contact.jpg)

1. Make the position of the header `static` (the default positioning) when the screen is `640px` wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.

1. Be sure to include the `viewport` tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. _(Hint: You won't need to use exact pixels for anything other than the container)_

1. Deploy your new portfolio (now with media queries!) to GitHub Pages.
