---
title: My page
layout: default
---
<div class="container-fluid header">
    <div class="container justify-content-center">
        <div class="row justify-content-center">
            <img src="images/FotoLuisDanielBenavidesNavarro.jpg" alt="Smiley face" height="200">
            <br/>
        </div>
        <div class="row justify-content-center">
              <h2>Luis Daniel Benavides Navarro, Ph.D.</h2>
        </div>
        <div class="row justify-content-center">
              <h5>Programmer, Scientist, Information Systems Architect</h5>
        </div>
        <div class="row justify-content-center">
            <h3 class="white-link-text-on-box">{% include navigation/socialmedianav.html %}</h3>    
        </div>
</div>
</div>

<div class="container">
<br/>


{% include maincontent/bio.html %}

{% include maincontent/contactinfo.html %}

<div id="projects">
    <h3>
        <a id="projects" class="anchor" href="#projects" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Projects</h3>

  <ul>    
  <li ><p></p><a href="https://www.cap4city.eu/home/" class="btn btn btn-link" data-show-count="false">Strengthening Governance Capacity for Smart Sustainable Cities
      (CAP4CITY).</a>
      <br/>Co-funded by the ERASMUS+ Programme of the European Union.<p/>
</li>
</ul>
</div>

<div id="events">
    <h3>
        <a class="anchor" href="#events" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Events</h3>

  <ul>  

  <li ><p></p><a href="/events/ArqIS2021/index.html" class="btn btn btn-link" data-show-count="false">Digital Transformation and Enterprise Architecture. Dec. 10 2021 (In Spanish).</a>
   <p/></li>	  

  <li ><p></p><a href="/events/cloudnative2021/index.html" class="btn btn btn-link" data-show-count="false">Cloud Native Architectures 2021. May 2021 (In Spanish).</a>
   <p/></li>

  <li ><p></p><a href="/events/q2020/index.html" class="btn btn btn-link" data-show-count="false">First workshop on Quantum Computing. June 2020 (In Spanish).</a>
   <p/></li>

  <li ><p></p><a href="/events/ArqIS2020/index.html" class="btn btn btn-link" data-show-count="false">Digital Transformation and Enterprise Architecture. May, 2020 (In Spanish).</a>
   <p/></li>
</ul>
</div>  

<div id="courses">   
    <h3>
        <a id="contact" class="anchor" href="#contact" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Courses</h3>

<ul class="list-group list-group-flush">    
  <li class="list-group-item"><a href="./courses/Quantum/quantumc.html" class="btn btn btn-link" data-show-count="false">Quantum Computing 2020-08 (in spanish)</a></li>
  <li class="list-group-item"><a href="./courses/AREM/arem.html" class="btn btn-link" data-show-count="false">Enterprise Architecture 2020-08 (in spanish)</a></li>
  <li class="list-group-item"><a href="./courses/ARSW/arsw.html" class="btn btn-link" data-show-count="false">Arquitectura de software 2020-06 (in spanish)</a></li>
</ul>
</div>


<h3>
<a id="publications" class="anchor" href="#publications" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Publications</h3>

{% include maincontent/publications.html %}

<!--
You can use HTML elements in Markdown, such as the comment element, and they won't
be affected by a markdown parser. However, if you create an HTML element in your
markdown file, you cannot use markdown syntax within that element's contents.
-->
