# website

Website for the Duke Shiny Ed Project

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

## Tips

- Clone the repo and make a new RStudio project.
- Always pull before making any changes in RStudio, since multiple people are now working from the same repo. 
- Load the blogdown package and then type `serve_site()` in the console. This will produce a local copy of the website that you can view in RStudio or in a web browser. 
  - You only need to type `serve_site()` once. As you save your changes, the local copy of the website will automatically update. 
  - Once you are happy with your changes, push them to GitHub!
  
## Resources

- [blogdown](https://bookdown.org/yihui/blogdown/)

