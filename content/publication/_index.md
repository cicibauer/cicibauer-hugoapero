---
title: A list of Publications
description: ""
author: "Cici Bauer"
show_post_thumbnail: true
show_author_byline: true
show_post_date: false
# for listing page layout
layout: list #list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: A Sidebar for Your Projects
  description: |
    Projects can be anything!
    Check out the _index.md file in the /project folder 
    to edit this content.
  author: "The R Markdown Team @RStudio"
  text_link_label: ""
  text_link_url: ""
  show_sidebar_adunit: false # show ad container

# set up common front matter for all individual pages inside project/
cascade:    
  show_author_byline: true
  show_post_date: true
  show_disqus_comments: false # see disqusShortname in site config
  # for single-sidebar layout only
  sidebar:
    text_link_label: View all projects
    text_link_url: /project/
    show_sidebar_adunit: false # show ad container

# add new section using level 3 trick to use project template for publications (experimenting)    
type: project
cascade:
  type: project    
---

** No content for the project index. This file provides front matter for the blog including the layout and boolean options. **
