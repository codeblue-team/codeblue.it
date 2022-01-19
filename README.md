# codeblue.it
Repository for the codeblue.it website

# How to use
The site us built on the blogdown package for R markdown. For details please refer to https://bookdown.org/yihui/blogdown/

To get started quickly adding posts:

- clone the repository
- open in RStudio
- move to ./content/post
- add a new folder for your post; naming convention YYYY-mm-dd_short_title
- preview the new website using blogdown::serve_site() . Changes are reflected live, so no need to use this command over and over again
- make sure the new post is in order
- check that the rest of the website still works
- buikd site using blogdown::build_site()
- synchronise the content of the ./public folder with the host cloud
- enjoy!
