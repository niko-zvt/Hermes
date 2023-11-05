---
layout: page
title: Millimetron
description: Millimetron space observatory (Spektr-M) is a project of Astro Space Center of Lebedev Physical Institute, Russian Academy of Sciences (ASC LPI).
img: assets/img/projects/millimetron/logo.jpg
importance: 70
year: 2016
category: work
---

#### ⚡️ Introduction

[Millimetron Space Observatory ("Spektr-M")](https://millimetron.ru/en/) (Fig. 1) is a project of [Astro Space Center](http://sites.lebedev.ru/en/asc/2061.html) of [Lebedev Physical Institute, Russian Academy of Sciences (ASC LPI)](http:/old.lebedev.ru/en/). It will be a 10-meter deployable and cooled space telescope designed to study various objects in the Universe at millimeter and infrared wavelengths from 0.07 to 10 mm. The observatory has two operational modes: as single-dish and as the space VLBI station in a Space-Earth interferometer. The first mode will have the best sensitivity to study the weakest sources of the Universe. The second mode together with ground telescopes will provide high angular resolution up to 10<sup>−8</sup> - 10<sup>−9</sup> arcseconds to study the structure of the most compact objects in the Universe - supermassive black holes (Fig. 2).

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html
            path="assets/img/projects/millimetron/mso.png"
            title="Concept of Millimetron Space Observatory, https://aboutspacejornal.net"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 1. Concept of Millimetron Space Observatory"
            zoomable=true %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html
            path="assets/img/projects/millimetron/supermassive-black-hole.png"
            title="The first direct image of a supermassive black hole. Event Horizon Telescope - https://www.eso.org/public/images/eso1907a/"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 2. The first direct image of a supermassive black hole"
            zoomable=true %}
    </div>
</div>

 Deep cooling of the telescope mirror system and scientific payload enables the high sensitivity (Fig. 3). While, high angular resolution is provided by the orbit configuration. Initially the observatory will be located near the Lagrange point L2 at a distance of 1.5 million kilometers from Earth in the anti-solar direction and in the second phase of the mission will operate in a near-Earth high elliptical orbit (HEO). Scientific program of Millimetron space observatory is aimed to solve a set of the most important and breakthrough scientific problems in the field of modern astrophysics and cosmology, including amongst others detailed studies of black hole shadows, search for wormholes, water trail in the Galaxy, CMB spectral distortions. The Millimetron Space Observatory project is approved by Russian Space Agency and included in the Russian Federal Space Program for 2016-2025 years.

#### ⚡️ VLBI Instruments

Quote from the official website of the Millimetron project:
<blockquote>
    Millimetron Space-Ground VLBI receivers will be used for <a href="https://en.wikipedia.org/wiki/Very-long-baseline_interferometry">Very Long Baseline Interferometry</a> observations between Millimetron and ground stations such as <a href="https://www.almaobservatory.org/en/home/">ALMA</a>, <a href="https://www.iram-institute.org/EN/content-page-235-3-235-0-0-0.html">NOEMA</a>, <a href="https://eventhorizontelescope.org/">EHT network</a>, <a href="https://radio.kasi.re.kr/kvn/main_kvn.php">KVN network</a> and so on. Observations will utilize both <a href="https://en.wikipedia.org/wiki/Lagrange_point">Lagrange L2 point</a> as well as <a href="https://en.wikipedia.org/wiki/Low_Earth_orbit">elliptical near-Earth orbit</a>. For efficient operations, VLBI instruments will be split into frequency bands, matching those of ALMA and other ground based stations. For multi-frequency operations capability, all VLBI bands will be quasi-optically combined using the set of dichroic filters and will receive signal from the same direction on the sky.
</blockquote>

["Contact-Technologia" NPP, LLC](http://contact-npp.ru/?content=mainpage.en) has developed and manufactured the entire hardware complex of technical means for the ground tracking station of the international radio astronomy project [Radioastron ("Spektr-R")](http://www.asc.rssi.ru/radioastron/index.html). Using successful experience, we started working on one of the most important parts of the scientific equipment of the [Millimetron project](https://millimetron.ru/en/participants#:~:text=Information%20Satellite%20Systems-,Contact%2DTechnologia,-Institute%20of%20Radio). The main device of which is an [Analog-to-Digital Converters and Formatters ("Formator-P")](http://contact-npp.ru/?content=millimetron.en). The device "Formator-P" is intended for scientific data acquisition and buffering, formatting scientific data according to predefined frame structure, and transferring resulting high-speed digital data stream to downlink transmitter device (Fig. 4).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
            path="assets/img/projects/millimetron/space-observatory.png"
            title="Millimetron Space Observatory working configuration, https://millimetron.ru"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 3. Millimetron Space Observatory working configuration"
            zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html
            path="assets/img/projects/millimetron/transmitter.png"
            title="Block diagram of the Millimetron transmitter, https://millimetron.ru"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 4. Block diagram of the Millimetron transmitter"
            zoomable=true %}
    </div>
