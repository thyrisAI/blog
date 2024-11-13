# Welcome to ThyrisAI Blog

## Contributing

All blog posts have their own folder under the `blog` folder.

### Formatting

File structure should be like this:
```
|
|- blog_id/
|--- view.mdx
|--- images/
|--- |--- example.png
```

The `view.mdx` file is the contents of your blog post. Put the images under `images` folder in the same directory.

### Blog Slug

Slugs are very important. They have all the required metadata for the blog post. Example slug:

```
---
title: "Test"
datePublished: "Nov 18 2024"
categories: ['blog']
status: "published"
image: "example.png"
description: "Example blog post."
---
```

This slug needs to be at the top of the `view.mdx` file.

`title`: The title of your post.\
`datePublished`: The date you wrote the blog post. The formatting needs to be exactly the same: `Mon DD YYYY` e.g. `Nov 13 2024`\
`categories`: The categories of your blog in an array of strings\
`status`: The status of your blog.\
`image`: The main image of your blog. Write the file name as is. It will get the file from the `images` folder of the blog's folder.\
`description`: What is your blog post about? A short description for readers to have a better context of your blog post.
