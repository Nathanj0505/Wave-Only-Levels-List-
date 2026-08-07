---
layout: page
title: Main List
---

# Main List

{% assign challenges = site.data.extended %}
{% for l in levels %}
## #{{ l.rank }} — {{ l.name }}

- **ID:** {{ c.id }}
- **Creator:** {{ c.creator }}
- **Verifier:** {{ c.verifier }}
- **FPS:** {{ c.fps }}
- **Video:** [Link]({{ c.video }})
- **Notes:** {{ c.notes }}

---
{% endfor %}
