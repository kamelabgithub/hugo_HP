---
date: 2023-04-06
title: "本年度は大幅にメンバが増えました"
linkTitle: " 2023年度新歓"
description: "大学院生 ５名、卒論生２名"
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
---

**太字になりますThis is a typical blog post that includes images.**

The front matter specifies the date of the blog post, its title, a short description that will be displayed on the blog landing page, and its author.

## 見出しになりますIncluding images

Here's an image (`featured-sunset-get.jpg`) that includes a byline and a caption.

{{< imgproc featured-sunset-get Fill "600x300" >}}
灯禾軒にて
{{< /imgproc >}}

The front matter of this post specifies properties to be assigned to all image resources:

```
グレーで囲まれます
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
  params:
    byline: "Photo: Riona MacNamara / CC-BY-CA"
```

To include the image in a page, specify its details like this:

```
{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}
```

The image will be rendered at the size and byline specified in the front matter.


