# Lame Jam: Learn. Game. Jam.

This is the homepage of the Lame Jam in Ottawa. The Lame Jam is an initiative to introduce new students into the world of game development and game jams by hosting short design and development talks, bringing in industry professionals, and offering mentoring and support from more experienced developers. 

## Updating the Website

The website is using a Jekyll theme called [Cayman-Blog](https://github.com/lorepirri/cayman-blog). It's an awesome theme, go support them!

### New Pages

To add new pages to the site, the simplest way is to duplicate the about page (about.md), rename it, and update the meta-data. Some quick notes:

* All pages use markdown. Learn you some!
* Pages all have parent layouts. Feel free to make your own. 
  * I recommend duping About because it's already set up to use the default page template and has some configuration
* Configuration details are at the top of the page. Easy enough to figure out!

### News Posts

* To make a new news post, make a file in the `/_posts` folder (if it's not there, create it)
* Name it `YYYY-MM-DD-the-post-title.md` with the current date
* Fill out the meta table at the top (layout: post, title, optionally: author, tagline, categories, thumbnail) 
* Best post example with lots of metadata [here](https://github.com/lorepirri/cayman-blog/blob/master/_posts/2017-04-20-post-content-styles.md)
* Lots of example posts [here](https://github.com/lorepirri/cayman-blog/tree/master/_posts)
