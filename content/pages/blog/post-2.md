---
title: 'Filtering damages GRACE signal quality, and we can counter it.'
date: '2021-10-20'
author: content/data/team/hilary-ouse.yaml
categories:
  - content/data/categories/news.yaml
tags:
  - content/data/tags/jamstack.yaml
  - content/data/tags/netlify.yaml
excerpt: >-
  Filtering is necessary for obtaining meaningful data from GRACE, but it
  suppresses the signal amplitude, changes its phase, and degrades the spatial
  resolution. What can we do to reduce the side effects of filtering?
thumb_image: /images/wrcr22168-fig-0001-m.png
thumb_image_alt: Post 2 placeholder image
image: /images/wrcr22168-fig-0001-m.png
image_alt: Post 2 placeholder image
image_position: left
seo:
  title: 'Non Minor, Inquit, Voluptas Percipitur Ex Vilissimis'
  description: Quae diligentissime contra Aristonem dicuntur a Chryippo
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: 'Non Minor, Inquit, Voluptas Percipitur Ex Vilissimis'
      keyName: property
    - name: 'og:description'
      value: Quae diligentissime contra Aristonem dicuntur a Chryippo
      keyName: property
    - name: 'og:image'
      value: images/classic/post-2.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: 'Non Minor, Inquit, Voluptas Percipitur Ex Vilissimis'
    - name: 'twitter:description'
      value: Quae diligentissime contra Aristonem dicuntur a Chryippo
    - name: 'twitter:image'
      value: images/classic/post-2.png
      relativeUrl: true
layout: post
---
GRACE data is noisy, which means filtering is essential to suppress noise. However, filtering also affects signal quality. In <https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2017WR021150,> authors describe a method that uses GRACE data only to estimate the signal loss due to filtering. They first describe the mathematical equations that define the signal loss due to filtering and then provide a neat data-driven method. This method is also compared with other signal restoration methods and was found to outperform them significantly.
