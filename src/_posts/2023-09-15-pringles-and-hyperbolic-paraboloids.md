---
layout: post
title:  From Pringles® to Space - Unveiling the Mysteries of Hyperbolic Paraboloids and Magic Linear Structures
date:   2023-09-15 18:00:00
description: It turns out that this iconic snack isn't just a happy accident – it's actually a product of mathematics, specifically a second-order surface type known as the hyperbolic paraboloid, which happens to resemble a "saddle". So, let's saddle up and explore the mathematical magic behind Pringles®!
tags: math geometry composites structures
categories: science
publications: true
---

Recently, I stumbled upon an intriguing post by Alex Wang that sheds light on the fascinating origin of Pringles®' shape.

<center>
{% include figure.html
path="/assets/img/blog/2023/pringles-and-hyperbolic-paraboloids/pringles.jpg"
width="50%"
class="img-fluid rounded z-depth-1"
zoomable=true %}
</center>

$$ z = {x^2 \over a^2} - {y^2 \over b^2}, {x^2 \over a^2} + {y^2 \over b^2} < 1$$

It turns out that this iconic snack isn't just a happy accident – it's actually a product of mathematics, specifically a second-order surface type known as the hyperbolic paraboloid, which happens to resemble a "saddle". So, let's saddle up and explore the mathematical magic behind Pringles®!

The original [post by Alex](https://www.linkedin.com/embed/feed/update/urn:li:share:7102229703553384448):

<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7102229703553384448" height="500" width="100%" frameborder="0" allowfullscreen="" title="Alex's post"></iframe>

<br/>

#### ⚡️ Let's add a bit more scientific boredom!

Aside from being a mouthful to say, the hyperbolic paraboloid is an incredible geometric shape, and it happens to be a ruled surface. In simpler terms, it's a surface created by the movement of a straight line (Fig. 1). Here we have points on two circles, connected with straight lines. Rotating the lower circle, we get hyperboloid of one sheet and then a cone. Parameter $$t$$ is the angle by which we rotate the lower circle. Such models can be seen in some museums. Equation is: 

$$ x^{2}+y^{2}=1+(z^{2}-1)\sin ^{2}{t \over 2}, t = 0..2\pi.$$

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="https://upload.wikimedia.org/wikipedia/commons/5/59/Cylinder_-_hyperboloid_-_cone.gif"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 1. Cylinder -> Hyperboloid -> Cone"
        zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="/assets/img/blog/2023/pringles-and-hyperbolic-paraboloids/helicoid.jpg"
        width="400"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 2. Helicoid"
        zoomable=true %}
    </div>
</div>

Ruled surfaces include cylinders, hyperboloids, cones, etc (Fig. 2). But this isn't just about geeking out over geometry; it's about Architectural and Engineering dynamite!

#### ⚡️ Architectural dynamite

Parabolic and linear surfaces have found a unique application in architecture, thanks to their ability to create efficient structures with impressive architectural aesthetics {% cite Architecture_Lauriola_MSc_Thesis %}. Parabolic curves can provide rational or optimal load distribution and perfect utilization of natural light, while linear surfaces add elements of geometric complexity and visual depth to modern buildings, transforming them into true architectural masterpieces.

Take a look at these masterpieces:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
        path="https://www.wmf.org/sites/default/files/styles/project_gallery_full_size/public/projects/gallery/RUS%20Shukhov_JPEG_img-03.jpg?itok=EVqdLMby"
        title="Shukhov Tower in Moscow, 1929. Courtesy of World Monuments Fund"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 3. Shukhov Tower<br>(Moscow, Russia)"
        zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="https://upload.wikimedia.org/wikipedia/commons/d/d6/Canton_Tower_20220626_%28cropped%29.jpg"
        title="Canton Tower (Guangzhou, China). Tim Wu, CC BY-SA 4.0 (Wikipedia)"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 4. Canton Tower<br>(Guangzhou, China)"
        zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="https://welcomekansai.com/wp-content/uploads/2017/12/kobe-tower5-768x512.jpg"
        title="Kobe Port Tower. © 2023 Welcome Kansai"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 5. Kobe Port Tower<br>(Kobe, Japan)"
        zoomable=true %}
    </div>
