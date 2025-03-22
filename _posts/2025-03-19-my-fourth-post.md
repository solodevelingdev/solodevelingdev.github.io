---
title: "How to Customize Chirpy Jekyll Template"
date: 2025-03-21 12:00:00 +0100
categories: [Blog]
tags: [fourth-post, blog,blog-creation]
toc: true
---

If you read and applied the knowledge of my previous posts about [How to Host a Blog on Github Pages]({% link _posts/2025-03-17-my-second-post.md %}), [How to Write Blog Posts on Your Github Pages Blog]({% link _posts/2025-03-19-my-third-post.md %}), then the next very thing you might want is to customize your blog, make it look more the house of your writings.Here on this post we will learn, using Chirpy template, how to customize the Profile picture, to add your social media or email account and also how to make one of the buttons on the front page redirect the viewer to other place on the web( like a store page for example).

## Profile Picture

This is the easiest one but it has its own particularities. So using Chirpy Template theme, most of easy things to change are on the ``_config.yml`` file. There you hit Ctrl+F or &#8984;+F on mac, and look for ``avatar``, this is the variable responsible for loading your profile picture. 

If you provide any png/jpeg picture path, like ``avatar: /assets/solodeveling_profilepic4.png`` for example, you will be able to see the difference by running your blog locally by executing:

```
bundle exec jekyll serve
```

The issue is that if your picture does not have simetric dimensions or square dimensions like ``200x200`` it will not look precisely placed, at least when using Chirpy template. So be sure to convert your image to a file with square dimensions and filled with the content/image you want.

## Social Media credentials

For this one things start to get a bit more fun 🙃. The first changes I encourage you to do are using still ``_config.yml`` file, there are a lot of things you can change there involving your personal info and your social media links, for example:

```YAML
title: SoloDevelingDev # the main title

tagline: A Dev Rank A working towards Rank S. # it will display as the subtitle

# Futher down on the file

url: "https://solodeveling.dev"

github:
  username: solodevelingdev # change to your GitHub username

twitter:
  username: solodevelingdev # change to your Twitter username

social:
  name: SoloDevelingDev
  email: solodeveling.dev@gmail.com # change to your email address
  links:
    # The first element serves as the copyright owner's link
    - https://x.com/solodevelingdev # change to your Twitter homepage
    - https://github.com/solodevelingdev # change to your GitHub homepage
    # Uncomment below to add more social links
    # - https://www.facebook.com/username
    # - https://www.linkedin.com/in/username

```

## Links to outside

If you have things like your own store or your own services page and you would like to have a link from your blog to your services website, keep reading 😉. 

One solution would be to change some information on ``_data/contact.yml`` and for example change the fontsawesome icon. There in ``contact.yml`` file you can do the following:

```YAML
- type: email
  icon: "fas fa-envelope"
  noblank: true # open link in current tab

- type: apps
  icon: "fas fa-rocket"
  noblank: true
  url: 'https://store.com'
```

Here we changed the icon to one of the fontsawesome icons ``fa-rocket`` and we redirect the reader to a random website called ``store.com``.

## Conclusion

On this Post you learned How to Customize your Blog to look more like you and also to link your blog to other things you do or sell on the internet 🙃.