---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: Formal Methods for Software Engineering
      subtitle: ''
      image:
        filename: all.jpg
      text: |
        This website is a part of the Formal Methods for Software Engineering course at the Bauhaus-Universität Weimar. Currently, this website offers the following resources:
        - Visit the [Formal Methods Playground](https://play.formal-methods.net).
        - Go back more than a decade to 2011 and visit a [more colorful predecessor of this website](index2011.html).
        - Watch the videos of the [Formal Methods for Software Engineering lecture on YouTube](https://www.youtube.com/playlist?list=PLGyeoukah9Nbd1yRDj3ridE7PtcL91-5u).

  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: 
    design:
      view: compact
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title: 'Latest Lecture'
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1' 
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
