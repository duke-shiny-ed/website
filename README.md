# website

Website for the Duke Shiny Ed Project

[![Netlify Status](https://api.netlify.com/api/v1/badges/820421fb-e04c-4bfb-b99a-bed0bd3199c8/deploy-status)](https://app.netlify.com/sites/duke-shiny-ed/deploys)

## Info for building 

- This site is made using [blogdown](https://github.com/rstudio/blogdown) and Hugo. 

To install blogdown: 

```
install.packages('blogdown')
```

- You will also need to install Hugo. You can install it using a command in blogdown.

```
install_hugo()
```

- The website is using the [Hugo Academic](https://themes.gohugo.io/academic/) theme.

## Update your project page 

- Go to *content* -> *project* -> *folder for your app*
- Put a screen shot of your app in your folder under the name *featured.jpg* (.png file should also work). You will need to delete the image that's currently in the foldr before saving the new one. 
- Update the index file: 
  - In the header: 
    - add image caption
    - change url to the url for your app
    - update the summary
    - update the title
    - update the url to the code to point to your app repo (if you wish)
  - In the body: 
    - add description of app (if you wish)
    - add instructions on how user can flow through the app

You can use Markdown syntax when you write your instructions. Here's a guide for Markdown syntax: https://www.markdownguide.org/cheat-sheet/

Type `serve_site()` in the console once to see a preview of the site. The site will render in the "Viewer" pane in Rstudio. If you want to see it in a web browser, click the icon next to the broom icon. 

Each time you save changes, the webpage will update in your browser. 


## Tips

- Clone the repo and make a new RStudio project.
- Always pull before making any changes in RStudio, since multiple people are now working from the same repo. 
- Load the blogdown package and then type `serve_site()` in the console. This will produce a local copy of the website that you can view in RStudio or in a web browser. 
  - You only need to type `serve_site()` once. As you save your changes, the local copy of the website will automatically update. 
  - Once you are happy with your changes, push them to GitHub!

## Update your "Meet the Team" page

- Go to *content* -> *authors* to find your folder. 
- In your folder, update your information in the *_index.md* file. Leave the field blank if you don't want to include that info. 
  - **Note:** Only include a link to your Twitter account if you use it as a professoinal account. Don't include links to any personal social media.
- Add a photo to the folder. Be sure the photo is called *avatar.jpg*. (A .png should also work). 

## Resources

- [blogdown](https://bookdown.org/yihui/blogdown/)

