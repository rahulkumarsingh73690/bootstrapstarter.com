---
layout: post
title: "Pintereso - Free Jekyll Theme"
theme: "Pintereso"
subtitle: "Jekyll Bootstrap Theme"          
categories:
    - Jekyll
tags: 
    - blogging
    - masonry
    - portfolio
    - freelancer
    - full-websites
    - photography
version:
    - Bootstrap 4
html: https://bootstrapstarter.com/bootstrap-templates/template-pintereso-bootstrap-html/
description: "A Jekyll theme built with Bootstrap 4 suitable for content curation, portfolio, blogging, photography etc."
image: "https://wowthemesnet.github.io/template-pintereso-bootstrap-jekyll/assets/images/screenshot.jpg"
---

# Pintereso, a free Bootstrap Jekyll theme suitable for content curation, portfolio, blogging, photography

### Features

- Theme Built for Jekyll
- 100% Compatible with Github pages
- SEO
- Search
- Index Pagination
- Post Share/Pin Save
- Post Categories
- Prev/Next Link
- Categories
- Feed
- Sitemap
- Cookie Consent & Privacy Policy
- Integrations:
    - Disqus Comments
    - Google Analaytics
    - Formspree.io Contact
    - AddThis Integration
    - Pinterest
- Design Features:
    - Bootstrap v4.x
    - Font Awesome v5.x
- Layouts:
    - Default
    - Post
    - Page
    
### How to Use

If you aren't familiar with Jekyll yet, you should know that it is a static site generator. It will transform your plain text into static websites and blogs. No more databases, slow loading websites, risk of being hacked...just your content. And not only that, with Jekyll you get free hosting with GitHub Pages! If you are a beginner we recommend you start with [Jekyll's Docs](https://jekyllrb.com/docs/installation/). Now if you know how to use Jekyll, let's move on to using Affiliates template in Jekyll:

#### Plugins: 
    - jekyll-feed
    - jekyll-sitemap
    - jekyll-paginate
    - jekyll-seo-tag

#### Customize

Download or Fork *Pintereso for Jekyll*. 

- In your local project, open <code>_config.yml</code>. Set your <code>baseurl</code>, <code>name</code>, <code>email</code> etc:

        name: 'Pintereso'
        description: 'Jekyll Template for Bloggers & Photographers'
        logo: 'assets/images/logo.png'
        favicon: 'assets/images/logo.png'
        baseurl: '/template-pintereso-bootstrap-jekyll'
        avatar: 'assets/images/sal.jpg'
        disqus: 'demowebsite'
        email: 'wowthemesnet@gmail.com'
        
- Navigate to <code>includes</code> folder. From there you can edit/add:

    - footer copyright - <code>footer-copyright.html</code>
    - footer social menu - <code>footer-social.html</code>
    - menu header - <code>menu-header.html</code>
    - google analytics script - <code>tracking-header.html</code>
    - addthis script - <code>tracking-footer.html</code>

- Start blogging! Add your .md posts in <code>_posts</code>. If you download the template you will notice it already has a few as an example. 

YAML Post Example

        ---
        title:  "Affiliates Jekyll Theme"
        metadate: "hide"
        categories: [ Free, Jekyll, Themes ]
        image: "assets/images/affiliates.jpg"
        visit: "https://www.wowthemes.net/free-jekyll-template-affiliates/"
        ---
     
- Adding pages. Place your .md pages in <code>_pages</code>. Don't forget to set the permalink, see below.
    
YAML Page Example:

        ---
        title: "About"
        permalink: "/about.html"
        image: "/assets/images/screenshot.jpg"
        ---