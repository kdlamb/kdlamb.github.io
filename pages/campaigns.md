---
layout: page
title: Research Projects
permalink: /campaigns
image: /assets/img/wave-clouds-band.jpeg
---

<p align="justify">
My current research is supported by the U.S. Department of Energy, the NSF LEAP Science
and Technology Center, the Zegar Family Foundation, and a Google Award for Machine Learning and Education with TPUs. 
The projects below are the ones I currently lead or co-lead; collaborative projects on which I am a co-investigator or named collaborator are
listed separately.
</p>

<h2>Current projects</h2>

<div class="cards">

<div class="card">
<h3 id="cm4"><a href="https://www.engineering.columbia.edu/about/news/columbia-engineering-faculty-members-awarded-genesis-mission-funding">Cloud Microphysics Multi-Scale Modeling Moonshot (CM4)</a></h3>
<p><strong>Question:</strong> Can we develop consistent multi-scale representations for turbulence and cloud microphysical processes in Earth System Models using AI and DOE ARM observations?</p>
<p><strong>Methods:</strong> Agentic AI, differentiable single-column and Earth system modeling,
automated parameterization development, benchmark design, online evaluation.</p>
<p><strong>Collaborators:</strong> Columbia, PNNL, NCAR, UW&ndash;Milwaukee<br>
<strong>Funding:</strong> U.S. Department of Energy,
<a href="https://www.energy.gov/undersecretaryforscience/genesis-mission/genesis-mission">Genesis Mission</a></p>
</div>

<div class="card">
<h3><a href="https://asr.science.energy.gov/projects/16120">Connecting Laboratory Experiments and In Situ Observations of Depositional
Ice Growth</a></h3>
<p><strong>Question:</strong> What controls the rate at which ice crystals grow by vapor
deposition in cirrus clouds, and how should that process be represented in models?</p>
<p><strong>Methods:</strong> Cloud chamber and levitation diffusion chamber experiments, aircraft cloud particle imagery,
neural ordinary differential equations, symbolic regression, conditional diffusion models.</p>
<p><strong>Collaborators:</strong> Pennsylvania State University, Columbia University<br>
<strong>Funding:</strong> U.S. Department of Energy, Atmospheric System Research</p>
<p><strong>Recent papers:</strong>
<a href="https://acp.copernicus.org/articles/23/6043/2023/">ACP (2023)</a>,
<a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025JH000905">JGR: MLC (2025)</a>,
<a href="https://arxiv.org/abs/2510.17935">ice growth discovery paper (in press)</a>.</p>
</div>

<div class="card">
<h3>Scientific Machine Learning and Ice Microphysics through LEAP</h3>
<p><strong>Question:</strong> How can scientific machine learning turn observations and
high-resolution simulations into stable, interpretable cloud parameterizations in Earth System Models?</p>
<p><strong>Methods:</strong> Reduced-order modeling of particle-based microphysics simulation, self-supervised learning on cloud particle
imagery, perturbed parameter ensembles.</p>
<p><strong>Funding:</strong> NSF <a href="https://leap.columbia.edu">LEAP Center</a> internal research awards</p>
<p><strong>Recent papers:</strong>
<a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023MS003918">JAMES (2024)</a>,
<a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025MS005341">JAMES (2026)</a>.</p>
</div>

<div class="card">
<h3>Systematizing Earth System Model Development with Agentic AI</h3>
<p><strong>Question:</strong> Can we more systematically develop, integrate, and tune parameterizations in Earth system models?</p>
<p><strong>Methods:</strong> Differentiable modeling, agentic AI, large-scale training on TPUs, benchmarking.</p>
<p><strong>Funding:</strong> Google Awards for Machine Learning and Education with TPUs</p>
</div>

<div class="card">
<h3 id="cloud-seeding">Optimizing the Where's and How's of Cloud Seeding with AI</h3>
<p><strong>Question:</strong> Does operational cloud seeding measurably change precipitation,
and can seeding strategies be optimized? Can cloud seeding reduce the risk of wildfires in the Western United States?</p>
<p><strong>Methods:</strong> Vision language model information extraction, causal inference,
large eddy simulations, reinforcement learning, denoising diffusion models.</p>
<p><strong>Collaborators:</strong> Columbia University<br>
<strong>Funding:</strong> Zegar Family Foundation</p>
<p><strong>Recent papers:</strong>
<a href="https://www.nature.com/articles/s41597-025-06273-1">Scientific Data (2025)</a> &mdash;
a comprehensive structured dataset of reported U.S. cloud seeding activities, 2000&ndash;2025.</p>
</div>

</div>

<h2>Collaborative projects</h2>

<ul>
<li><a href="https://www.bnl.gov/envsci/cloud-chamber/">An Automated, Multimodal-AI-Enabled Cloud
Chamber for Constraining Cloud Microphysical Processes</a></li>
<li>NSF Science and Technology Center: <a href="https://leap.columbia.edu">Learning the Earth with
Artificial Intelligence and Physics</a></li>
<li>NASA Digital Twins for Climate Science (with <a href="https://www.nasa.gov/goddard-institute-for-space-studies/">NASA GISS</a>)</li>
</ul>

<hr style="width:70%">

<h2>Earth and Space Science Machine Learning research sprints</h2>

<h3>Frontier Development Laboratory Europe, 2022</h3>
<img src="{{ site.github.url }}/assets/img/aerosols-fdl.png" alt="Frontier Development Laboratory Europe aerosols team project graphic" class="figure contain" width="220" height="165" align="left" style="margin: 0 20px 12px 0;"/>
<p align="justify">
I was the domain lead mentor for the <a href="https://fdleurope.org/fdl-europe-2022">Aerosols team</a>.
Over eight weeks our team developed a dataset of high-resolution geostationary satellite imagery
and meteorological data to improve forecasting of pyrocumulonimbus events using machine learning
and causal methods.
</p>
<p align="justify">
<small>[1] <a href="https://arxiv.org/abs/2211.13052"> Tazi et al., NeurIPS Tackling Climate Change with ML (2022)</a></small><br>
<small>[2] <a href="https://arxiv.org/abs/2211.08883"> Diaz Salas‐Porras et al., NeurIPS Workshop on Causality for Real-world Impact (2022)</a></small>
</p>
<br clear="all">

<h3>NASA Frontier Development Laboratory, 2019</h3>
<img src="{{ site.github.url }}/assets/img/spaceweather-fdl.png" alt="NASA Frontier Development Laboratory space weather project graphic" class="figure contain" width="220" height="165" align="left" style="margin: 0 20px 12px 0;"/>
<p align="justify">
I spent eight weeks in Mountain View, CA, as a domain science researcher on the
<a href="https://fdl.ai/">Forecasting Geoeffectiveness team</a>,
developing a data-driven machine learning approach for predicting space weather phenomena.
</p>
<p align="justify">
<small>[1] <a href="https://arxiv.org/abs/1910.01570">Lamb, Malhotra, Vlontzos, Wagstaff et al., NeurIPS ML4Physics Workshop (2019)</a></small><br>
<small>[2] <a href="https://arxiv.org/abs/1910.03085">Lamb, Malhotra, Vlontzos, Wagstaff et al., NeurIPS ML4Physics Workshop (2019)</a></small>
</p>
<br clear="all">
