---
layout: page
title: Spectral broadening and post-compression at CXI 
description: Advancing time-resolved hard x-ray scattering experiments via spectral broadening and post-compression
img: assets/img/IMG_0076.jpg
importance: 1
category: work
related_publications: false
---

Sub-10 femtosecond (fs) pulses at 800 nm are generated via spectral broadening and post-compression of the Ti:Sapphire laser system at the coherent x-ray imaging (CXI) instrument at LCLS. 
Combined with sub-10 fs x-ray pulses from the FEL generated using half-charge mode, we have demonstrated 9.7 fs and 13.1 fs instrument response functions at 15 keV and 10 keV, respectively, in two different gas-phase hard x-ray scattering experiments.

The hollow capillary fiber (HCF) set-up and laser beam path is depicted below.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CXI_HCF_1.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The hollow capillary fiber (HCF) system built at CXI, with HCF parameters listed. Dispersion is managed using chirped mirrors and bulk material propagation.
</div>

The spectrum of the output of the HCF is shown below when under vacuum and pressurized with 1.0 bar of Ar, showing the spectral broadening. The mode is also shown and isn't the worst thing ever. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CXI_HCF_2.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The spectrum and mode of the spectrally broadened HCF output.
</div>

The pulse duration is characterized using second harmonic generation frequency-resolved optical gating (SHG-FROG) and FROG retrieval is performed using [this code](https://github.com/leschenkos/Slava-FROG).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CXI_HCF_3.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The measured SHG-FROG autocorrelation is 12 fs FWHM. The SHG-FROG retrieval gives 8.3 fs FWHM pulse duration. 
</div>

Using the FEL in half-charge mode at 9.8 keV and the 8.3 fs 800 nm pulses, we measured a 13.1 fs instrument response function in cyclohexadiene following strong-field ionization.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CXI_HCF_5.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The measured 13.1 fs instrument response function in CHD. 
</div>

Using the FEL in half-charge mode at 15 keV and the 8.3 fs 800 nm pulses, we measured a 9.7 fs instrument response function in heavy water following strong-field ionization.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CXI_HCF_4.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The measured 9.7 fs instrument response function in heavy water. 
</div>
