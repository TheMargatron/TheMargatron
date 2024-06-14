Hello and welcome to my PhD homepage! I am Margaret Bolton and I'm most of the way through my [Environmental Intelligence](https://www.exeter.ac.uk/research/eicdt/) PhD at the University of Exeter, supervised by the marvellous [Regan Early](https://biosciences.exeter.ac.uk/staff/profile/index.php?web_id=Regan_Early) and excellent [Abraham Kuijper](https://biosciences.exeter.ac.uk/staff/profile/index.php?web_id=Bram_Kuijper). To give you a quick background, I completed my BSc in Ecology at the University of Edinburgh, did a conservation internship with the RSPB at Otmoor, then finished my MSc with a first class degree in Applied Ecology at the University of Exeter where I first met my two current supervisors. I like to take an interdisciplinary approach to research so have fitted in well at the EI CDT. Their core goal is to unite different fields of research to solve environmental problems through the application of AI and data science. The common threads in my research interests are biotic interactions, biogeography, theoretical ecology, and the application of novel research methods. Alongside my PhD I have provided coding support to undergraduates in their final year, contributed to an AI-centred art exhibition, taught a crochet workshop, and supported the running of the EI CDT Art Lab.

## PhD chapter summary
The working title of my PhD is ... still a work in progress. The thesis consists of the following 3.5 core chapters.

Chapter 1: Parasitism
* Combining data from the Global Mammal Parasite database, GBIF, and the IUCN, Regan and I are examining gradients in parasitism rates across latitudes, host ranges, and host climatic niches. The main finding is that hosts are most likely to face parasitism at low latitudes (i.e. towards the equator). Hosts are also most likely to experience parasitism at the edges of their range, a pattern which we think is driven by climatic stress on the host at low latitudes, but by another unidentified factor at high latitudes.
* The R code will be available on publication

Chapter 2: Altruism
* This section started as set-up research for chapter 3 but has since become its own entity. Bram and I have developed an individual based simulation in C++ which we are using to explore the ecological thresholds beyond which helpful behaviour evolves. For example, if the average adult survival of a population is higher, the more likely it is that help will evolve since an individual is more likely be interacting with kin. In this chapter we explore the effect of competition between generations, implementing different model update mechanisms to reflect different real-life species traits.

Chapter 3: Mutualism
* Tying back to the first chapter, mutualism and parasitism exist on a continuum whereby environmental or ecological dynamics can cause a species to switch from parasitism to mutualism, and vice versa. This chapter takes the C++ simulation from chapter three and allows individuals to interact with a separate species. We are still in the early stages of exploring this simulation so the main result so far is that the model works!

Chapter 3.5: AI-ism (sensitivity analysis)
* If time permits, I would like to write a wrapper program for the C++ simulation which uses machine learning to perform sensitivity analysis, feeding the simulation with inputs and exploring the parameter space to find either the range of parameters which have the strongest effect on the evolution of help or the sets of parameters which define the evolutionary threshold for help.

## Publications and talks
The Bayesian data analysis I did for my undergraduate thesis contributed to this paper on blue tit biogeography:
[The effects of woodland habitat and biogeography on blue tit Cyanistes caeruleus territory occupancy and productivity along a 220 km transect](https://doi.org/10.1111/ecog.03573)

I gave an engaging and well received pick-your-own-adventure style talk on my evolutionary research at the 28th EMPSEB conference. I have delivered many other presentations, including at the Macro-Ecology SIG conference in 2018 and the Symposium on Ecological and Evolutionary drivers of pathogen emergence. 

As a result of my work with the EI Art Lab I was invited to give a radio interview in the lead up to the British Science Festival in 2023 with Heart Devon, followed by a second on ABC's Science Show with Robyn Williams.

## Art Lab
Art Lab is an interdisciplinary workshop funded by the EI CDT which [Harriet Poznansky](https://www.harrietpoznansky.com/about-contact) runs and I support through admin, co-hosting, and promotion. The goal is to create a space where scientific and artistic research can meet to fuel the development of new ideas and new ways of communicating those ideas. 
