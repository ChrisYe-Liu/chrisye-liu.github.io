---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-item {
  display: flow-root;
  margin: 25px 0;
}

.research-image {
  float: left;
  width: 320px;
  height: auto;
  margin: 0 24px 12px 0;
  padding: 6px;
  border: 1px solid #dddddd;
  border-radius: 4px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
  box-sizing: content-box;
}

.research-content {
  min-width: 0;
}

.research-content h4 {
  margin-top: 0;
  margin-bottom: 10px;
  color: blue;
  font-size: 1rem;
}

.research-content p {
  margin-top: 0;
  text-align: justify;
}

.research-venue {
  color: red;
  font-weight: bold;
}

.research-divider {
  border: none;
  border-top: 1px solid #555555;
  margin: 25px 0;
}

/* Mobile devices */
@media (max-width: 768px) {
  .research-image {
    float: none;
    display: block;
    width: 100%;
    max-width: 320px;
    height: auto;
    margin: 0 auto 15px;
    box-sizing: border-box;
  }
}
</style>


<hr class="research-divider">

<div class="research-item">

  <img
    src="/images/research/wpt.png"
    alt="Dependable Wireless Power Transfer for Batteryless IoT"
    class="research-image"
  >

  <div class="research-content">

    <h4><b>Dependable Wireless Power Transfer for Batteryless IoT</b></h4>

    <p>
      Wireless power transfer (WPT) is a promising technology for powering
      batteryless and energy-autonomous IoT devices. However, reliable energy
      delivery remains challenging due to dynamic wireless channels,
      asynchronous power transmissions, and the nonlinear behavior of
      energy-harvesting circuits. Counterintuitively, adding more power sources
      may not always improve energy availability and can even cause energy black
      holes, significantly degrading system performance. To address these
      challenges, we investigate dependable WPT, with a focus on understanding
      and mitigating energy unreliability through analytical modeling, system
      design, and experimental evaluation, ultimately enabling predictable and
      reliable energy delivery for batteryless IoT systems.
   
      The related papers have been published in
      <span class="research-venue">IEEE WCM 2022</span>
      <a href="https://chrisye-liu.github.io/files/ye22understandingWPT.pdf"
         target="_blank">[PDF]</a>,
      <span class="research-venue">IEEE WCM 2024</span>
      <a href="https://chrisye-liu.github.io/files/ye24wpt.pdf"
         target="_blank">[PDF]</a>,
      <span class="research-venue">IEEE WCM 2025</span>
      <a href="https://chrisye-liu.github.io/files/ye25wcm.pdf"
         target="_blank">[PDF]</a>,
      <span class="research-venue">IEEE TMC 2025</span>
      <a href="https://chrisye-liu.github.io/files/ye25tmc.pdf"
         target="_blank">[PDF]</a>,
      <span class="research-venue">IEEE TII 2026</span>
      <a href="https://chrisye-liu.github.io/files/ye263dwpt.pdf"
         target="_blank">[PDF]</a>,
      and
      <span class="research-venue">IEEE JSAC 2026</span>
      <a href="https://chrisye-liu.github.io/files/ye26JSAC.pdf"
         target="_blank">[PDF]</a>.
    </p>

  </div>
</div>


<hr class="research-divider">


<div class="research-item">

  <img
    src="/images/research/chirpbox.jpg"
    alt="ChirpBox: An Infrastructure-Less LoRa Testbed"
    class="research-image"
  >

  <div class="research-content">

    <h4><b>ChirpBox: An Infrastructure-Less LoRa Testbed</b></h4>

    <p>
      A key obstacle hindering the development of large-scale LoRa testbeds
      outdoors is the lack of a backbone infrastructure allowing them to
      communicate with the nodes and supply them with power easily. As a result,
      many LoRa installations are deployed indoors or only support a handful of
      outdoor devices, which does not allow proper testing. To bridge this gap,
      we built ChirpBox, an infrastructure-less LoRa testbed.
   
      ChirpBox is <b>open source</b>, and the
      <span class="research-venue">tutorial website</span>
      can be found at
      <a href="https://chirpbox.github.io/" target="_blank">[Link]</a>.
      The related papers have been published in
      <span class="research-venue">EWSN 2021</span>
      <a href="https://chrisye-liu.github.io/files/pei21chirpbox.pdf"
         target="_blank">[PDF]</a>,
      <span class="research-venue">SenSys-DATA 2021</span>
      <a href="https://chrisye-liu.github.io/files/pei21loradataset.pdf"
         target="_blank">[PDF]</a>,
      <span class="research-venue">IPSN 2022</span>
      <a href="https://chrisye-liu.github.io/files/yang22emu.pdf"
         target="_blank">[PDF]</a>,
      and
      <span class="research-venue">IEEE TCCN 2025</span>
      <a href="https://chrisye-liu.github.io/files/ye2024chirpbox.pdf"
         target="_blank">[PDF]</a>.
    </p>

  </div>
</div>

<hr class="research-divider">


