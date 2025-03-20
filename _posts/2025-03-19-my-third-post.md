---
title: "How to Write Blog Posts on Your Github Pages Blog"
date: 2025-03-19 12:00:00 +0100
categories: [Blog]
tags: [second-post, blog,blog-creation]
toc: true
---


If you follow my last post tutorial on [How to create your Blog with Github Pages]({% link _posts/2025-03-17-my-second-post.md %}), now you have your blog up and running at \<your-github-username>.github.io and you are probable eager to write you first Blog post.

Whenever you clone most of Jekyll themes you will see that they have a folder called ``_posts/``, there is the place where you will be placing your blog post files. Create a file there following this format ``year-month-day-some-blog-title.md`` like this file I am writing right now for example ``2025-03-19-my-third-post.md``.

## Blog post files start with a Header

Our Blog post files require a "header" in order to work, like this one:
```
---
title: "How to Write Blog Posts on Your Github Pages Blog"
date: 2025-03-19 12:00:00 +0100
categories: [Blog]
tags: [second-post, blog,blog-creation]
toc: true
---
```

First parts of this header are easier to understand than others like title, date, categories and tags. This "header" is called Frontmatter, and don't worry this is just an authoring convention popularized by the same static site generator Jekyll we are using to create our blog.

## After Frontmatter comes what really matters

Joke a side after having the Frontmatter header your file(.md) is in good shape for you to add content to it, in the same way I am doing right now. Because we are using Markdown formatting you should follow Markdown tags and syntax to make your content even more interesting. Here are some examples:

```bash
[Google](google.com) # links in markdown
### Big Header
## Medium Header
# Small Header
- # bullet point list
1. # numbered list
``inline text-block highlight``
```

## Conclusion

On this post we learned how to write blog posts, we learned about Frontmatter and most of the things you need to start writing your own blogposts. 

