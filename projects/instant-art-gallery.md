# Instant Art Gallery

I wanted to provide more clear, written instructions about what I'd like you to do with the art gallery code we played with in class last night. If you were there last night you probably don't need these first few steps, but here they are none the less:

- Login to [github.com](https://github.com)
- Login to [glitch.com](https://glitch.com) (one can login with one-click once you've logged-in with GitHub)
- Go to the starter code for this project: [https://glitch.com/~instant-art-gallery](https://glitch.com/~instant-art-gallery)
- Click the "View Source" button to view the code
- In the upper-right-hand corner of the editor click on the "Remix This" button to make your own copy of the project you can start editing.

In class we went through the JavaScript file and talked about what the various pieces did. We also updated the "tags" that were being searched to return different kinds of images for our gallery.

On the CSS side of things we updated the style to give the images an appearance of a frame and make it look like they were actually paintings or photos hung up on a gallery wall. This included adjusting borders, padding and margins, along with some fun visual tricks like shadows, gradients and [transforms](https://css-tricks.com/almanac/properties/t/transform/).

I'd like you all to continue working on making changes to this project with the intent to share them in class on Thursday. I'll leave a little time at the beginning of class Thursday to work on this, but please try to find time before class as well. Here are a list of ideas to explore:

- Try adjusting the colors, utilizing web fonts to add a title of some kind to the page (CSS)

-  Right now the images are horizontally aligned. Try aligning them vertically instead (CSS)

- At the very end of class we used a pseudo selector to target every other image in the gallery:  #gallery img:nth-child(odd). You can also use this pseudo-selector to target specific children in the hierarchy, such as the 3rd item like so #gallery img:nth-child(3). Try experimenting with this to give each image in the gallery a different feel of some kind. (CSS)

- Focus on making the gallery responsive so that the images look good on large and small screens. A percentage-based approach can sometimes work, but often you'll have to utilize [media-queries](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) at some point to get it just right. (CSS)

- Experiment with [CSS Filters](CSS Filters) to give the images in the gallery a similar look & feel (CSS)

- Right now the number of images to display is hard-coded into our JavaScript via the numberOfImages variable. Our call to the Flickr API returns 20 images we can potentially use. Can you change this approach to display a random number of images from what's available? (JavaScript)

- Make it so that a different set of images are displayed every time the "Curate" button is pressed without needing to manually change the tags variables in the code each time. The solution can include creating a text input that allows the user to manually provide the tags, but it doesn't necessarily have to. (JavaScript)

- Try adding several different buttons that allow the user to choose which "gallery" they want to view. When each of those buttons is pressed, pull from a different set of tags and style the paintings and gallery in a different way. This is probably the most complicated item on this list :) (JavaScript + CSS)
You're free to experiment however you with, but hopefully these prompts will help.

