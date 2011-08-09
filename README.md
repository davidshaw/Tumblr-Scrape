# tumblr_scrape.rb
## A simple Ruby Tumblr scraper

Every so often, you might find a [Tumblr](http://tumblr.com) user whose tumblog is just *awesome*.

As it stands, in order to download each of their images, you are required to manually browse and right click a whole bunch of pictures, tiring your fingers and probably getting bored long, long before you reach the end of their Tumblr.

tumblr_scrape.rb allows you to quickly and easily download an entire (up to, currently, 9000 images) Tumblog to a directory of your choice.

Usage is simple:

`ruby tumblr_scrape.rb <username> <directory to download> <number of images to download>`

The only required parameter is the Tumblr username: the current working directory is the default download location, and 9000 is (currently) the default max images. There is a random few-second pause between images so that no one accidentally slams Tumblrs servers.

Happy scraping!
