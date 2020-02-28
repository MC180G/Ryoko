# Ryoko
**Author** Matt Colson



### Overview

I've created a web app that lets users view and leave comments on articles about Japanese Festivals scraped from a particular site. Whenever a user visits this site, the app scrapes stories from **japan-guide.com** and displays them for the user. Each scraped article is saved to the application database with the following information:

     * Headline - the name of the Festival

     * Date - the approximate date of the Festival

     * Summary - a short summary of the Festival

     * URL - the url to the original article

     * Photo - a picture of the Festival

  Users are also able to leave comments on the articles displayed and revisit them later. The comments are saved to the database as well and associated with their articles. Users are also able to delete comments left on articles. All stored comments are visible to every user.

* ### Built With:

* NPM Packages:

   * express

   * express-handlebars

   * mongoose

   * cheerio

   * axios

   *Heroku (with mLab) - BackEnd

  ## Tips

* Go back to Saturday's activities if you need a refresher on how to partner one model with another.

* Whenever you scrape a site for stories, make sure an article isn't already represented in your database before saving it; Do not save any duplicate entries.

* Don't just clear out your database and populate it with scraped articles whenever a user accesses your site.

  * If your app deletes stories every time someone visits, your users won't be able to see any comments except the ones that they post.

### Helpful Links

* [MongoDB Documentation](https://docs.mongodb.com/manual/)
* [Mongoose Documentation](http://mongoosejs.com/docs/api.html)
* [Cheerio Documentation](https://github.com/cheeriojs/cheerio)