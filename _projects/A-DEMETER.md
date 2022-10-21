---
title: "DEMETER"
excerpt: "Demonstrator Experiment with Multiplexed Event Topology and Energy Reconstruction"
collection: projects
---

Demonstrator Experiment with Multiplexed Event Topology and Energy Reconstruction
===
In collaboration with the Physics Division of Lawrence Berkeley National Laboratory, I lead an effort to demonstrate distinction of one- and two-electron events within ultra-cryogenic calorimeters like the lithium molybdate used in CUPID. This requires development of multiplexed signal readout at the milliKelvin scale with stringent radiopurity requirements, as well as photonic and phononic simulations and event reconstruction.

<img src='/images/DEMETER_logo.png' alt="A black star sits at the center of a large blue box. Spiraling out of the stars are two mirrored green wheat stalks, which are meant to invoke the path of electrons away from a decay site. The leaves are meant to evoke scintillation light coming off the tracks of the neutrons. The word 'demeter' is written in loopy font in all lower-case in the lower right corner of the box. " style="width:400px;height:400px;display: block; margin-right: auto; margin-left: auto;" >

## Multiplexing
Driven in part by the need to scale cryogenic electronics to the $\mathcal{O}(10k)$ channel scale for tonne-scale rare-event searches, DEMETER focuses first on multiplexed solutions for readout. These efforts address a key component missing from large scale deployment of superconducting sensors at this scale --- including both TES-arrays as well as qubits. The full-system demonstrator of the multiplexing technologies for rare event searches will be essential for the development of cryogenic experiments searching for dark matter (Cosmic Frontier of HEP) and measurements of the neutrino mass (NP).

There are quite a few issues with existing fMUX solutions when applied to rare-event searches --- 
* fMUX has not been fielded at sub-Kelvin temperatures. [CUPID](/projects/B-CUPID), for example, will operate at 0.01 K. 
* The radioactivity of uranium and thorium that is naturally occurring in materials used for multiplexing readouts is a background in rare-event searches and also negatively impacts qubit coherence. For example, any cables that are fed into the cryogenic volume must meet stringent radiopurity requirements. 
* Readout, triggering, signal processing, and data management solutions that scale to tens of thousands of channels while preserving the fidelity of the signals needs to be demonstrated.

We are currently testing frequency-domain multiplexing ('fMUX') electronics locally in the UC Berkeley dilution refrigerator. We have encouraging results from an array of TESs, but there are still some issues that need addressing including parasitic inductance. 


## Single-Crystal Reconstruction

<img src='/images/DEMETER_sketch.png' alt="A simple schematic of the current DEMETER baseline design. A blue translucent cube sits in the center of the frame, with small cubic energy sensors in one corner of each face. Three thin squares align with the back left, back right, and bottom faces of the cube, and are labeled as light detectors; they also have cubic energy sensors in one corner of each detector. The infrastructure and 3 additional light detectors are not shown." style="width:800px;height:625px;display: block; margin-right: auto; margin-left: auto;" >

The "background-free" operation of the detector is key for reaching the ultimate sensitivity. One mechanism to accomplish this could be the topological reconstruction of events at the single crystal level, i.e. directional or spatial discrimination of single-beta and double-beta events in the case of neutrinoless double beta decay. Reconstruction using a combination of light propagation and phonon wave detection would result in total event discrimination. ``Phonon imaging” [has been illustrated](https://link.aps.org/doi/10.1103/PhysRevB.33.4189) in TeO<sub>2</sub> which is a candidate cryogenic calorimeter material. Photon reconstruction is common practice in gaseous or liquid NLDBD detectors, including the use of machine learning techniques for light response calibration in liquid xenon (see my dissertation [here](https://drive.google.com/file/d/1xQsJRK8Oga5WYXljRGcimERsPrkpa_rb/view)). 

However, topological reconstruction inside solid bolometric crystals has not yet been achieved at operating temperatures. A successful demonstration of this combined technology would not only dramatically improve capabilities to search for rare events but would also contribute to searches for dark matter which rely on similar technology.


