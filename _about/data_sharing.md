---
title:  "Population Imaging: Data Sharing"
image: images/data_sharing.png
excerpt: "I am in charge of the PIWS project. It allows to assemble and serve the data of major European/international projects in population imaging for big-data analyzes. PIWS relies on CubicWeb, a semantic web software developed by the French company Logilab."
collection: about
reference: https://www.frontiersin.org/articles/10.3389/fninf.2017.00018/full
code: https://github.com/neurospin/piws
---


<div class="portfolio-grid">
  <figure class="item">
    <a class="figure-item">
      <img src="{{'images/data_sharing.png' | relative_url}}" alt="">
      <div>
        <h5 class="name">Architecture of the data sharing service (DSS)</h5>
        <small>CubicWeb</small>
        <i class="fa fa-reddit-alien"></i>
      </div>
    </a>
  </figure>
  <figure class="item">
    <a class="figure-item">
      <img src="{{'images/data_sharing_schema.jpg' | relative_url}}" alt="">
      <div>
        <h5 class="name">A snippet of the schema used in a publication DSS</h5>
        <small>CubicWeb</small>
        <i class="fa fa-reddit-alien"></i>
      </div>
    </a>
  </figure>
  <figure class="item">
    <a class="figure-item">
      <img src="{{'images/data_sharing_upload.jpg' | relative_url}}" alt="">
      <div>
        <h5 class="name">Illustration of the upload process</h5>
        <small>CubicWeb</small>
        <i class="fa fa-reddit-alien"></i>
      </div>
    </a>
  </figure>
</div>

In neurosciences or psychiatry, the emergence of large multi-center population imaging studies raises numerous technological challenges. From distributed data collection, across different institutions and countries, to final data publication service, one must handle the massive, heterogeneous, and complex data from genetics, imaging, demographics, or clinical scores. These data must be both efficiently obtained and downloadable. We present a Python solution, based on the CubicWeb open-source semantic framework, aimed at building population imaging study repositories. In addition, we focus on the tools developed around this framework to overcome the challenges associated with data sharing and collaborative requirements. We describe a set of three highly adaptive web services that transform the CubicWeb framework into a (1) multi-center upload platform, (2) collaborative quality assessment platform, and (3) publication platform endowed with massive-download capabilities. Two major European projects, IMAGEN and EU-AIMS, are currently supported by the described framework. We also present a Python package that enables end users to remotely query neuroimaging, genetics, and clinical data from scripts.
