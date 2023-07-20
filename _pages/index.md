---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#8A9C9F"
  overlay_image: /images/header1.png
  # actions:
  #   - label: "<i class='fas fa-download'></i> Install now"
  #     url: "/docs/quick-start-guide/"
excerpt: >
  <p>Astoria's hobby farming journey in the Pacific Northwest</p><br>
  <small>On pygmy goats, aging pets, gardening, nature, and more </small> 

intro: 
  - excerpt: 'What Her Animals is About'

feature_row:
  - image_path: /images/flora.png
    alt: "flora"
    title: "Flora"
    excerpt: "What's in my veggie patch? Reforesting our land and PNW nature explorations."
    url: "/flora/"
    btn_class: "btn--primary"
    btn_label: "Read"
  - image_path: /images/fauna.png
    alt: "fauna"
    title: "Fauna"
    excerpt: "How do we best care for our aging livestock? Raising pygmy goats, rabbits, dogs, and cats."
    url: "/fauna/"
    btn_class: "btn--primary"
    btn_label: "Read"
  - image_path: /images/flavor.png
    alt: "flavor"
    title: "Flavor"
    excerpt: "What's cooking? My favorite recipes to cook and bake."
    url: "/flavor/"
    btn_class: "btn--primary"
    btn_label: "Read" 

feature_row2:
  - image_path: /images/flora.png
    alt: "flora"
    title: "My Garden Journal"
    excerpt: 'What is growing in my garden right now.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /images/fauna.png
    alt: "fauna"
    title: "Meet Astoria's Animals"
    excerpt: 'Who is currently living on the farm'
    url: "/her%20animals/2023/07/19/meet-her-animals.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "/_flora/garden-journal-1.md"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row2" type="right" %}


<!-- {% include feature_row id="feature_row4" type="center" %} -->