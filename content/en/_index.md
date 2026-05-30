---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      username: me
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: collection
    id: news
    content:
      title: News
      page_type: blog
      count: 10
      order: desc
    design:
      view: card
  - block: resume-experience
    id: experience
    content:
      username: me
      title: Experience
    design:
      date_format: 'January 2006'
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills
      username: me
  - block: resume-awards
    id: awards
    content:
      title: Awards
      username: me
  - block: resume-languages
    id: languages
    content:
      title: Languages
      username: me
---
