---
layout: page
title: C/C Composites
description: The project was aimed at studying micro-, meso- and microstructure characteristics of an axially braided C/C composites.
img: assets/img/projects/c-c-composites/logo.jpg
importance: 60
year: 2018
category: work
publications: true
---

#### ⚡️ Introduction

[Carbon-carbon (C/C) composites](https://en.wikipedia.org/wiki/Reinforced_carbon%E2%80%93carbon) are materials based on a carbon matrix and a braided frame of a 3-, 4- or 5-dimensional carbon fiber structure (Fig. 1). Designed for use in products of high-temperature, nuclear, and space-rocket technology. They can also be used as [friction carbon ceramics in the braking systems of airplanes](https://www.boeing.com/commercial/aeromagazine/articles/qtr_03_09/article_05_1.html) and trains.

The main value of C/C composites and [C/SiC ceramics based on silicon carbide](https://en.wikipedia.org/wiki/Reinforced_carbon%E2%80%93carbon#:~:text=Carbon%20fibre%2Dreinforced%20silicon%20carbide%20(C/SiC)) is that they allow the manufacture of structural elements of special equipment operating under conditions of exposure to extreme temperatures, high-speed gas flows, liquid metals, aggressive environments, mechanical and erosive wear. The most common examples are the manufacture of uncooled liquid [rocket engine nozzles](https://en.wikipedia.org/wiki/Rocket_engine_nozzle), low-thrust liquid fuel combustion chambers, parts of aviation gas turbine engines and industrial gas turbine units (Fig. 2).

This composite was developed for the reentry vehicles of intercontinental ballistic missiles, and is most widely known as the material for the nose cone and wing leading edges of the [Space Shuttle orbiter](https://en.wikipedia.org/wiki/Space_Shuttle) and [Buran spaceplane](https://en.wikipedia.org/wiki/Buran_(spacecraft)), however, the [C/C Buran heat tiles](https://www.buran.ru/htm/tersaf4.htm) have an antioxidant molybdenum disilicide coating (Fig. 3).

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/c-c-composites/c-c-composite.png"
            title="Body-reinforced C-C composite. NII ''Grafit'', Rosatom. https://strana-rosatom.ru/2020/09/28/uglerod-vezdesushhij-komu-i-kak-niigra/"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 1. Body-reinforced C-C composite.<br>NII ''Grafit'', Rosatom"
            zoomable=true %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/c-c-composites/dmt-mai-202.png"
            title="Combustion chamber of liquid rocket engine made of C-SiC ceramic composite. JSC ''Kompozit'', Roscosmos. https://www.kompozit-mv.ru/en/nonmetallic-materials/112-oxidation-resistant-c-sic-composite.html"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 2. Combustion chamber of liquid rocket engine made of C-SiC ceramic composite.<br>JSC ''Kompozit'', Roscosmos"
            zoomable=true %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
            path="assets/img/projects/c-c-composites/buran.png"
            title="Buran, http://www.buran.ru/"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 3. Buran spacecraft"
            zoomable=true %}
    </div>
</div>    

#### ⚡️ Problems

The prediction of the characteristics of composites can be carried out in two ways {% cite Chunguang_Wang_CC_Composites %}:
- direct experiment with a set of a large number of statistical data;
- computer modeling of the structure with further analysis by methods of mathematical physics and computational algorithms.

As a result of the complex spatial structure of the material (Fig. 4) and a wide range of operating temperatures, the prediction of various characteristics by direct experimental methods can be difficult or impossible. Therefore, computational methods such as the [Finite Element Method](https://en.wikipedia.org/wiki/Finite_element_method) are often used. And the main tool for predicting effective characteristics is the method of constructing a [Representative Volume Element](https://en.wikipedia.org/wiki/Representative_elementary_volume) {% cite Magnitsky_2020_Failure_criterion_C_C_composite %}. That is why [microscopic data](https://en.wikipedia.org/wiki/Microscopic_scale) (Fig. 5) are the basis for predicting the properties of materials and qualitative comparison of macro-characteristics.

In order to study the [microstructure](https://en.wikipedia.org/wiki/Microstructure) characteristics of a carbon-carbon composite with volumetric reinforcement, comprehensive observations and studies of [mesoscopic](https://en.wikipedia.org/wiki/Mesoscopic_physics) and microstructural characteristics are carried out. [Mechanical](https://www.kompozit-mv.ru/en/material-testing/142-laboratory-investigations-of-the-physico-mechanical-properties-of-materials-and-coatings.html) and [thermal](https://www.kompozit-mv.ru/en/material-testing/143-laboratory-studies-of-thermophysical-properties-of-materials-and-coatings.html) tests are carried out in a wide temperature range - from cryogenic (120 K) to thousands of degrees (3000 K). [Scanning optical](https://en.wikipedia.org/wiki/Near-field_scanning_optical_microscope) and [electron microscopy](https://en.wikipedia.org/wiki/Transmission_electron_microscopy), [micro-CT](https://en.wikipedia.org/wiki/X-ray_microtomography) are also used to obtain the characteristics of the microstructure and the rules for the distribution of C/C composite material. In the future, the effective characteristics of the composite are determined, followed by validation with field experiments.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/c-c-composites/fibers.png"
            title="Complex spatial structure of 3D, 4D, and 5D C/C composites"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 4. Complex spatial structure of 3D, 4D, and 5D C/C composites"
            zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/c-c-composites/microstructure.png"
            title="Microstructure of C/C composite"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 5. Microstructure of C/C composite"
            zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/c-c-composites/c-c-parts.png"
            title="Examples of workpiece and parts made of C/C composites"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 6. Examples of workpiece and parts made of C/C composites"
            zoomable=true %}
    </div>
</div>

#### ⚡️ Results

In the course of the project, were created:
- physical model of the material;
- geometric model of a representative unit (RVE unit).

A also reliably determined the characteristics of this type of material with deviations of no more than 5%. The characteristics of the microstructure show that a C/C composite with volumetric reinforcement is a heterogeneous material with cracks and pores of various sizes, which is a 3-dimensional and 4-directional body of carbon fibers as a reinforcing phase and pitch carbon as a binding matrix (Fig. 6).

#### ⚡️ See also
