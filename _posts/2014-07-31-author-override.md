---
layout: post
title: "Fakultas Sain & Tekhnologi"
author: Rona Rosita
modified:
excerpt: "Mahasiswa Program Studi Sistem Informasi
Fakultas Sains dan Teknologi, Universitas Islam Negeri Sultan Syarif Kasim, Riau."
tags: []
---

For those of you who may have content written by multiple authors on your site you can now assign different authors to each post if desired.

Previously the theme used a global author for the entire site and those attributes would be used in all bylines, social networking links, Twitter Card attribution, and Google Authorship. These `owner` variables were defined in `config.yml`

Start by modifying or creating a new `authors.yml` file in the `_data` folder and add your authors using the following format.

{% highlight yaml %}
# Authors

Rona Rosita:
  name: Rona Rosita
  web: http://thewhip.com
  email: ronarosita12@gmail.com
  bio: "Mahasiswa Program Studi Sistem Informasi'13,
  Fakultas Sains dan Teknologi, Universitas Islam Negeri Sultan Syarif Kasim, Riau."
  avatar: ronaedit.jpg
  twitter: extravagantman
  google:
    plus: Ronarosita

Rona Rosita:
  name: Rona Rosita
  email: ronarosita12@gmail.com
  bio: "Mahasiswa Program Studi Sistem Informasi
  Fakultas Sains dan Teknologi, Universitas Islam Negeri Sultan Syarif Kasim, Riau"
  avatar: ronaedit.jpg
  twitter: ronarosita
  google:
    plus: CorneliusFiddlebone
{% endhighlight %}

To assign Rona Rosita as an author for our post. You'd add the following YAML front matter to a post:

{% highlight yaml %}
author: billy_rick
{% endhighlight %}
