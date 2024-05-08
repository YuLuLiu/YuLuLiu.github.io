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
#  - block: markdown
#    content:
#     title: News
#      text: |-
#        - [DATE1] News item 1 Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum
#        - [DATE2] News item 2 Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum
#    design:
#      columns: '2'

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
#
#
#
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        The best way to reach me is via email or Twitter DM: 
      # Contact (add or remove contact options as necessary)
      email: yu.l.liu [at] mail [dot] mcgill [ccTLD for Canada]
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: twitter.com/liu_yu_lu
          link: 'https://twitter.com/liu_yu_lu'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
