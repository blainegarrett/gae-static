# GAE-Static: Hosting on Google Cloud Made Simple

A simple base project starter for static websites on Google AppEngine &amp; Google Cloud Services. See [gae-static.appspot.com](http://gae-static.appspot.com) for full documentation and examples or visit [the project page on github](https://github.com/blainegarrett/gae-static).

### Installation Instructions and Getting Started
See the [project homepage](http://gae-static.appspot.com/) for an overview and [absolute primer guide](http://gae-static.appspot.com/absolute-primer.html).

### Project Highlights of gae-static
* Host assets (html, css, js, images, etc) anywhere in your site folder structure like normal web hosting
* Your directory roots serves up index.html files (customizable)
* Does not require any knowledge of programming languages to get your site up an running
* Does not require fiddling with the command line to deploy to Google Cloud.
* Easily develop your website on your own machine and deploy to Google Cloud.
* Lighting fast and cheap (free?) to host on Google App Engine
* Easily integrate with Google Cloud Storage for CDN support

### Current Limitations ([See All](https://github.com/blainegarrett/gae-static/issues))
* Can not customize error pages (404 and various GAE errors) [Issue #3](https://github.com/blainegarrett/gae-static/issues/3)
* Can not list contents of directories [Issue #2](https://github.com/blainegarrett/gae-static/issues/2)
* Folders without trailing slash do not 301 Redirect [Issue #1](https://github.com/blainegarrett/gae-static/issues/1)

Experience other issues? Have requests? Feel free to [file a ticket](https://github.com/blainegarrett/gae-static/issues) on the github project or contribute a fix.

### Sites Utilizing gae-static
* [gae-static.appspot.com](http://gae-static.appspot.com) - Vanilla install of the gae-static project with documentation
* [blaineandkatie.com](http://blaineandkatie.com) - Blaine and Katie Garrett's wedding website
* [karnakgallery.com](http://karnakgallery.com) - Promotional site for the "All Over The Walls" documentary by Blue Bridge Media
* [antistarband.com](http://antistarband.com) - Website for Midwest hard rock band Antistar 

If you have a website that utilizes GAE Static, please message ([@blainegarrett](https://twitter.com/blainegarrett)) and we'll add it to the list.

## Contribution Notes
This project was started by Blaine Garrett ([website](http://blainegarrett.com)). If you would like to contribute to this project, feel free to make pull requests against it and tag Github user @blainegarrett

## Additional Notes and Resources
* [Dead Simple App Engine Static Hosting](http://gusclass.com/blog/2013/09/27/dead-simple-app-engine-static-hosting/) by [Gus Class](http://gusclass.com/) - Addresses the "naked" folder redirect
* [Free Static Page Hosting on Google Appengine in 5 minutes](http://www.fizerkhan.com/blog/posts/Free-Static-Page-Hosting-on-Google-App-Engine-in-a-5-minutes.html) A similar solution with more prescribed directory structure. Includes skip files directive for common files
* [Implementing a static website in Google App Engine](http://www.enkisoftware.com/devlogpost-20130823-1-Implementing_a_static_website_in_Google_App_Engine.html) Another very specific solution. Addresses custom error pages.
* [Github project - app-engine-static](https://github.com/faisalraja/app-engine-static) - A similar static solution that leverages Jinja2 template system for rendering of static content - requires some python and command line knowledge