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
```

### Menus
```
[[menu.main]]
    name = "About"
    url = "/about/"
[[menu.main]]
    name = "Tags"
    url = "/tags/"
[[menu.main]]
    name = "Archive"
    url = "/archive/"
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
