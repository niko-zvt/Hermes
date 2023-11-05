---
layout: page
title: Lead-free Ferroelectrics
description: The project to create solid solutions and ceramics based on them for new environmentally friendly and sustainable nano- and microelectronics materials.
img: assets/img/projects/ferroelectrics/logo.jpg
importance: 90
year: 2014
category: work
publications: true
---

#### ⚡️ Introduction

Ferroelectric is a material with spontaneous polarization, the orientation of which can be changed by means of an external electric field. Such substances have ferroelectric hysteresis (Fig. 1), when the polarization of the material depends ambiguously on the external electric field.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/ferroelectrics/ferroelectric-hysteresis.png"
            title="Ferroelectric hysteresis loop"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 1. Ferroelectric hysteresis loop"
            zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/ferroelectrics/perovskite-structure-of-PZT.png"
            title="Perovskite structure of PZT"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 2. Perovskite structure of PZT"
            zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/ferroelectrics/pzt-phase-diagram.png"
            title="Phase diagram of PZT"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 3. Phase diagram of PZT"
            zoomable=true %}
    </div>
</div>

An important ferroelectric material for applications is [lead zirconate titanate (PZT)](https://en.wikipedia.org/wiki/Lead_zirconate_titanate) (Fig. 2), which is a [solid solution](https://en.wikipedia.org/wiki/Solid_solution) formed between ferroelectric lead titanate and anti-ferroelectric lead zirconate. PZT is a ceramic [perovskite](https://en.wikipedia.org/wiki/Perovskite_(structure)) material that shows a marked [piezoelectric effect](https://en.wikipedia.org/wiki/Piezoelectricity), meaning that the compound changes shape when an electric field is applied. Currently, a significant market share of devices based on piezoelectric materials is occupied by devices created using well-studied PZT ceramics.

Different compositions are used for different purposes of PZT (Fig. 3):
- for [memory cells (FRAM)](https://en.wikipedia.org/wiki/Ferroelectric_RAM) a composition closer to lead titanate is preferred {% cite Fujitsu_2010_FRAM_PZT %};
- for piezoelectric applications ([ultrasonic transducers](https://en.wikipedia.org/wiki/Ultrasonic_transducer) or [piezoelectric resonators](https://en.wikipedia.org/wiki/Crystal_oscillator)), a material closer to lead zirconate with [morphotropic phase boundaries (MPBs)](https://en.wikipedia.org/wiki/Piezoelectricity#:~:text=In%20general%2C%20the%20main%20fabrication%20challenge%20is%20creating%20the%20%22morphotropic%20phase%20boundaries%20(MPBs)%22%20that%20provide%20the%20materials%20with%20their%20stable%20piezoelectric%20properties%20without%20introducing%20the%20%22polymorphic%20phase%20boundaries%20(PPBs)%22%20that%20decrease%20the%20temperature%20stability%20of%20the%20material.%5B34%5D) is preferred {% cite Cohen_2008_Morphotropic_Phase_Boundaries %}.

#### ⚡️ Problems

The production of PZT is associated with the processing of lead-containing compounds, which causes significant damage to the environment and human health {% cite Bell_2018_Leadfree_Piezoelectrics %}. Based on this, many scientific centers are searching for new piezoelectric materials that would have properties superior to those of analogues used in practice (primarily PZT), and also did not contain lead in their composition and would be environmentally friendly materials.

The search for promising lead-free dielectric and piezoelectric materials is currently being carried out in several main directions.
1. Synthesis of new chemical compounds of polar dielectrics and study of their structure and properties.
2. Preparation and investigation of solid solutions based on previously known chemical compounds in the vicinity of the morphotropic phase boundary.
3. Development of methods for obtaining nanostructured bulk ceramic and film samples of dielectrics containing textures with a selected grain direction.
4. Identification of new crystalline phases near the morphotropic phase boundary in existing lead-free solid solutions (such, for example, as recently discovered monoclinic phases in PZT), the presence of which leads to a sharp increase in piezoelectric modules and the dielectric constant of the material.

At [Voronezh State Technical University (VorSTU)](https://cchgeu.ru/en/), such work is carried out by the [Department of Solid-State Physics](https://cchgeu.ru/en/education/institutes-and-faculties/faculty-of-radio-engineering-and-electronics/#:~:text=The%20Department%20of%20Solid%2Dstate%20Physics).

#### ⚡️ Results

During 2012-2016, I was a material scientist at [The Laboratory of Ferroelectrics](http://ferroics.narod.ru/index-2.htm) at VorSTU.
The areas of scientific interest of our group were: [ferroelectrics](https://en.wikipedia.org/wiki/Ferroelectricity),  [lead-free ferroelectric ceramics](https://link.springer.com/article/10.1557/s43578-021-00180-y), [ferroelastics](https://en.wikipedia.org/wiki/Ferroelasticity), [multiferroics](https://en.wikipedia.org/wiki/Multiferroics), [relaxation phenomena in solids](https://www.britannica.com/science/relaxation-phenomenon), [second-order phase transitions](https://en.wikipedia.org/wiki/Phase_transition#:~:text=8%5D%5B9%5D-,Second%2Dorder%20phase%20transitions,-are%20also%20called).

##### My goals:
- R&D projects on new lead-free ceramics
    - materials design of perovskite solid solutions;
        - selection of [stoichiometric coefficients](https://en.wikipedia.org/wiki/Stoichiometry) for new solid solutions (including [Aurivillius phase structures](https://en.wikipedia.org/wiki/Aurivillius_phases));
        - preparation of a mixture of raw materials for the synthesis of a given solid solution;
        - production of samples (including high-temperature sintering of ceramic compositions);
    - conducting a physical experiment in a wide range of temperatures and frequencies (from −195.75 to 700 °C, from 0.5 to 100 kHz);
    - analysis of the obtained results, statistical processing and their theoretical justification;
- Software development
    - utility for finding functional dependencies (Fig. 4);
    - utility for automated selection of stoichiometric coefficients for new chemical compounds;
    - SCADA-tool for data collection from scientific instruments - electrical capacitance, electrical resistance, the imaginary part of the permittivity, the tangent of the dielectric loss angle and the reactor temperature (Fig. 5);
- Hardware development
    - a high-temperature furnace with stable indicators of internal isothermal processes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/ferroelectrics/software-functions.png"
            title="Functional dependencies finder"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 4. Functional dependencies finder"
            zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/ferroelectrics/software-rcl-meter.png"
            title="RCL-meter"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 5. RCL-meter"
            zoomable=true %}
    </div>
</div>

##### Published scientific achievements:
- Crossover from an Ordinary Ferroelectric to a Relaxor in Sr<sub>(2+x)</sub>Bi<sub>(4-x)</sub>Ti<sub>(5-x)</sub>Nb<sub>x</sub>O<sub>18</sub> {% cite Zhivotenko_2016_Crossover_in_SrBiTiNbO %};
- Relaxor Behavior of Layered Perovskite Sr<sub>2.8</sub>Bi<sub>3.2</sub>Ti<sub>4.2</sub>Nb<sub>0.8</sub>O<sub>18</sub> {% cite Zhivotenko_2015_Relaxor_Behavior_of_Layered_Perovskite %};
- Crossover Normal Ferroelectric to Relaxor Ferroelectric in Sr<sub>(2+x)</sub>Bi<sub>(4-x)</sub>Ti<sub>(5-x)</sub>Nb<sub>x</sub>O<sub>18</sub> {% cite Zhivotenko_2015_Crossover_Normal_to_Relaxor_Ferroelectric %};
- Phase Transitions in a Family of New Ferroelectric Materials with a Layered Aurivillius Structure {% cite Zhivotenko_2015_Ferroelectric_Materials %};
- Preparation and dielectric properties of (x)BiLi<sub>0.5</sub>Sb<sub>0.5</sub>O<sub>3</sub> — (1−x)Na<sub>0.5</sub>Bi<sub>0.5</sub>TiO<sub>3</sub> solid solution {% cite Zhivotenko_2014_Preparation_and_properties_solid_solution %}.

#### ⚡️ Fun fact

In 2015, [The Second Russia-China Workshop on Dielectric and Ferroelectric Materials (RuChWDFM-2)](https://istina.msu.ru/conferences/12079077/) was held (Fig. 6), at which my colleagues and I presented one of the scientific papers. Can you find me?

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html 
            path="assets/img/projects/ferroelectrics/ru-cn-wdfm.jpg"
            title="The Second Russia-China Workshop on Dielectric and Ferroelectric Materials"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 6. The Second Russia-China Workshop on Dielectric and Ferroelectric Materials"
            zoomable=true %}
    </div>
</div>

#### ⚡️ See also
