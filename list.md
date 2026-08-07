---
layout: page
title: Main List
---

# Main List

{% assign challenges = site.data.list %}
{% for c in challenges %}
## #{{ c.rank }} — {{ c.name }}

- **ID:** {{ c.id }}
- **Creator:** {{ c.creator }}
- **Verifier:** {{ c.verifier }}
- **FPS:** {{ c.fps }}
- **Video:** [Link]({{ c.video }})
- **Notes:** {{ c.notes }}

---
{% endfor %}
