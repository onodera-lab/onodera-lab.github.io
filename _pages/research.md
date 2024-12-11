---
title: "Onodera Lab - Research"
layout: gridlay
excerpt: "Onodera Lab -- Research"
sitemap: false
permalink: /research/
---
{% assign profile_photo_border_radius = "0%" %}
{% assign profile_photo_width = "30%" %}
{% assign profile_photo_margin_right = "20px" %}

# Research

The research in our lab focuses on developing programmable photonic devices for both classical and quantum information processing. For a more detailed description, you can watch a talk I recently gave at McGill University, available on [YouTube](https://www.youtube.com/watch?v=nIavaDss_LU).

---

## Developing Programmable Photonic Devices

<style>
  .responsive-image {
    width: 100%; /* Full width on smaller screens */
    max-width: 350px; /* Restricts width to 400px on larger screens */
    height: auto; /* Maintains aspect ratio */
  }

  @media (min-width: 350px) {
    .responsive-image {
      float: right; /* Floats the image to the right on medium and larger screens */
    }
  }
</style>


<div class="row">
<div class="col-sm-12 clearfix">

<img src="{{ site.url }}{{ site.baseurl }}/images/research_pics/photonics.gif" 
     class="responsive-image" 
     style="border-radius: 0px; margin-left: 2%; margin-top: 1%;margin-right:0%;"
     alt="Photonics Image">
Programmable photonic devices can reconfigurably manipuate light on a chip, enabling integrated photonics to go beyond traditional communication applications, for quantum computing and deep learning. In our lab, we are developing novel programmable photonic devices with the goal of achieving precise control over millions of parameters, which can be subsequently trained with machine learning algorithms for various information processing tasks.

Recently, [we developed an optically programmable photonic device](https://arxiv.org/abs/2402.17750), where the two-dimensional refractive-index distribution $n(x,z)$ can be reprogrammed in real-time by shaping the illumination on the chip. As shown in the figure, one can shine light in the shape of a line (onto the chip) to dynamically realize a waveguide, and even bend it, which is impossible with lithographically patterned chips. We have also recently extended this approach to a reprogrammable nonlinear waveguide, where the nonlinear optical susceptibility $\chi^{(2)}(x, z)$ can be dynamically controlled for programmable nonlinear and quantum optics.

</div>
</div>

## Quantum Information Processing with Light
<style>
  .responsive-image_v2 {
    width: 100%; /* Full width on smaller screens */
    max-width: 300px; /* Restricts width to 400px on larger screens */
    height: auto; /* Maintains aspect ratio */
  }

  @media (min-width: 300px) {
    .responsive-image_v2 {
      float: right; /* Floats the image to the right on medium and larger screens */
    }
  }
</style>



<div class="row">
<div class="col-sm-12 clearfix">

<img src="{{ site.url }}{{ site.baseurl }}/images/research_pics/quantum.png" 
     class="responsive-image_v2" 
     style="border-radius: 0px; margin-left: 2%; margin-top: 1%; margin-right:0%;"
     alt="Photonics Image">
Quantum photonic technologies offer a promising path to quantum computing and sensing, due to the large bandwidth of light and potential for room-temperature operation. However, scalability remains a key challenge. Our lab aims to address this with novel programmable photonic devices that leverage the multimode nature of light. Specifically, we focus on generating and manipulating quantum states of light in ultrashort (femtosecond) pulses (shown in [figure](https://doi.org/10.1364/OPTICA.514075)). A single beam of light, with its broad bandwidth, can support many temporal modes. Recently, we demonstrated the [programmable generation of multimode squeezed light in over 100 modes](https://arxiv.org/abs/2401.06119).

Ultrashort pulses, with their large peak intensities, also enhance the efficiency of nonlinear processes. During my PhD, I theoretically showed that ultrashort pulses in recently developed nonlinear nanophotonic platforms can reach the [single-photon nonlinearity regime](https://doi.org/10.1103/PhysRevLett.124.240503), enabling coherent non-Gaussian operations crucial for continuous-variable quantum information processing. Entering this regime pave the way for fundamentally new quantum technologies, including a room-temperature photon-resolving detector. Our lab is pursuing these directions using programmable photonic devices for quantum computing and sensing applications.

</div>
</div>

## Optical Deep Learning and Signal Processing

As deep learning becomes more prevalent in our increasingly data-driven society, the exponentially increasing energy consumption of conventional digital processors has become a critical challenge. Optical neural networks (ONNs) present a promising alternative, utilizing the low-dissipation propagation of light to process information. In our lab, we are developing ONNs capable of performing both large-scale linear operations, such as matrix-vector multiplication, and nonlinear operations.

A key philosophy of our approach is to [harness the natural physical transformations of complex optical systems for information processing](https://doi.org/10.1038/s41586-021-04223-6). During my postdoc, I developed a [hybrid physical-digital training algorithm](https://doi.org/10.1038/s41586-021-04223-6), known as physics-aware training, that enables the training of complex optical systems for deep learning. Building on this foundation, our lab is advancing this direction by building ONNs based on complex multimode nonlinear wave propagation in both space and time, to enable programmable interactions across more than 100 modes. Beyond deep learning computations, this paradigm will also be applied to signal processing tasks in datacom systems, such as channel equalization and optical packet recognition.

<style>
  .responsive-image_v3 {
    width: 100%; /* Full width on smaller screens */
    max-width: 700px; /* Restricts width to 400px on larger screens */
    height: auto; /* Maintains aspect ratio */
    float: left;
  }

  @media (min-width: 400px) {
    .responsive-image_v3 {
      float: left; /* Centers the image */
      width: 100%;
    }
  }
</style>

<div class="row">
<div class="col-sm-12 clearfix">

<img src="{{ site.url }}{{ site.baseurl }}/images/research_pics/pnn.png" 
     class="responsive-image_v3" 
     style="border-radius: 0px; float: center;"
     alt="Photonics Image">

</div>
</div>





