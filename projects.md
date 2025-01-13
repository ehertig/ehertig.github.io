---
layout: page
title: Projects
permalink: /projects/
main_nav: true
---

<hr>

<h3 id="headings">B-mode delensing for the Simons Observatory</h3>

<h5 id="headings">University of Cambridge & Simons Observatory Collaboration, supervised by Anthony Challinor and Blake Sherwin</h5>

The Simons Observatory (SO) will target B-mode polarization anisotropies in the CMB to infer the tensor-to-scalar ratio (amplitude of inflationary gravitational waves). This faint signal must be disentangled from much brighter emissions by our own Galaxy, and from secondary B-modes produced by weak gravitational lensing. During my PhD, I worked on a pipeline performing both foregroung cleaning and delensing simultaneously, aiming to go from sky maps to unbiased and precise constraints on inflationary physics. The methods and results are presented in detail in this [paper](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.043532).

<ul>
  <li>The following code estimates the lensing deflection field from a combination of CMB maps and external data, and builds a template of the lensing B-modes.</li>
</ul>

[![Lensing reconstruction code]({{ site.baseurl }}/assets/Delensing_code_repo.jpg "Lensing reconstruction code")](https://github.com/simonsobs/delensing)

<ul>
  <li>The main analysis pipeline then takes observed sky maps and the lensing template as inputs, and outputs posterior distributions for our model parameters. We use maps in 6 frequency channels to constrain and clean Galactic foregrounds.</li>
</ul>

[![Component separation code]({{ site.baseurl }}/assets/BBPower_repo.jpg "Component separation code")](https://github.com/simonsobs/BBPower/tree/delensing-emilie)

<ul>
  <li>Demonstration on simulated maps: the template accurately captures the true lensing B-modes, and including it in the analysis leads constraints on the tensor-to-scalar ratio to visibly tighten.</li>
</ul>

![Results on simulations]({{ site.baseurl }}/assets/SO_project_summary.jpg "Results on simulations")

<hr>

<h3 id="headings">Lattice simulations of false vacuum decay</h3>

<h5 id="headings">University of Cambridge & QSimFP Consortium, in collaboration with Hiranya Peiris and Alex Jenkins</h5>

<p>  </p>

<p> </p>

<hr>

<h3 id="headings">Model-independent anomaly detection in gravitational waves</h3>

<h5 id="headings">EPFL LPPC, supervised by Sergey Sibiryakov and Inar Timiryasov</h5>

<p>  </p>

<hr>

<h3 id="headings">Time-delay cosmography with strongly lensed quasars</h3>

<h5 id="headings">EPFL LASTRO, supervised by Frederic Courbin and Aymeric Galan</h5>

<p> TDLMC pipeline found here https://github.com/TDCOSMO/hierarchy_analysis_2020_public/tree/master/TDLMC </p>

<hr>

<h3 id="headings">CHIME radiotelescope calibration</h3>

<h5 id="headings">UBC Vancouver, supervised by Gary Hinshaw and Mateus Fandino</h5>

<p> </p>

<hr>