<div class="research-item">

  <img
    src="/images/research/noisemapping.jpg"
    alt="Dynamic Mapping of Environmental Noise with IoT"
    class="research-image"
  >

  <div class="research-content">

    <h4><b>Dynamic Mapping of Environmental Noise with IoT</b></h4>

    <p>
      Environmental noise poses a growing threat to public health and sustainable
      urban development. However, conventional noise-mapping approaches largely
      rely on costly manual measurements or computational models that provide
      coarse-grained and often static estimates. To address this gap, we investigate
      DAMPEN, a versatile wireless acoustic sensor network for real-time,
      fine-grained, and large-scale environmental noise mapping. DAMPEN integrates
      acoustic sensor networks, mobile crowdsensing, edge鈥揷loud computing, and
      AI-assisted analytics to support dynamic visualization, noise-source
      recognition, personal exposure assessment, and data-driven noise mitigation.
      Our research further explores dependable multimedia transmission,
      energy-efficient and event-triggered sensing, and defenses against inaudible
      sound attacks. The long-term goal is to build a low-cost, scalable,
      easy-to-maintain, sustainable, dependable, and trustworthy sensing
      infrastructure for smart cities and industrial environments. Related papers
      have been published in <span class="research-venue">IEEE Network 2020</span>
      <a href="https://chrisye-liu.github.io/files/ye20noisemap.pdf"
         target="_blank" rel="noopener noreferrer">[Paper]</a>
      and <span class="research-venue">IEEE Industrial Electronics Magazine 2021</span>
      <a href="https://chrisye-liu.github.io/files/ye21industrialnoise.pdf"
         target="_blank" rel="noopener noreferrer">[Paper]</a>.
    </p>

  </div>
</div>


<hr class="research-divider">


<div class="research-item">

  <img
    src="/images/research/ewsncompetition.jpg"
    alt="Dependable Wireless Network Protocols for IoT"
    class="research-image"
  >

  <div class="research-content">

    <h4><b>Dependable Wireless Network Protocols for IoT</b></h4>

    <p>
      Wireless networking in the Internet of Things is challenging because a
      massive number of devices in a relatively small region need to be
      interconnected. Particularly, the CSMA/CA operation is not a viable
      solution since a dense network leads to high channel contention.
      Moreover, external radio interference can undermine network dependability.
      Thus, we proposed and implemented protocols to address these challenges.
      This research work was supported by NSFC.
  
      The related papers have been published in
      <span class="research-venue">PPNA 2018</span>
      <a href="https://chrisye-liu.github.io/files/ye18crosslayer.pdf"
         target="_blank">[PDF]</a>,
      <span class="research-venue">INFOCOM 2020</span>
      <a href="https://chrisye-liu.github.io/files/xiao20harmony.pdf"
         target="_blank">[PDF]</a>,
      and
      <span class="research-venue">ICNP 2020</span>
      <a href="https://chrisye-liu.github.io/files/michael20ct.pdf"
         target="_blank">[PDF]</a>.
    </p>

  </div>
</div>


<hr class="research-divider">


<div class="research-item">

  <img
    src="/images/research/ecovibe.jpg"
    alt="On-Demand Railway Bridge Structural Health Monitoring"
    class="research-image"
  >

  <div class="research-content">

    <h4><b>On-Demand Railway Bridge Structural Health Monitoring</b></h4>

    <p>
      Over 73,000 railway bridges are older than 110 years in Europe.
      The IoT is promising for railway bridge health monitoring. However,
      existing energy-efficient approaches, such as duty cycling and energy
      harvesting, face challenges in this application due to the unpredictability
      of train passages and insufficient ambient energy around bridges.
      We proposed EcoVibe, the first railway bridge monitoring IoT system that
      provides on-demand sensing with near-zero idle energy dissipation.
      This research work was supported by VINNOVA.
  
      The related papers have been published in
      <span class="research-venue">IEEE ComMag 2016</span>
      <a href="https://chrisye-liu.github.io/files/ye16EcoSense.pdf"
         target="_blank">[PDF]</a>
      and
      <span class="research-venue">IEEE IoTJ 2019</span>
      <a href="https://chrisye-liu.github.io/files/ye19EcoVibe.pdf"
         target="_blank">[PDF]</a>.
    </p>

  </div>
</div>


<hr class="research-divider">


<div class="research-item">

  <img
    src="/images/research/water.jpg"
    alt="Harvest Energy from Water: A Green Water Quality Sensing System"
    class="research-image"
  >

  <div class="research-content">

    <h4><b>Harvest Energy from Water: A Green Water Quality Sensing System</b></h4>

    <p>
      Water quality data is crucial and valuable, but its acquisition is not
      always trivial. A promising solution is to distribute a wireless sensor
      network in water to measure and collect the data. However, a drawback
      exists in that the system's batteries must be replaced or recharged after
      being exhausted. To mitigate this issue, we designed a self-sustained and
      on-demand water quality sensing system powered by renewable bioenergy from
      microbial fuel cells. This research work was supported by the Exploratory
      Advanced Research Program of FHWA.
  
      The related papers have been published in
      <span class="research-venue">IEEE ComMag 2016</span>
      <a href="https://chrisye-liu.github.io/files/ye16EcoSense.pdf"
         target="_blank">[PDF]</a>
      and
      <span class="research-venue">ACM TECS 2017</span>
      <a href="https://chrisye-liu.github.io/files/qi17watersensing.pdf"
         target="_blank">[PDF]</a>.
    </p>

  </div>
</div>


<hr class="research-divider">