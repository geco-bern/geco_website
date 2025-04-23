---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Highlights of 2024"
subtitle: ""
summary: ""
authors: [Benjamin Stocker]
tags: []
categories: []
date: 2025-04-23T13:37:08+02:00
lastmod: 2025-04-23T13:37:08+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Here are some highlights of our research and collaborations in 2024.

## Research

### *How does nitrogen influence the global carbon cycle?*

Nitrogen is an essential nutrient for plants and is used both in photosynthesis enzymes and for building cell structures. Therefore, plant availability of nitrogen plays an important role in the global carbon cycle and its change under global warming and an increase in atmospheric CO<sub>2</sub>. For example, the question is whether and to what extent nitrogen availability limits the CO<sub>2</sub> fertilization of plant growth. Global models simulate these relationships and therefore require a solid understanding of relevant processes. In our review study (Stocker et al., 2024), we show (i) that these models simulate strongly divergent global carbon balances in recent decades (Fig. 1), (ii) that these divergences are related to different representations of carbon-nitrogen cycle interactions, and (iii) that theoretical foundations from evolutionary ecology enable more robust models that explain essential patterns from empirical analyses and experiments.

![TRENDY C sink](sink_trend_trendy.png "Temporal change in the global C sink over the years 1959-2020 from model simulations and observations (Obs.). Models are divided into model types that simulate carbon and nitrogen interactions (CN) and models that only simulate the carbon cycle (C). Model names are given in the legend. This figure shows that CN models diverge strongly in their simulation of the land carbon sink, while C models are relatively consistent with each other, but systematically overestimate the sink. Figure from Stocker et al. (2024).")

In another study (Stocker & Prentice, 2024), we show how these theoretical foundations can be implemented in a dynamic model of terrestrial carbon and nitrogen dynamics. The foundation of the model is (i) the acclimatization of photosynthesis to the abiotic environment (climate, CO<sub>2</sub>) and its implication for nitrogen demand, and (ii) the allocation of assimilated carbon for growth in aboveground biomass (stem, leaves) versus root growth. The model representation of allocation is based on the functional balance approach, which is dynamically simulated in the model as a function of nitrogen, light, and CO<sub>2</sub> availability. With these relatively simple basic assumptions, we can predict both the seasonal plant growth dynamics and the CO<sub>2</sub> and nitrogen balance of the ecosystem (Fig. 2), as well as the response of plants to experimentally manipulated CO<sub>2</sub> concentration and nitrogen fertilization. Thus, we provide a demonstration of how the core of global vegetation models can be formulated to more reliably simulate global changes in the carbon cycle and thus in the Earth system. 

![N sinks](n_sinks_sources.png "")
![C sinks](c_sinks_sources.png "Modeled seasonal plant growth dynamics and the C and nitrogen (N) balance of an ecosystem. Figure from Stocker & Prentice (2024).")

#### References

Stocker, B. D., Dong, N., Perkowski, E. A., Schneider, P. D., Xu, H., de Boer, H. J., Rebel, K. T., Smith, N. G., Van Sundert, K., Wang, H., Jones, S. E., Prentice, I. C., and Harrison, S. P.: Empirical evidence and theoretical understanding of ecosystem carbon and nitrogen cycle interactions, *New Phytologist*, n/a, https://doi.org/10.1111/nph.20178, n.d.

Stocker, B. D. and Prentice, I. C.: CN-model: A dynamic model for the coupled carbon and nitrogen cycles in terrestrial ecosystems, *biorxiv*, https://doi.org/10.1101/2024.04.25.591063, 28 April 2024. [pre-print]


### **(How) do environmental factors and species affiliation influence nitrogen (N) and phosphorus (P) concentrations in plant leaves?**

A widespread assumption is that the nutrient concentration of leaves is mainly determined by species affiliation - a concept known as the “biogeochemical niche hypothesis”. This hypothesis assumes that each plant species occupies a fixed biogeochemical niche with specific N:P ratios. Our study (Tian et al., 2024) challenges this assumption by analyzing the influence of environmental factors on leaf nutrient composition using various statistical and machine learning-based models.
 
![Random Forest vs. Linear Mixed Effects model](leafp_lmm_rf.png "Proportion of explained variation (*R*<sup>2</sup>) of environmental factors (Environment) and species identity, estimated with different model types (LMM: Linear Mixed Effects Models, RF: Random Forest).") 

About half of the total variation in leaf N and P and in the N:P ratio occurs within species, while environmental variables explain 29 % of the variation in leaf N, 31 % in leaf P and 22 % in the N:P ratio. Nitrogen deposition, atmospheric CO<sub>2</sub> concentrations and the temperature of the coldest month are particularly significant. Random forest models identified environmental factors as significant drivers of within-species variation, while linear mixed effects models largely failed to detect these effects. Many species show a high plasticity in their leaf nutrient composition along environmental gradients, indicating a flexible adaptation to different environmental conditions. The results of the study suggest that environmental factors play as important a role as phylogenetic affiliation in determining leaf nutrient composition. We also show that previous interpretations of the data were based on limited statistical methods. This challenges the previous assumption of a fixed biogeochemical niche and emphasizes the importance of phenotypic plasticity of plants.

