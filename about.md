---
title: About
---

# The Writing for Practice Forum

The Writing for Practice Forum is a peer-led training opportunity offered in collaboration between artists and researchers at Goldsmiths College and Sheffield Hallam University. It was initiated by Kate Pickering and Rowena Harris in 2018 and is now organised by Katarina Rankovic (GC) and Julia Calver (SHU). The forum is a discursive space in which to gain valuable feedback on imaginative or experimental approaches with text-based material. It is open to all researchers within Goldsmiths and SHU, other CHASE institutions and beyond as either presenting writers or discussion participants and requires no prior knowledge or preparation, other than an interest in developing a deeper understanding of writing as part of practice-based research.  



## Organisers

{% for author in site.authors %}

### [{{ author.name }}]("{{ author.url }}")
{{ author.content | markdownify }}

{% endfor %}


