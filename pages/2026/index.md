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
  - title: "Participants"
    url: /2026#participants
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

- image_path: /assets/images/2025/xxx.jpeg
      alt: "Katy DeCelles"
      excerpt: >
        **Katy DeCelles**<br>
        University of Toronto<br>
        [)
      bio: >

- image_path: /assets/images/2025/xxx.jpeg
      alt: "Maureen Eger"
      excerpt: >
        **Maureen Eger**<br>
        University of Southern California<br>
        [)
      bio: >
    
- image_path: /assets/images/2025/xxx.jpeg
      alt: "Alice Farmer"
      excerpt: >
        **Alice Farmer**<br>
        UNHCR<br>
        [)
      bio: >

- image_path: /assets/images/2025/xxx.jpeg
      alt: "Ann Owens"
      excerpt: >
        **Ann Owens**<br>
        UCLA<br>
        [)
      bio: >



---


# Overview

TBD.

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


# Participants
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
