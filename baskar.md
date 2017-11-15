---
layout: default
title: ComPM Lab
permalink: /research/compm
---

# Computational Physics and Mechanics Laboratory


In the spring semester of my freshman year, I participated in ISU's Honors Mentor Research program. This program pairs first-year honors students with faculty research mentors to participate in undergraduate research. I was paired with Dr. Baskar Ganapathysubramanian's group in the Computational Physics and Mechanics Laboratory. I continued my work with the ComPM group through the end of my second year at Iowa State.

When I first joined, I learned about the lab's computational framework for simulating the self-segregating effects of block copolymers (BCP). These effects are of interest due to the amount of control they enable for the structure of polymers at a micro-scale. The BCPs that we analyzed were di-block copolymers, consisting of two blocks of monomer units (an A and B block) covalently bonded to form a polymer chain. In a bulk system (or melt) of BCPs, the equilibrium or lowest energy structure is determined by two main factors: the "Flory-Huggins" parameter describing how much the A and B block dislike each other and want to segregate, and the ratio of the length of the A block to the length of the entire polymer chain.


<figure>
	<img src="{{ site.baseurl }}/assets/bcp_models.jpg" alt="Abstracted models of di-block copolymers"/>
	<figcaption> Various ways of modeling di-block copolymers. <a href="https://www.sciencedirect.com/science/article/pii/S0021999116306064">Image source</a></figcaption>
</figure>

I spent some of this initial time creating meshes in Matlab to be used as inputs for simulations. I also learned the basics of High-Performance Computing and how to work with Stampede and Comet supercomputers located at the Texas Advanced Computing Center and San Diego Supercomputer Center, respectively.
 
<figure>
	<img src="{{ site.baseurl }}/assets/seahorse.png" alt="Simulation on a seahorse-shaped mesh"/>
	<figcaption>A simulation run on a seahorse-shaped mesh, highlighting our ability to run simulations for arbitrary shapes. To make this, I first wrote a Matlab script that turns a solid, black and white image into a set of coordinates to be used as in input for the mesh making library. The mesh is then used for the input for the simulation. </figcaption>
</figure>


My main project consisted of developing a framework for efficiently creating phase diagrams for BCP systems under confinement. Confinement effects, such as a BCP melt in a cylindrical nanopore template, introduce another degree of control for the final structure of a BCP melt. Modeling these confinement effects allows us to explore unique geometries and observe novel structures not seen in a bulk BCP system.

Part of creating this framework required me to parametrically define and run simulations in large batches. In order to keep all of the data organized, I created scripts to easily tag data and organize it in an SQL database. 

Another aspect of my research included learning about effective communication of scientific research. In order to strengthen my communication skills, I made research posters and oral presentations, for the following symposiums:

* Iowa State University Undergraduate Research Symposium - April 2017
   
   Oral Presentation - "Effects of Confinement Geometry on Diblock Copolymer Systems Using Finite Element Analysis"

* National Conference on Undergraduate Research - April 2017

   Oral Presentation - "Effects of Confinement Geometry on Diblock Copolymer Systems Using Finite Element Analysis" 

* Materials Research Society Fall Meeting - November 2016

   Poster Presentation - "Exploration of Confined Polymer Microstructures using a Finite Element Based High Throughput Computational Platform"

* Iowa State University Honors Poster Presentation

   Poster Presentation - "A Computational Study of Confinement Effects in Block Copolymers"

<figure>
	<img src="{{ site.baseurl }}/assets/ncur.JPG" alt="The author presenting at the National Conference on Undergraduate Research"/>
	<figcaption>My presentation at the National Conference on Undergraduate Research in Memphis, Tennessee</figcaption>
</figure>
