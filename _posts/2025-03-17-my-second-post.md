---
title: "How to Host a Blog on Github Pages"
date: 2025-03-15 12:00:00 +0100
categories: [Blog]
tags: [second-post, blog,blog-creation]
toc: true
---
Welcome to my blog! This is my second post using the Chirpy Jekyll theme. 

On this post I will be sharing the steps required to Host a Blog for free on Github Pages. Because I will be sharing my experience I will be using one specific CV/Blog Template called [Chirpy](https://chirpy.cotes.page/), but feel free to choose any Template from this [list](https://github.com/search?q=jekyll+theme&type=repositories) the steps I will be explaining here should work the same. 

If you picked a Template and for some reason one of the Steps here did not worked, let me know by sending me an email*.

Steps
1. [Create a Github account if you don't have one](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github)
2. [Follow Option 1. of Chirpy Blog Template Documentation](https://chirpy.cotes.page/posts/getting-started/)

## Step 3: Setup your Blog Local Environment
You will need setup a local environment for writing your future blog posts, to write your blog information and later to customize things on the template.

On my case I followed the setup instructions on Chirpy Getting Started page and did not work for me, but don't worry I will write here what I did differently. 

First things first we will be using Jekyll, a Ruby gem that enables us to cut corners and makes hosting a static web page like our blog really easy. On MacOS we need to install a couple of things to be able to run our local environment:
1. [Install Homebrew & Ruby](https://jekyllrb.com/docs/installation/macos/)
2. Try to install Jekyll(on the last step of previous link)


If you, like me, had issues installing jekyll because of Ruby version, don't worry there is a solution. **Why this error happens?** Sometimes the version we are installing or the version we have in our system does not goes well with Jekyll gem. **Solution** you can install virtual environment for Ruby called rbenv, and then install the version of ruby you need/want. You can do this with the following commands.

```
brew install rbenv
# Instead of 3.4.1 you can use other versions also
rbenv global 3.4.1
```

## Conclusion

Now with the correct version of Ruby you should be able to install 

## References

- [Blog Template Documentation](https://chirpy.cotes.page/posts/getting-started/)
- [Jekyll Documentation](https://jekyllrb.com/docs/installation/macos/)



