---
layout: project
urltitle:  "Uncertainty Estimation for Dense Prediction Tasks"
title: "Uncertainty Estimation for Dense Prediction Tasks"
categories: tutorial, computer vision, uncertainty, dense prediction, iccv, 2021
permalink: /
bibtex: true
paper: true
acknowledgements: ""
---

<br />
<div class="row">
  <div class="col-xs-12">
    <center><h1>Uncertainty Estimation for Dense Prediction Tasks</h1></center>
    <center><h2>Oct 11 - Oct 17, 2021. ICCV Tutorial, Montreal, Canada.</h2></center>
  </div>
</div>

<br />

<div class="row">
    <div class="col-xs-12">
        <p>
	  This is a half-day tutorial that aims to introduce uncertainty for dense prediction tasks. 
        </p>
    </div>
</div>

<br />

<div class="row" id="schedule">
  <div class="col-md-4 col-xs-12">
    <h2>Schedule</h2>
  </div>
</div>

<!-- Speakers -->
<div class="row" id="speakers">
  <div class="col-xs-12">
    <h2>Speakers</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-6 col-lg-3">
    <a href="http://jingzhang617.github.io/">
      <img class="people-pic" src="{{ "./static/img/people/jing.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://jingzhang617.github.io/">Jing Zhang</a>
      <h6>The Australian National University</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://sites.google.com/site/daiyuchao/">
      <img class="people-pic" src="{{ "./static/img/people/yuchao.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://sites.google.com/site/daiyuchao/">Yuchao Dai</a>
      <h6>Northwestern Polytechnical University</h6>
    </div>
  </div>
	
  <div class="col-xs-6 col-lg-3">
    <a href="http://dpfan.net/">
      <img class="people-pic" src="{{ "./static/img/people/dengping.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://dpfan.net/">Deng-Ping Fan</a>
      <h6>Inception Institute of Artificial Intelligence</h6>
    </div>
  </div>
	
  <div class="col-xs-6 col-lg-3">
    <a href="http://users.cecs.anu.edu.au/~nmb/">
      <img class="people-pic" src="{{ "./static/img/people/nick.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://users.cecs.anu.edu.au/~nmb/">Nick Barnes</a>
      <h6>The Australian National University</h6>
    </div>
  </div>
	
  <div class="col-xs-6 col-lg-3">
    <a href="https://people.csiro.au/m/p/peyman-moghadam/">
      <img class="people-pic" src="{{ "./static/img/people/peyman.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://people.csiro.au/m/p/peyman-moghadam/">Peyman Moghadam</a>
      <h6>CSIRO</h6>
    </div>
  </div>

<div class="col-xs-6 col-lg-3">
    <a href="https://cecs.anu.edu.au/people/christian-walder/">
      <img class="people-pic" src="{{ "./static/img/people/walder.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://cecs.anu.edu.au/people/christian-walder/">Christian Walder</a>
      <h6>CSIRO</h6>
    </div>
  </div>

<div class="col-xs-6 col-lg-3">
    <a href="https://www.monash.edu/engineering/mehrtashharandi/">
      <img class="people-pic" src="{{ "./static/img/people/mehrtash.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://www.monash.edu/engineering/mehrtashharandi/">Mehrtash Harandi</a>
      <h6>CSIRO</h6>
    </div>
  </div>

<hr />

<!-- Intro -->
<div class="row" id="intro">
    <div class="col-xs-12">
        <h2>Introduction</h2>
        <p>Deep neural networks are generally treated as deterministic networks, where a single prediction is produced. They intend to learn a mapping function from the input space to the output space via maximum likelihood estimation (MLE) for the weights. Deep models can also be explained as working on point estimation. A specific weights set is estimated while ignoring any uncertainty that may have in the proper weight values. This type of learning is often susceptible to overfitting. In this tutorial, we will first illustrate the importance of uncertainty estimation, especially uncertainty estimation in dense prediction tasks Then we will summarize existing uncertainty estimation methods. Due to the close connection between uncertainty estimation and model calibration, we further introduce how uncertainty estimation can be used for deep model calibration, especially for dense model calibration.

In this tutorial, we will discuss uncertainty estimation in the following topics:
1. The definition of uncertainty estimation and the widely studied solutions.
2. Typical work uncertainty estimation techniques in dense prediction tasks.
3. The implementation details and tricks for applying different uncertainty estimation solutions in various dense prediction tasks.
        </p>
    </div>
</div>
	
<!-- Links -->
<div class="row" id="links">
    <div class="col-xs-12">
        <h2>Useful Links</h2>
        <p>All the related materials can be found at: <a href="https://github.com/JingZhang617/latent_variable_models/"></a>
        </p>
    </div>
</div>


