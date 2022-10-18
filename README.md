# IOC Jekyll Starter theme

For detailed instructions and videos, please see the IOC Student Hub. This readme will just contain a few important notes.

The starter theme uses:
- jekyll
- Gridlex for the flexbox grid
- snipcart for eCommerce
- lightwidget for the instagram widget
- lightbox2 for the pop-up images in the shop
- the jekyll-archives plugin to generate category archive pages automatically
- the jekyll-paginate plugin to automatically paginate old blog posts in the archive folder

Because the starter theme uses plugins, the process for running jekyll in terminal is slightly different.

1. In terminal navigate to your folder as normal
2. Run `bundle install`. This will download and install all the plugins
3. To ensure that you run jekyll using the right plugins each time, instead of just entering `jekyll serve` you will now enter `bundle exec jekyll serve` each time
4. Remember that if you make any changes to the _config.yml file then you need to restart terminal by entering `control C` and then re-entering `bundle exec jekyll serve`

As this is a new theme that hasn't been tested extensively, please let us know if you find any bugs, or any of the code confusing.

You may notice a few different files including a GEMFILE and GEMFILE.lock, these are both related to the two jekyll plugins used.


## If you already have a site and want to add a blog

1. Copy and paste the _posts folder into your project
2. Copy and paste the 'archive' and 'post' layout into your layouts folder
3. Copy the Gemfile into your main folder
4. Copy the contents of the _config.yml file into yours.
5. Save the whole site
6. Close terminal and restart. Navigate to the folder and this time run 'bundle install'. It will flash and not say anything for a minute, then eventually should start downloading. It will say 'Bundle Complete!'
