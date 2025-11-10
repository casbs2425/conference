---
permalink: /2026
title: "Conference on Recent Developments in the Behavioral Sciences"
excerpt: XX XX, 2026 <br> Center for Advanced Study in the Behavioral Sciences (CASBS) <br> Stanford University (75 Alta Road, Stanford, CA 94305)
browser-title: "CASBS Conference"
masthead-title: "CASBS Conference"
masthead-subtitle: "@2026"
masthead-url: "/"
layout: splash
author_profile: false
header:
    overlay_color: "#000"
    overlay_filter: "0.7"
    overlay_image: /assets/images/bg.png
navigation:
  # - title: "CFP"
  #   url: /2025/call-for-papers
  - title: "Program"
    url: /2026#program
  # - title: "Keynotes"
  #   url: /2025#keynotes
  # - title: "Panelists"
  #   url: /2025#panelists
  # - title: "Accepted Papers"
  #   url: /glb2022#accepted-papers
  - title: "Participate"
    url: /2026#participate
  # - title: "Relevant Workshops"
  #  url: /relevant

keynotes: 
- image_path: /assets/images/2025/xxx.jpeg
  alt: ""
  excerpt: >
    **<big></big>**<br>
    Institute<br>
    [https://xxx.com/](https://xxx.com/)<br><br>
    **xxx**
  abstract: >
    xxx
  bio: >
    xxx
  

panelists:

participants:
    - image_path: /assets/images/2025/jackson_sq.jpg
      alt: "Katy DeCelles"
      excerpt: >
        **Katy DeCelles**<br>
        University of Toronto<br>
        [)
        bio: >

    - image_path: /assets/images/2025/mei_sq.jpeg
      alt: "Maureen Eger"
      excerpt: >
        **Maureen Eger**<br>
        University of Southern California<br>
        [)
      bio: >
    

    - image_path: /assets/images/2025/wang_sq.jpg
      alt: "Alice Farmer"
      excerpt: >
        **Alice Farmer**<br>
        UNHCR<br>
        [)
      bio: >

    - image_path: /assets/images/2025/xie_sq.jpeg
      alt: "Ann Owens"
      excerpt: >
        **Ann Owens**<br>
        UCLA<br>
        [)
      bio: >


        

---


# Overview

The field of AI Behavioral Science is rapidly emerging at the intersection of artificial intelligence and behavioral science research. As AI systems increasingly shape human experiences— ranging from influencing decision-making on social media to automating tasks in the labor market— behavioral scientists and AI researchers face the critical challenge of understanding and guiding these interactions for positive outcomes. Central to this endeavor is the study of behaviors exhibited by sophisticated AI models, trained on vast human datasets and iteratively refined through human feedback.

This workshop will explore four pivotal questions:

1. How can AI serve as a transformative tool for behavioral science research?
2. How can behavioral science principles enhance our ability to evaluate and interpret AI behaviors?
3. How can understanding AI behaviors provide deeper insights into human decision-making processes?
4. How can we envision the future of human-AI collaboration to maximize benefits for individuals, organizations, and society?

This workshop aims to catalyze discussions and collaborations that will shape the future of this promising field by bringing together thought leaders and practitioners from across disciplines.


# Program

| Time (PDT) | Agenda |
| ----------------- | ------------ |
| **09:00-09:30**    | **Opening Remarks** by XX | 
| **09:30-10:45**    | **Topic 1: XX** <br>  |
| **10:45-12:00**    | **Topic 2: XX** <br>  |
| **12:00-13:30**    | **Lunch Break and Discussion** |
| **13:30-15:00**    | **Topic 3: XX** <br>  |
| **15:00-16:30**    | **Topic 4: XX** <br>  |
| **16:30-17:00**    | **Summary and Closing Remarks** by XX |

Please note that this preliminary program is subject to change.

<!-- # Keynotes

To be announced. -->

<!-- {% include feature_row id="keynotes" type="left" %} -->
<!-- {% include feature_row id="keynotes"%} -->

<!-- # Panelists

To be announced. -->

<!-- {% include feature_row id="panelists" %} -->

<!-- # Accepted Papers
<ul>
{% for pubitem in site.data.papers2023 %}
    <li> {{ pubitem.title | markdownify | remove: '<p>' | remove: '</p>' | strip }} <br>
    <div class="small">
    <i> {{ pubitem.authors | markdownify | remove: '<p>' | remove: '</p>' | strip }} </i> 
    </div>
    {% if pubitem.abstract %} 
    <a class="btn btn--small btn--info collapsible">Abstract</a> 
    <div class="btn-content small">
        <b>Abstract</b>: {{ pubitem.abstract }}
    </div>
    {% endif %}
    {% if pubitem.PDF %} <a href="{{ pubitem.PDF }}" class="btn btn--small btn--info">PDF</a>{% endif %}
    {% if pubitem.code %} <a href="{{ pubitem.code }}" class="btn btn--small btn--info">
    {% if pubitem.new_dataset %} Code & Datasets {% else %} Code {% endif %} </a>{% endif %}
    </li>
{% endfor %}
</ul> -->


# Participate
Please contact us at casbs2025 at gmail dot com if you have any questions.

{% include feature_row id="participants"%}

<!-- # Program Committee

To be announced. -->

<!-- <div class="small row-two-columns">
<div class="column-half">
<ul>
{% for people in site.data.pc-members2023 limit:11 %}
<li>{{ people | markdownify | remove: '<p>' | remove: '</p>' | strip }} </li>
{% endfor %}
</ul>
</div>
<div class="column-half">
<ul>
{% for people in site.data.pc-members2023 offset:11 %}
<li>{{ people | markdownify | remove: '<p>' | remove: '</p>' | strip }} </li>
{% endfor %}
</ul>
</div>
</div> -->

<script>
    var coll = document.getElementsByClassName("collapsible");
    var i;

    for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
        this.classList.toggle("active");
        var content = this.nextElementSibling;
        if (content.style.display === "block") {
        content.style.display = "none";
        } else {
        content.style.display = "block";
        }
    });
    }
</script>
