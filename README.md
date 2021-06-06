# burgontan

A blog focused theme for Hugo.

## Expected Config Items

```
[markup.goldmark.renderer]
unsafe= true
```

## Optional Config Items

```
[params]
mainColor = "#ac4142"
linkHoverColor = "#f9e9e9"
recentPostsAfterPost = "true"
relatedPosts = "true"
```

## Optional Partial Templates
```
site-header.html
site-footer.html
home.html
```

## Optional Pages

**/about**

Create a page in `content/about.md` and use `layout: staticpage`.

**/archives**

Create a page in `content/archives.md` and use this front matter:
```
---
title: "Posts Archive"
layout: archive
hidden: true
---
```

## Front Matter
```
hidden: true
```
