---
layout: page
title: Research Program
permalink: /research
image: /assets/img/CloudBand.jpeg
---

<h2>Research vision</h2>

<p align="justify">
Many of the largest uncertainties in Earth system models arise from processes that are nonlinear,
multiscale, and sparsely observed. My research develops scientific AI methods that combine
physical constraints, observations, and high-resolution simulations to discover governing
relationships and translate them into robust model components. The long-term goal is an
integrated framework in which AI assists not only with fitting parameterizations, but with
formulating hypotheses, developing code, diagnosing model behavior, and evaluating physical
consistency.
</p>

<h2 id="agentic-ai-for-earth-system-model-development">Agentic AI for Earth system model development</h2>

<p align="justify">
We develop multi-agent systems that help design, translate, test, and optimize Earth system model
parameterizations. This work combines automated scientific reasoning, differentiable modeling,
benchmark development, and rigorous online evaluation to make model development more systematic
and reproducible. Parameterization development has historically been slow, artisanal, and hard to
reproduce; the aim here is to make it a systematic, testable process in which physical constraints
and online model stability are first-class criteria rather than afterthoughts.
</p>

<p align="justify">
This thrust is supported by a DOE Genesis award and by Google TPU support for AI-ready climate
modeling, and connects to a broader effort to build modular, differentiable Earth system models.
</p>

<p align="justify">
<small>[1] <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025MS005341">Lamb, Singer, Loftus, Morrison, Powell, Ko, Buch, Hu, van Lier Walqui, Gentine. JAMES (2026)</a></small><br>
<small>[2] <a href="https://arxiv.org/abs/2510.10654">Erfani, Lamb, Bauer, Tsigaridis, van Lier Walqui, Schmidt. Under review (2025)</a></small><br>
<small>[3] <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025JH001011">Erfani, Lamb, Bauer, Tsigaridis, van Lier Walqui, Schmidt. JGR: Machine Learning and Computation (2026)</a></small>
</p>

<h2 id="learning-cloud-microphysics">Learning cloud microphysics with physics-informed machine learning</h2>

<p align="justify">
We combine laboratory and airborne field observations, high-resolution simulations, and scientific machine learning to discover interpretable cloud microphysical processes and develop improved cloud parameterizations. Current topics include using generative AI and physics-informed machine learning to improve ice microphysical process representation, and using reduced order modeling to parameterize warm rain microphysical processes.
</p>

<p align="justify">
Cloud microphysics is the physical center of gravity of my program: it is where the governing
processes are least well constrained, where laboratory and in situ observations can still settle
open questions, and where errors propagate directly into climate projections.
</p>

<h3>Ice microphysics and depositional growth</h3>
<img src="{{ site.github.url }}/assets/img/Cirrus.jpg" alt="Cirrus clouds at high altitude" class="figure" width="220" height="165" align="right" style="margin: 0 0 12px 20px;"/>
<p align="justify">
Depositional ice growth is an important microphysical process controlling cloud formation in
mixed-phase and ice clouds. Ice crystal habits and growth rates depend sensitively on temperature,
pressure, and supersaturation, but the surface effects controlling vapor deposition are complex
and difficult to characterize experimentally. This lack of clear physical understanding makes it
hard to predict ice crystal habits and to parameterize depositional growth in weather and climate
models. We use neural ordinary differential equations and symbolic regression to recover
interpretable growth laws directly from cloud chamber experiments, and conditional diffusion
models to infer thermodynamic histories from in situ ice crystal imagery.
</p>
<p align="justify">
<small>[1] <a href="https://arxiv.org/abs/2510.17935">Lamb, Harrington, Moyle, Pokrifka, Clouser, Ebert, M&ouml;hler, Saathoff. In press (2026)</a></small><br>
<small>[2] <a href="https://acp.copernicus.org/articles/23/6043/2023/">Lamb et al. Atmospheric Chemistry and Physics (2023)</a></small><br>
<small>[3] <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025JH000905">Ko, Harrington, Sulia, Przybylo, van Lier Walqui, Lamb. JGR: Machine Learning and Computation (2025)</a></small><br>
<small>[4] <a href="https://arxiv.org/abs/2509.07688">Ko, Govindarajan, Lindsten, Sulia, Przybylo, van Lier Walqui, Lamb. NeurIPS Tackling Climate Change with ML (2025)</a></small><br>
<small>[5] <a href="https://essopenarchive.org/doi/full/10.22541/essoar.15003780/v1">Nicolaou, Frields, Stephens, Watson-Parris, Cai, Sulia, Przybylo, Ko, Lamb. Under review (2026)</a></small>
</p>
<br clear="all">

<h3>Aerosol and cloud microphysics parameterization</h3>
<img src="{{ site.github.url }}/assets/img/cloudfields.jpg" alt="Field of shallow cumulus clouds seen from above" class="figure" width="220" height="165" align="right" style="margin: 0 0 12px 20px;"/>
<p align="justify">
Improving representations of aerosol and cloud microphysics in atmospheric models is key to
accurately predicting future changes in climate, but current microphysical schemes are limited by
both structural and parametric uncertainty. Machine learning can emulate expensive computational
models and can build parameterizations directly from observations and higher-resolution models
using reduced-order approaches, which yield compact representations that remain physically
interpretable.
</p>
<p align="justify">
<small>[1] <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023MS003918">Lamb, van Lier Walqui, Santos, Morrison. JAMES (2024)</a></small><br>
<small>[2] <a href="https://www.nature.com/articles/s41598-023-45235-8">Lamb and Gentine. Scientific Reports (2023)</a></small><br>
<small>[3] <a href="https://ml4physicalsciences.github.io/2024/files/NeurIPS_ML4PS_2024_208.pdf">Lamb and Harrington. NeurIPS ML4PS (2024)</a></small>
</p>
<br clear="all">

<h3>Subgrid cloud variability and macrophysics</h3>
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

<img src="{{ site.github.url }}/assets/img/CloudOrg.jpeg" alt="Convective cloud field organized over a wide region" class="figure" width="220" height="165" align="right" style="margin: 0 0 12px 20px;"/>
<p align="justify">
We use large-scale historical data, causal inference, and physically grounded machine learning to
evaluate interventions affecting precipitation and climate risk. Current work examines the
climatological impacts and optimization of cloud seeding, with connections to water resources,
drought, and wildfire risk. Cloud seeding has been carried out operationally across the western
United States for decades, but its aggregate effect on precipitation has never been assessed at a
climatological scale, in part because the operational record was not machine-readable. We built
that record first, then used it to ask what the intervention actually does.
</p>
<p align="justify">
<small>[1] <a href="https://www.nature.com/articles/s41597-025-06273-1">Donohue and Lamb. Scientific Data (2025)</a></small><br>
<small>[2] <a href="https://doi.org/10.1017/eds.2025.4">Liao, Buch, Lamb, Gentine. Environmental Data Science (2025)</a></small><br>
<small>[3] <a href="https://www.nature.com/articles/s42005-025-02426-1">Nathaniel, Roesch, Buch, DeSantis, Rupe, Lamb, Gentine. Communications Physics (2025)</a></small>
</p>
<br clear="all">

<hr style="width:70%">

<p align="justify">
Before my current program I worked on in situ aerosol measurement, atmospheric instrumentation,
and isotopic water vapor as a tracer of cold cloud microphysics. That work established the
observational foundation I draw on now and is described on a separate page:
<a href="{{ site.github.url }}/earlier-research">Earlier research and field campaigns</a>.
</p>
