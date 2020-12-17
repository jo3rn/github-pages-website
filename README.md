# github-pages-website
 This is a basic example of how to use GitHub Pages aka getting a simple website ready in no time.
 
 You can find the source of this website at [https://github.com/jo3rn/github-pages-website/](https://github.com/jo3rn/github-pages-website/)

# Steps to build your own website

## Enable in settings
![Screenshot of GitHub Pages section in settings](screenshot_settings_github_pages.PNG)

## Add a configuration file
Create a file called `_config.yml`. Fill it with data to configure the website. There are tons of options. A web search will help you with that.

## Add content
By default your `README.md` will be used as content provider for the main page of your website. Alternatively you can create a file called `index.md` in the top level directory.

## Have a look at your website
It's already available! Browse to `https://<USERNAME>.github.io/<REPOSITORY-NAME>/`

In this case it is [https://jo3rn.github.io/github-pages-website/](https://jo3rn.github.io/github-pages-website/).

## Add pages
The easiest way to create more pages for your website is to add more markdown files. For this website I added `another_page.md` to which I can also [link](another_page.md) to from the current page.

## Change theme
You can change the outfit of your website by choosing a different theme. For example, to change to the modernist theme you add this line to the config: `theme: jekyll-theme-modernist`. Here is a list of [supported themes](https://pages.github.com/themes/). I have kept the default theme for this website.

## Further steps
There is a lot more to customize once your website is running. Feel free to explore the [documentation for GitHub Pages](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages).
