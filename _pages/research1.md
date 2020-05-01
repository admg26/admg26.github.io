---
permalink: /research/
title: "Research"
---
<style>
.csl-block {
    font-size: 16px;
}
.csl-title, .csl-author, .csl-event, .csl-editor, .csl-venue {
    display: block;
    position: relative;
    font-size: 16px;
}

.csl-title b {
    font-weight: 600;
}

.csl-content {
    display: inline-block;
    vertical-align: top;
    padding-left: 20px;
}

.no-bullet {
   list-style-type: none;
}

</style>


{% assign bib_file = 'publications.bib' %}
{% bibliography -f {{bib_file}}  %}

