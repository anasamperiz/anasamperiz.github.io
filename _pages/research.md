---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

<h3>PhD thesis - From watershed to reef: reconstructing the history of land use change and coral reef health in Fiji</h3> 

My current project focuses on disentangling how climate change and land use are impacting the growth of massive reef-building coral (<i>Porites</i>) in Fiji, and how abrupt terrestrial discharges into coastal ecosystems are linked to coral degradation.

Coral reefs are one of the most vulnerable ecosystems on Earth due to their high sensitivity to environmental changes in their habitats. Reef-building corals show limited tolerance to changes in light availability, climate and current patterns, sedimentation, salinity, pH and increasing temperature. These organisms face different threats as a result of changes in their environment. Natural disturbances, such as climatic events and tropical storms are short-lasting and infrequent enough as to enable recovery of the reefs, but chronic anthropogenic impacts (e.g. fishing practices, land-use, climate change) produce a constant cumulative stress caused by increasing of water pollutants, sediments and/or nutrients, as well as increment of seawater temperature and acidification. 

In this project I aim to disentangle the relationships between coral gowth, water quality and climatic events in Fijian inshore reefs, and reconstruct the sensitivity of reef-building corals to environmental changes in the last century. 

The main research questions we are addressing are: 
  1.	How does coral growth change across space and time in Fijian inshore reefs?
  2.	How do environmental conditions and climatic events affect different inshore reefs in Fiji. 
  3.	Can massive Porites corals be used as inshore water quality proxy?

Understanding the response of massive long-lived corals to environmental changes over time, as a result of climate and biogeochemical shifts, is critical for the assessment of the future of modern coral reefs. 

To address these questions, I am using an interdisciplinary approach that couples traditional geochemical techniques (i.e. Ba/Ca, Mn/Ca, Sr/Ca,… ) and computed tomography (CT) to reconstruct seasonal changes in coral growth (i.e. linear extension, density and calcification) from massive long-lived <i>Porites</i> corals under a range of different catchment environments (agricultural, urban and forested) and a number of stress events (e.g. thermal stress, cyclones).


<h3>MRes - Stylasterids: A new paleoceanographic archive?</h3>

Stylasterids are a commonly found deep-sea coral taxon that build their skeletons from either calcite or aragonite (or both). Their potential as paleoceanographic archives remains unexplored and robust geochemical proxy data collected from modern specimens is very limited. 

Ninety-three stylasterids were selected from locations including the Southern Ocean, Equatorial Atlantic, North Atlantic and Galápagos Islands spanning a range of depths from 63 to 2894 m and temperatures from 0 to 17°C. Samples were identified up to species level when possible. They included 20 species belonging to 7 genera. These were Adelopora sp., Cheiloporidion sp., Conopora sp., Errina sp., Errinopsis sp., Inferiolabiata sp., and Stylaster sp. Fifty-six specimens were analysed for skeletal mineralogy. Sixteen samples were calcitic, and 40 were aragonitic. 

Oxygen and carbon (δ<sup>18</sup>O and δ<sup>13</sup>C) isotopic composition was measured in all the specimens. Five specimens were sub-sampled in the main trunk, secondary branches and growing tips. All data were below equilibrium, with the tips of the colonies having the lightest values, and the trunk being the heaviest. The δ<sup>18</sup>O and δ<sup>13</sup>C range within a single specimen is lower compared to published values in deep-sea scleractinian corals. All the specimens were subsampled in the main trunk. Their δ<sup>18</sup>O and δ<sup>13</sup>C was measured and compared to local hydrographic data to gain insight into calcification mechanisms and test their use as paleotemperature archives. Different isotopic values were found between aragonitic and calcitic samples. Calcitic corals showed less depleted values from equilibrium for δ<sup>18</sup>O but a higher depletion forδ<sup>13</sup>C. 

The data indicate that environmental temperature is recorded in the skeletal chemistry of stylasterid corals. A global δ<sup>18</sup>O:temperature calibration for aragonitic stylasterids was produced. This calibration showed a mean depletion of 0.97‰ from equilibrium. This work highlights the potential application of stylasterid coral δ<sup>18</sup>O data to reconstruct ancient seawater temperature.

<img src="research/IMG_7262 (2).JPG" alt="Stylasterid coral" width="500" height="600">

<h4>Output:</h4> Samperiz, A., Robinson, L., Stewart, J., Strawson, I., Leng, M., Rosenheim, B., Ciscato, E., Hendry, K., Santodomingo, N. 2020.  <a href='https://doi.org/10.1016/j.epsl.2020.116407'>Stylasterids: A new paleoceanographic archive.</a> <i>Earth and Planetary Science Letters</i> 545:116407. doi:10.1016/j.epsl.2020.116407
<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
