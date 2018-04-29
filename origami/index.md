---
title: "origami"
permalink: /origami/
categories:
  - origami
tags:
  - origami
gallery:
  - url: /images/origami/roses_0.jpg
    image_path: /images/origami/roses_0.jpg
    alt: "a rose is a rose is a rose"
    title: "a rose is a rose is a kawasaki rose"
  - url: /images/origami/roses_1.jpg
    image_path: /images/origami/roses_1.jpg
    alt: "test2"
    title: "praise the sun \o/"
  - url: /images/origami/singed_1.jpg
    image_path: /images/origami/singed_1.jpg
    alt: "trololol"
    title: "singed! mix, mix, swirl, mix..."
---

These are gallery tests for image wrapped in `<figure>` elements.

To place a gallery add the necessary YAML Front Matter:

```yaml
gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"
  - url: /assets/images/unsplash-gallery-image-4.jpg
    image_path: /assets/images/unsplash-gallery-image-4-th.jpg
    alt: "placeholder image 4"
    title: "Image 4 title caption"
```

And then drop-in the gallery include --- gallery `caption` is optional.

```liquid
{% raw %}{% include gallery caption="This is a sample gallery with **Markdown support**." %}{% endraw %}
```

{% include gallery caption="This is a sample gallery with **Markdown support**." %}

