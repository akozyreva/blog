# blog
This is little blog, which was configured, using HUGO

https://gohugo.io/

The theme, which was used:

https://github.com/hauke96/hugo-theme-hamburg

# Demo

https://akozyreva.github.io/german-blog/

# Requirements
- preinstalled HUGO on computer

# Creating the posts
For creating new post in work folder you need to type
```
hugo new posts/<name_of_post>.md
```
By default the status of post is draft. You need to change it to "false" in order to publish it"
````
draft: false
````
# Running site locally
In order to run site locally use the following command:
```
hugo server -D
```
-D allow you to show drafts of your posts
# Deploying on Github host
In your work directory run the following command:
````
./deploy.sh
````
