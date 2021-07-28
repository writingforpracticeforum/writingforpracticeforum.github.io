---
title: About
---

# About

The Writing for Practice Forum is a peer-led training opportunity offered in collaboration between artists and researchers at the [MARs](http://m-a-r-s.online/) research centre at Goldsmiths College and at Sheffield Hallam University. It was initiated by Kate Pickering and Rowena Harris in 2018 and is now organised by Katarina Ranković and Julia Calver. The forum is a discursive space in which to gain valuable feedback on imaginative or experimental approaches with text-based material. It is open to all researchers within Goldsmiths and SHU, other CHASE institutions and beyond as either presenting writers or discussion participants and requires no prior knowledge or preparation, other than an interest in developing a deeper understanding of writing as part of practice-based research.

<br>

## Organisers

{% for author in site.authors %}

### [{{ author.name }}]( {{ author.url }} )
#### {{ author.institution }}
{{ author.excerpt | markdownify }}

{% endfor %}


