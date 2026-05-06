---
layout: page
title: Research
---

<center>
<i class="fa fa-android fa-5x" style="color: #000000;"></i>&nbsp;&nbsp;&nbsp; 
<i class="fa fa-mobile fa-5x" style="color: #000000;"></i>&nbsp;&nbsp;&nbsp; 
<i class="fa fa-desktop fa-5x" style="color: #000000;"></i>&nbsp;&nbsp;&nbsp; 
<i class="fa fa-eye fa-5x" style="color: #000000;"></i>&nbsp;&nbsp;&nbsp; 
<i class="fa fa-lock fa-5x" style="color: #000000;"></i>
</center>

<!-- ![research photo](/assets/images/research.jpg){:style="display:block; margin-left:auto; margin-right:auto"} -->
<!-- : width="300" -->

# Research Interests 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;My research interests lie in hardware/systems security with a side on computer systems. Recently, my work has been focused on side-channel vulnerabilities inherent to graphics stacks and discovering new microarchitectural side-channel attack techniques. I'm currently advised by [Professor Chris Fletcher](https://cwfletcher.github.io/) at the University of California, Berkeley. 

# Publications
<ul>
{% for pub in site.data.publications %}{% include publication.html pub=pub %}
{% endfor %}
</ul>

# Theses
<ul>
{% for thesis in site.data.theses %}{% include publication.html pub=thesis %}
{% endfor %}
</ul>
