---
layout: post
title: Acapulco Sandalye
subtitle: Bir meksika sandalyesi
cover-img: /assets/img/IMG_6247.png
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [Acapulco Chair]
comments: true
mathjax: true
author: Atölye Garaj
---


Sandalye yapımı için demir çubuklar kaynak makinesi, boya için komprasör, oturma yeri için de ip kullandım Profile uygun şekli vermek için de bir bükücü. İstek üzerine üretileceğinden renk ve sallanır yada sabit olması konsunda karar sizin 


![Sandalye1](/assets/img/IMG_6247.png){: .mx-auto.d-block :}

It can also be centered!

![Sandalye2](/assets/img/IMG_6248.png){: .mx-auto.d-block :}

![Sandalye3](/assets/img/IMG_6249.png){: .mx-auto.d-block :}



### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

{: .box-success}
If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})

<details markdown="1">
<summary>Click here!</summary>
Here you can see an **expandable** section
</details>
