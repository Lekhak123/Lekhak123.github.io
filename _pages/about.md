---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /images/homepage.png
  actions:
    - label: "Download Resume"
      url: "/files/Resume.pdf"
excerpt: "I am a third-year undergraduate student at The University of Texas at Arlington, where I am pursuing a Bachelor of Science in Computer Science... I am a research assistant at the Arlington Computational Linguistics Lab (ACL2) advised by Dr. Kenny Zhu... My research is in the emerging field of animal language processing, where I work on creating novel datasets and building machine learning models for analyzing canine vocal communication."
intro:
  - excerpt: 'Please feel free to browse through my publications and blog posts to get a better understanding of my work.'
feature_row:
  - image_path: /images/blog-post-feature.png # Consider creating a relevant image
    alt: "Blog Posts"
    title: "Blog Posts"
    excerpt: "Stay up to date with my latest research and projects."
    url: "/posts/"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /images/image_6a395b.jpg
    alt: "A dog representing canine vocalization research"
    title: "Publications"
    excerpt: "A list of my publications and preprints on animal language processing."
    url: "/publications/"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /images/resume-feature.png # Consider creating a relevant image
    alt: "Resume"
    title: "Resume"
    excerpt: "A summary of my education, experience, and skills."
    url: "/files/Resume.pdf"
    btn_label: "Read More"
    btn_class: "btn--inverse"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}