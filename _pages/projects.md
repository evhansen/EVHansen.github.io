---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## A little on Neutrinos:

Neutrinos are one of the most abundant particles in the observable universe, and yet they are one of the least understood parts of nature. The neutrino can be emitted from the sun and from the earth; we also observe them from nuclear reactors, supernovae, and particle accelerators. The human body also produces neutrinos! Why don't we understand something that's so common? It mostly has to do with how neutrinos interact with matter. Short answer is: they mostly don't! Neutrinos interact via the weak force, and therefore tend to travel through matter as if its not even there. It takes gigantic detectors or very active sources to get any observed events! But... there are quite a few things we do know:

Neutrinos come in three "flavors" -- which flavor is observed by a given interaction is not only based on where it was born but also how long it's been since it was created, as a single neutrino oscillates between flavors as it travels. The mechanism by which these flavors oscillate is due to a rotation between the flavor eigenstates and the mass eigenstates -- thus the observation of neutrino oscillations requires at least two neutrinos to have a nonzero mass. Considering the best model at the time suggested neutrinos always had zero mass, this was _huge_! The Nobel Prize was awarded very recently ([2015](https://www.nobelprize.org/prizes/physics/2015/advanced-information/)) "for the discovery of neutrino oscillations, which shows that neutrinos have mass."

We have known neutrinos have mass, but what exactly is the value of their mass? ... ... **No one knows**. We have a pretty good idea of how big they aren't (we know they're less than 1 eV) but we don't have values for the masses, or in fact which mass state is the lightest!

We don't know a lot of things about the neutrino, but one of the most fascinating outstanding questions is the possibility that neutrinos, as neutral massive particles, could possibly be their own antiparticle. This all has to do with the frame of reference you're looking in, and FermiLab has a great analogy [here](https://news.fnal.gov/2012/09/neutrinos-majorana-or-dirac/). I currently participate in an experiment ([CUPID](https://cupid.lngs.infn.it)) that seeks to understand this particular question by compiling a lot of a very special isotope, 100-Molybdenum, putting it in one place with a bunch of instrumentation, and waiting for it to decay. My job, through analysis and hardware development, is to help isolate the signal of a neutrinoless double beta decay from backgrounds caused by Earth and her materials being inherently full of radioactivity noise.

You can learn more about [neutrinos](https://www.symmetrymagazine.org/article/is-the-neutrino-its-own-antiparticle), [rare-event searches](https://www.symmetrymagazine.org/article/waiting-for-a-sign), and [background reduction](https://www.symmetrymagazine.org/article/on-background) at these links.


## Current and Past Projects:

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}

