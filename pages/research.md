---
layout: page
title: Research
permalink: /research
image: /assets/img/CloudBand.jpeg
---

<p align="justify">
Clouds and aerosols remain some of the greatest sources of uncertainty for future climate projections, 
as these processes happen at scales smaller than Earth system model grids (∼100 km), but involve complex, 
non-linear, and multi-scale behavior that is challenging to parameterize. My research develops scientific AI methods that combine
physical constraints, observations, and high-resolution simulations to discover governing
relationships and translate them into Earth system model parameterizations. 
</p>

<h2 id="agentic-ai-for-earth-system-model-development">Agentic AI for Earth system model development</h2>

<p align="justify">
Integrating new physical knowledge into Earth system models has historically been a slow process; agentic AI
offers the potential to rapidly accelerate model development, while simultaneously making it more systematic. 
My research investigates how multi-agent systems can design, translate, test, and optimize Earth system model
parameterizations. This work combines automated scientific reasoning, differentiable modeling,
benchmark development, and rigorous online evaluation to make model development more systematic
and more reproducible. 
</p>

<p align="justify">
A recent talk I gave on this topic: <a href="https://www.youtube.com/watch?v=uo6nUV0MVbo">Agentic AI for Earth system model development</a>.
</p>

<h2 id="learning-cloud-microphysics">Improving Cloud Processes in Earth System Models</h2>
<h3>Systematic Cloud Microphysics Development with Machine Learning</h3>
<img src="{{ site.github.url }}/assets/img/cloudfields.jpg" alt="Field of shallow cumulus clouds seen from above" class="figure" width="220" height="165" align="right" style="margin: 0 0 12px 20px;"/>
<p align="justify">
Cloud microphysics, the small-scale interactions between liquid droplets and ice crystals, plays a 
central role in the climate through its effects on radiation, cloud lifetimes, and precipitation, 
and is one of the most significant sources of model uncertainty. Current microphysical schemes are 
limited by physical process uncertainty and by the difficulty of developing simplified (bulk) models used in Earth system models.
Machine learning can emulate expensive computational models and can build parameterizations directly from observations and higher-resolution models
using reduced-order approaches, which yield compact representations that remain physically
interpretable.
</p>
<p align="justify">
<small>[1] <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023MS003918">Lamb, van Lier Walqui, Santos, Morrison. JAMES (2024)</a></small><br>
<small>[2] <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025MS005341">Lamb, Singer, Loftus, Morrison, Powell, Ko, Buch, Hu, van Lier Walqui, Gentine. JAMES (2026)</a></small><br>
</p>
<br clear="all">


<h3>Learning Ice Microphysics from Observations with Physics-Informed Machine Learning</h3>
<img src="{{ site.github.url }}/assets/img/Cirrus.jpg" alt="Cirrus clouds at high altitude" class="figure" width="220" height="165" align="right" style="margin: 0 0 12px 20px;"/>
<p align="justify">
Depositional ice growth is an important microphysical process controlling cloud formation in
mixed-phase and ice clouds. Ice crystal habits and growth rates depend sensitively on temperature,
pressure, and supersaturation, but the surface effects controlling vapor deposition are complex
and difficult to characterize experimentally. This lack of clear physical understanding makes it
hard to predict ice crystal habits and to parameterize depositional growth in weather and climate
models. We use physics-informed machine learning and symbolic regression to recover
interpretable growth laws directly from laboratory experiments, and generative AI to
connect in situ ice crystal images observed during airborne field campaigns to their past atmospheric history.
</p>
<p align="justify">
<small>[1] <a href="https://arxiv.org/abs/2510.17935">Lamb, Harrington, Moyle, Pokrifka, Clouser, Ebert, M&ouml;hler, Saathoff. In press (2026)</a></small><br>
<small>[2] <a href="https://acp.copernicus.org/articles/23/6043/2023/">Lamb et al. Atmospheric Chemistry and Physics (2023)</a></small><br>
<small>[3] <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025JH000905">Ko, Harrington, Sulia, Przybylo, van Lier Walqui, Lamb. JGR: Machine Learning and Computation (2025)</a></small><br>
<small>[4] <a href="https://arxiv.org/abs/2509.07688">Ko, Govindarajan, Lindsten, Sulia, Przybylo, van Lier Walqui, Lamb. NeurIPS Tackling Climate Change with ML (2025)</a></small><br>
<small>[5] <a href="https://essopenarchive.org/doi/full/10.22541/essoar.15003780/v1">Nicolaou, Frields, Stephens, Watson-Parris, Cai, Sulia, Przybylo, Ko, Lamb. In press (2026)</a></small>
</p>
<br clear="all">


<h3>Parameterizing Cloud Macrophysics</h3>
<img src="{{ site.github.url }}/assets/img/wave-clouds.JPG" alt="Wave clouds organized in parallel bands" class="figure" width="220" height="165" align="right" style="margin: 0 0 12px 20px;"/>
<p align="justify">
The amount of sunlight clouds reflect or absorb plays an important role in the Earth's energy
budget. Clouds form complex patterns that evolve over time and are challenging to parameterize,
and the spatio-temporal organization of clouds and convection strongly affects cloud lifetime and
the amount and timing of precipitation. Machine learning can be used to develop novel metrics
representing subgrid-scale cloud macrophysical properties in large-scale models.
</p>
<p align="justify">
<small>[1] <a href="https://www.pnas.org/doi/10.1073/pnas.2216158120">Shamekh, Lamb, Huang, Gentine. PNAS (2023)</a></small>
</p>
<br clear="all">

<h2 id="ai-for-precipitation-and-climate-interventions">AI for precipitation and climate interventions</h2>

<p align="justify">
We use large-scale historical datasets, causal inference, and physically grounded machine learning to evaluate 
interventions that affect precipitation and climate risk. Our current work focuses on the climatological impacts 
and optimization of cloud seeding, including its potential implications for water resources, drought, and wildfire risk. 
Although cloud seeding has been conducted operationally across the western United States for decades, 
its aggregate effect on precipitation has not previously been evaluated at climatological scales. A major obstacle was 
that the historical operational record existed primarily in unstructured reports and could not be readily analyzed. 
We therefore first constructed a machine-readable record of cloud-seeding activities and are now using it, together with 
historical meteorological data, to determine when, where, and under what conditions cloud seeding affects precipitation.
</p>
<p align="justify">
<small>[1] <a href="https://www.nature.com/articles/s41597-025-06273-1">Donohue and Lamb. Scientific Data (2025)</a></small><br>
<small>[2] <a href="https://doi.org/10.1017/eds.2025.4">Liao, Buch, Lamb, Gentine. Environmental Data Science (2025)</a></small><br>
<small>[3] <a href="https://www.nature.com/articles/s42005-025-02426-1">Nathaniel, Roesch, Buch, DeSantis, Rupe, Lamb, Gentine. Communications Physics (2025)</a></small>
</p>
<br clear="all">