</div>
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="https://parknaukitorus.pl/wp-content/gallery/wieza-cisnien-dzis/DJI_0022.jpg" 
        title="Ciechanow Water Tower. Courtesy of Torus Science Park"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 6. Double ruled water tower with toroidal tank<br>(Ciechanow, Poland)"
        zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="https://upload.wikimedia.org/wikipedia/commons/5/57/Sagrada_Familia_8-12-21_%281%29.jpg"
        title="Sagrada Familia Church. Canaan, CC BY-SA 4.0 (Wikipedia)"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 7. Sagrada Familia Church<br>(Barcelona, Spain)"
        zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="https://upload.wikimedia.org/wikipedia/commons/a/a3/W-wa_Ochota_PKP-WKD.jpg"
        title="Warszawa Ochota railway station. Panek, CC BY-SA 4.0 (Wikipedia)"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 8. A hyperbolic paraboloid roof of Warszawa Ochota railway station<br>(Warsaw, Poland)"
        zoomable=true %}
    </div>
</div>

But wait, there's more! 

#### ⚡️ Engineering dynamite

This same principle underpins the structural designs of space rockets. 

During the space race, both the USSR and the USA were pioneering various technologies for manufacturing grid-like structural components for rockets and spacecraft. For instance, McDonnell Douglas (now part of Boeing) patented [isogrid structures](https://en.wikipedia.org/wiki/Isogrid) (Fig. 9 - 10). See patent US4012549A {% cite Isogrid_Lattice_Structures %}. Orthogrid and angle-grid structures also came into existence (Fig. 11). These designs have been and continue to be utilized in rockets like the "Atlas", "Delta" and even in the "Crew Dragon" spaceship.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="https://upload.wikimedia.org/wikipedia/commons/e/ef/Orion-Delta_IV_adapter_isogrid.jpg"
        title="Isogrid adapter for Orion-Delta IV. NASA, Public domain, via Wikimedia Commons"
        width="100%"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 9. Isogrid adapter for Orion-Delta IV (NASA)"
        zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="https://upload.wikimedia.org/wikipedia/commons/a/a3/CST-100_pressure_vessel.jpg"
        title="CST-100 pressure vessel. Kim Shiflett, Public domain, via Wikimedia Commons"
        width="100%"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 10. Pressure vessel for ''Crew Space Transportation'' spacecraft (CST-100)"
        zoomable=true %}
    </div>
</div>

<center>
{% include figure.html
path="/assets/img/blog/2023/pringles-and-hyperbolic-paraboloids/grids.jpg"
title="Different types of grid structures"
width="100%"
class="img-fluid rounded z-depth-1"
caption-small="Fig. 11. Different types of grid structures"
zoomable=true %}
</center>

However, in my view, significant breakthroughs occurred in the 1980's at the [CRISM](https://www.tsniism.ru/en/index.htm) institute (USSR/Russia). There, anisogrid structures were developed and patented – high-strength composite structures created by winding continuous carbon fibers (CFRP). Such structures serve as the primary load-bearing components in the payload adapters of modern "Proton" class rockets (Fig. 12). They exhibit tremendous weight efficiency and stability {% cite Anisogrid_Composite_Lattice_Structures %}.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
        path="/assets/img/blog/2023/pringles-and-hyperbolic-paraboloids/anisogrids.jpg"
        title="Different types of anisogrid payload adapters in the form of a ruled surfaces"
        width="100%"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 12. Different types of anisogrid payload adapters in the form of a ruled surfaces"
        zoomable=true %}
    </div>
</div>

Just search for ["anisogrid structure"](https://www.google.com/search?q=anisogrid+structure) and prepare to be amazed!

#### ⚡️ Accessories

And if you want a ruled surface as a personal accessory, just use a Vietnamese hat made of leaves known as ["Nón lá"](https://en.wikipedia.org/wiki/N%C3%B3n_l%C3%A1) (Fig. 13).

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <center>
        {% include figure.html
        path="https://upload.wikimedia.org/wikipedia/commons/1/18/Ch%E1%BB%A3_S%E1%BA%A7m_S%C6%A1n_%2C_n%C4%83m_1905..jpg"
        title="Nón lá at Sầm Sơn market in 1905. Ratmanhme282020, CC BY-SA 4.0, via Wikimedia Commons"
        width="50%"
        class="img-fluid rounded z-depth-1"
        caption-small="Fig. 13. Nón lá at Sầm Sơn market in 1905"
        zoomable=true %}
        </center>
    </div>
</div>

#### ⚡️ See also