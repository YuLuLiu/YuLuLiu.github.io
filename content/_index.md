---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hi!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
#
#
#
  - block: markdown
    content:
      title: News
      text: |-
        **I'll be attending <span style="color:red">CHI 2025 in Yokohama, Japan (April 26 - May 1)</span>, as the lead organizer of the [HEAL (Human-centered Evaluation and Auditing of Language models) workshop](https://heal-workshop.github.io/)!**
    design:
      columns: '2'
#
#    
# TODO: add "news" section: https://github.com/HugoBlox/hugo-blox-builder/issues/1677
#
  - block: collection
    id: publication
    content:
      title: Publications
      text: #|-
        #{{% callout note %}}
        #Quickly discover relevant content by [filtering publications](./publication/).
        #{{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
#
# Uncomment below once blog posts are up!
#
#  - block: collection
#    id: posts
#    content:
#      title: Blog Posts
#      subtitle: 'Coming soon, hopefully!'
#     text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#     # Choose a layout view
#      view: compact
#     columns: '2'
---