#### Reference

Tian, D., Yan, Z., Schmid, B., Kattge, J., Fang, J., and Stocker, B. D.: Environmental versus phylogenetic controls on leaf nitrogen and phosphorous concentrations in vascular plants, *Nature Communications*, 15, 5346, https://doi.org/10.1038/s41467-024-49665-4, 2024.

## Networking and collaboration  

- Pilot project with Swiss Data Science Center to detect anomalies in satellite data of forests in Switzerland. Visualization of anomalies published: https://ndvi-anomalies.dsl.unibe.ch/.
- Collaboration with Prof. O. Romppainen-Martius (GIUB) in the HYD-RESPONSES project on behalf of the Swiss Federal Office for the Environment.
- Collaboration with Prof. M. Raissig (Biology, Uni. Bern) in project funded by Oeschger Centre for Climate Change Research
- Collaboration with various partners (led by Prof. S. Harrison, Uni. Reading, UK) in project (LEMONTREE) funded by Schmidt Futures Virtual Earth System Research Institute
- Collaboration on white paper “How to unfold the full potential of AI to mitigate climate change impact on Swiss society and economy” with various partners under the leadership of the Swiss Academy of Engineering Sciences. Publication: Holzner et al. (2024), see 'Further publications'.

## Further publications

Bachofen, C., Tumber-Dávila, S. J., Mackay, D. S., McDowell, N. G., Carminati, A., Klein, T., Stocker, B. D., Mencuccini, M., and Grossiord, C.: Tree water uptake patterns across the globe, *New Phytologist*, 242, 1891–1910, https://doi.org/10.1111/nph.19762, 2024.

Holzner, C., Jennifer Susan Adams, Christos Altantzis, Tom Beucler, Julia Bingler, Samuel Brown, Thomas Brunschwiler, Chiara Colesanti-Senni, Frank de Morsier, Márcio dos Reis Martins, Andreas M. Fischer, Stefan Frei, Remo M. Frey, Alisa Freyre, Gregory Giuliani, Marvin Höge, Apolonio Huerta, Vincent Humphrey, Stefan Keller, Romeo Kienzler, Erwan Koch, Jonathan Koh, Agnieszka Kosinska, Sven Kotlarski, Manuel Kugler, Gerrit Kuhlmann, Markus Leippold, Reik Leiterer, David Leutwyler, Olivia Martius, Adrien Michel, Veruska Muccione, Michal Muszynski, Urs Neu, Diana-Denisa Rodila, Claudia Röösli, Andreas Scheidegger, Tobias Schimanski, Konrad Schindler, Christian Spindler, Tanja Stanelle, Benjamin Stocker, Devis Tuia, Saeid Ashraf Vaghefi, Jan Dirk Wegner, Jonas Weiss, Matthew Whellens, Mira Wolf-Bauwens, Hendrik Wulf, Biagio Zaffora, and Marius Zumwald: How to use the power of AI to reduce the impact of climate change on Switzerland, Swiss Academy of Engineering Sciences SATW, Zurich, 2024.

Liu, J., Ryu, Y., Luo, X., Dechant, B., Stocker, B. D., Keenan, T. F., Gentine, P., Li, X., Li, B., Harrison, S. P., and Prentice, I. C.: Evidence for widespread thermal acclimation of canopy photosynthesis, *Nature Plants*, 1–9, https://doi.org/10.1038/s41477-024-01846-1, 2024.

Sophia, G., Caldararu, S., Stocker, B. D., and Zaehle, S.: Leaf habit drives leaf nutrient resorption globally alongside nutrient availability and climate, *Biogeosciences*, 21, 4169–4193, https://doi.org/10.5194/bg-21-4169-2024, 2024.

Zhang-Zheng, H., Deng, X., Aguirre-Gutiérrez, J., Stocker, B. D., Thomson, E., Ding, R., Adu-Bredu, S., Duah-Gyamfi, A., Gvozdevaite, A., Moore, S., Oliveras Menor, I., Prentice, I. C., and Malhi, Y.: Why models underestimate West African tropical forest primary productivity, *Nature Communications*, 15, 9574, https://doi.org/10.1038/s41467-024-53949-0, 2024.

Kladny, K.-R., Milanta, M., Mraz, O., Hufkens, K., and Stocker, B. D.: Enhanced prediction of vegetation responses to extreme drought using deep learning and Earth observation data, *Ecological Informatics*, 80, 102474, https://doi.org/10.1016/j.ecoinf.2024.102474, 2024.