</div>

Device "Formator-P" acquires different types of data from various sources:
- along signals from [VLBI receivers](https://millimetron.ru/en/general/instruments#:~:text=the%20IF%20band.-,Main%20parameters%20of%20the%20Space%2DVLBI%20receiver%20bands%20are%20shown%20in,Dedicated%20SIS%20receiver,-*%20Receiver%20bands%20in), simultaneously for upper and lower sideband in two polarizations;
- digital data from [high resolutiion spectrometer](https://millimetron.ru/en/general/instruments#:~:text=ground%20data%20link.-,High%20Resolution%20Spectrometr,-High%20resolution%20spectrometer) through SpaceWire channel;
- digital data from [high frequency, medium resolution spectrometer](https://millimetron.ru/en/general/instruments#:~:text=University%20of%20Rome.-,Short%20Wave%20Matrix%20Spectrometer,-Short%20wave%20Matrix) through SpaceWire channel;
- digital data from [low frequency, medium resolution spectrometer](https://millimetron.ru/en/general/instruments#:~:text=Space%20Research%20(SRON).-,Long%20Wave%20Matrix%20Spectrometer,-The%20main%20objective) through SpaceWire channel;
- digital [scientific telemetry data](https://millimetron.ru/en/ground-segment/ground-tracking-stations#:~:text=onboard%20high%20ratio%20data%20transmission%20radio%20complex%20(VIRK%2DM)) through command/response data bus MIL-STD-1553B.

Digitized data from VLBI receivers get temporary stored in Flash-based nonvolatile memory - to accommodate very high-speed VLBI data rate to downlink data rate. Digital data, received through SpaceWire channel and MIL-STD-1553B data bus, combined with VLBI data, stored in nonvolateble memory, get coded with error-correcting codes, and then formatted to scientific data frame structure, for futher transmitting through two independent frequency channels to Earth stations.

#### ⚡️ Results

During the project, high-tech equipment and scientific software were designed, manufactured and tested. The device "Formator-P" has been created, which has a number of unique technical features (Tab. 1).

<div class="caption-table">
    Tab. 1. Technical characteristics of the onboard converter and signal shaper "Formator-P".
</div>

| Parameter                                                                                                      | Value            |
| -------------------------------------------------------------------------------------------------------------- | ---------------- |
| Size of Flash-based nonvolatile memory for VLBI data                                                           | 10000 Gbytes     |
| Number of reserved analog inputs for VLBI signals                                                              | 4                |
| Bandwidth for VLBI signals                                                                                     | 5 - 975 MHz      |
| Sampling frequency for VLBI signals                                                                            | 2000 MHz         |
| Number of bits per sample for VLBI signals ADC                                                                 | 8                |
| Number of bits per sample for output VLBI signals                                                              | 1 or 2           |
| Maximum VLBI data rate, coming to nonvolatile memory                                                           | 16 Gbps          |
| Number of reserved SpaceWire channels for receiving digital scientific data&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| 3                |
| Maximum data rate for SpaceWire channel                                                                        | 25 Mbps          |
| Number of reserved digital outputs to downlink transmitter device                                              | 2                |
| Data rate for one digital output to downlink transmitter device                                                | 600 Mbps         |
| Maximum data rate for reserved MIL-STD-1553B                                                                   | 500 Kbps         |
| Supply voltage                                                                                                 | +- 27 V          |
| Power consumption (operating mode dependent)                                                                   | 20 - 67 W        |
| Dimensions                                                                                                     | 330x310x81 mm    |

<div class="caption-table">
   
</div>

#### ⚡️ Fun fact

I had the honor of placing the company logo at the opening of the new office (Fig. 5).

As a young student, I sit on the right and create a finite element model of the ''Formator-P'' device for analyzing heat losses and generating heat power (Fig. 6).

<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html
            path="assets/img/projects/millimetron/contact-tech-01.png"
            title="''Contact-Technologia'' NPP, LLC. http://contact-npp.ru/?content=mission.en"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 5. Logo of ''Contact-Technologia'' NPP, LLC"
            zoomable=true %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html
            path="assets/img/projects/millimetron/contact-tech-02.png"
            title="''Contact-Technologia'' NPP, LLC. http://contact-npp.ru/?content=mission.en"
            class="img-fluid rounded z-depth-1"
            caption-small="Fig. 6. My colleague and I are working on the Formator-P device in 2016"
            zoomable=true %}
    </div>
</div>