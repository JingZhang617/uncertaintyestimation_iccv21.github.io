---
layout: project
urltitle:  "Towards Robust, Trustworthy, and Explainable Computer Vision"
title: "Towards Robust, Trustworthy, and Explainable Computer Vision"
categories: tutorial, computer vision, robustness, interpretability, trustworthy, explainability, natural language, grounding, machine learning, iccv, 2021
permalink: /
bibtex: true
paper: true
acknowledgements: ""
---

<br />
<div class="row">
  <div class="col-xs-12">
    <center><h1>Towards Robust, Trustworthy, and Explainable Computer Vision</h1></center>
    <center><h2>Oct 11 - Oct 17, 2021. ICCV Tutorial, Montreal, Canada.</h2></center>
  </div>
</div>

<br />

<div class="row">
    <div class="col-xs-12">
        <p>
	  This is a half-day tutorial that aims to introduce participants to different aspects of computer vision models beyond performance -- robustness, trustworthiness and explainability. 
        </p>
    </div>
</div>

<br />

<div class="row" id="schedule">
  <div class="col-md-4 col-xs-12">
    <h2>Schedule</h2>
  </div>
  <div class="col-md-8 col-xs-12">
      <select id="timezone-select" class="form-control"></select>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped" id="schedule-table">
    <tbody>
    <tr> <th scope="row" data-time="11:15">11:15 AM</th> <td>Opening Remarks</td></tr>
    <tr> <th scope="row" data-time="11:30">11:30 AM</th> <td>Talk 1: "Explaining Model Decisions and Fixing Them via Human Feedback" by Ramprasaath R. Selvaraju </td></tr>
    <tr> <th scope="row" data-time="12:15">12:15 PM</th> <td>Talk 2: "Characterizing Bias and Developing Trustworthy AI Models" by Sara Hooker</td></tr>
    <tr> <th scope="row" data-time="13:00">01:00 PM</th> <td>Break</td></tr>
    <tr> <th scope="row" data-time="13:30">01:30 PM</th> <td>Talk 3: "Interacting with Deep AI Models" by Bolei Zhou</td> </tr>
    <tr> <th scope="row" data-time="14:15">02:15 PM</th> <td>Talk 4: "Adversarially Robust Models as Visual Priors" by Aleksander Madry</td></tr>
    <tr> <th scope="row" data-time="15:00">03:00 PM</th> <td>Panel Discussion</td> </tr>
    <tr> <th scope="row" data-time="15:30">03:30 PM</th> <td>Closing Remark</td> </tr>
    </tbody>
    </table>
  </div>
</div>

<hr />

<!-- Speakers -->
<div class="row" id="speakers">
  <div class="col-xs-12">
    <h2>Speakers</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-6 col-lg-3">
    <a href="http://ramprs.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/ram.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://ramprs.github.io/">Ramprasaath R. Selvaraju</a>
      <h6>Salesforce Research</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="http://bzhou.ie.cuhk.edu.hk/">
      <img class="people-pic" src="{{ "/static/img/people/bolei.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://bzhou.ie.cuhk.edu.hk/">Bolei Zhou</a>
      <h6>Chinese University of Hong Kong</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://people.csail.mit.edu/madry/">
      <img class="people-pic" src="{{ "/static/img/people/madry.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://people.csail.mit.edu/madry/">Aleksander Madry</a>
      <h6>MIT</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="https://www.sarahooker.me/">
      <img class="people-pic" src="{{ "/static/img/people/sara.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://www.sarahooker.me/">Sara Hooker</a>
      <h6>Google Research</h6>
    </div>
  </div>
</div>

<hr />

<!-- Organizers -->
<div class="row" id="organizers">
  <div class="col-xs-12">
    <h2>Organizers</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-6 col-lg-3">
    <a href="http://ramprs.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/ram.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://ramprs.github.io/">Ramprasaath R. Selvaraju</a>
      <h6>Salesforce Research</h6>
    </div>
  </div>
  <div class="col-xs-6 col-lg-3">
    <a href="http://bzhou.ie.cuhk.edu.hk/">
      <img class="people-pic" src="{{ "/static/img/people/bolei.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://bzhou.ie.cuhk.edu.hk/">Bolei Zhou</a>
      <h6>Chinese University of Hong Kong</h6>
    </div>
  </div>
</div>

<hr />
<!-- Intro -->
<div class="row" id="intro">
    <div class="col-xs-12">
        <h2>Introduction</h2>
        <p>Convolutional Neural Networks (CNNs) and other deep networks have enabled unprecedented breakthroughs in a variety of computer vision tasks, from image classification to object detection, semantic segmentation, image captioning, visual question answering, and visual dialog. While these models enable superior performance, their lack of decomposability into individually intuitive components makes them hard to interpret. Consequently, when today’s intelligent systems fail, they often fail spectacularly disgracefully without warning or explanation, leaving a user staring at an incoherent output, wondering why the system did what it did. In order to be able to build trust in intelligent systems and move towards their meaningful integration into our everyday lives, we must build `transparent' models that have the ability to explain why they predict what they predict. </p>
        <p>This tutorial will introduce participants to different aspects of computer vision models beyond performance. Ramprasaath R. Selvaraju will focus on explainable-AI methodologies and how understanding the decision process helps fixing various characteristics of the model. Sara Hooker will address the trustworthiness and the social impact of vision models. Bolei Zhou will focus on the interactive aspect of dissected vision models and its implication to visual editing applications. Aleksander Madry will focus on the robustness of vision models. Therefore, in this tutorial there will be a unification of different perspectives beyond test-set performance that are just as important to have in vision models. </p>
    </div>
</div>

<hr />

<!-- Speaker Relevance -->
<div class="row" id="speaker">
    <div class="col-xs-12">
        <h2>Speaker Relevance</h2>
        <p>The tutorial lectures will be given by several well-known researchers specialized in computer vision and the topic relevant to explainability, fairness, generalization, robustness of visual models. 
For example, Dr. Selvaraju has done work on generating visual explanations for decisions emanating from any deep network-- in order to debug and diagnose network errors, enable knowledge transfer between humans and AI, and correct unwanted biases that may be learned by a network during training. Prof. Zhou has done several works on the visualization and interpretation of the semantic units of deep neural networks for both discriminative and generative models. Prof. Madry has done much work on identifying biases learned by deep models, introduced several benchmarks to evaluate the robustness of vision models, and adversarial machine learning.
Sara Hooker has done work on benchmarking interpretability techniques and understanding the biases introduced during network compression in order to build fair and trustworthy AI systems. </p>
        
<p>We believe that this tutorial will give the vision community not only an educational crash course on explainable, robust and trustworthy AI, but also inspire deeper thinking about the visual models we are training. </p>
    </div>
</div>


