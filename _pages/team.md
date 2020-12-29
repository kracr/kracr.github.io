---
title: "KRaCR Lab - Team"
layout: gridlay
excerpt: "KRaCR Lab: Team members"
sitemap: false
permalink: /team/
---
<!-- Trigger/Open The Modal -->

<!-- The Modal -->

# Group Members
### Faculty
{% assign number_printed = 0 %}
{% for member in site.data.lab_members.faculty_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo  }}" class="responsive" style="float: left" />

  <h4 style="color:purple;">{{ member.name }}</h4>
  <i>{{ member.info }}
    <br> 
    <a style="color:purple">email: </a>
    {{ member.email}}<br><a style="color:purple;">Research Interests: </a>
    {{ member.research_interest }}
    <br> 
    <a style="padding-left: 2px;" href = "https://github.com/kracr/" target=_blank aria-label="GitHub"><i class="fab fa-github-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="LinkedIn"><i class="fab fa-linkedin fa-2x" style="color:#5b4785;"></i></a> 
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="Twitter"><i class="fab fa-twitter-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "mailto:kracr@iiitd.ac.in" target= _blank aria-label ="Mail"><i class="fas fa-envelope-square fa-2x" style="color:#5b4785;"></i></a>
  </i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}



### Ph. D Students
{% assign number_printed = 0 %}
{% for member in site.data.lab_members.PhD_Students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="responsive" style="float: left" />
<h4>{{ member.name }}</h4>
  <i>{{ member.info }}
    <br> 
    <a style="color:purple">email: </a>
    {{ member.email}}<br><a style="color:purple;">Research Interests: </a>
    {{ member.research_interest }}
    <br> 
    <a style="padding-left: 2px;" href = "https://github.com/kracr/" target=_blank aria-label="GitHub"><i class="fab fa-github-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="LinkedIn"><i class="fab fa-linkedin fa-2x" style="color:#5b4785;"></i></a> 
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="Twitter"><i class="fab fa-twitter-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "mailto:kracr@iiitd.ac.in" target= _blank aria-label ="Mail"><i class="fas fa-envelope-square fa-2x" style="color:#5b4785;"></i></a>
  </i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}




### Masters Students
{% assign number_printed = 0 %}
{% for member in site.data.lab_members.Master_Students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="responsive"  style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}
    <br> 
    <a style="color:purple">email: </a>
    {{ member.email}}<br><a style="color:purple;">Research Interests: </a>
    {{ member.research_interest }}
    <br> 
    <a style="padding-left: 2px;" href = "https://github.com/kracr/" target=_blank aria-label="GitHub"><i class="fab fa-github-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="LinkedIn"><i class="fab fa-linkedin fa-2x" style="color:#5b4785;"></i></a> 
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="Twitter"><i class="fab fa-twitter-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "mailto:kracr@iiitd.ac.in" target= _blank aria-label ="Mail"><i class="fas fa-envelope-square fa-2x" style="color:#5b4785;"></i></a>
  </i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


### Bachelors Students
{% assign number_printed = 0 %}
{% for member in site.data.lab_members.Bachelor_Students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="responsive" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}
    <br> 
    <a style="color:purple">email: </a>
    {{ member.email}}<br><a style="color:purple;">Research Interests: </a>
    {{ member.research_interest }}
    <br> 
    <a style="padding-left: 2px;" href = "https://github.com/kracr/" target=_blank aria-label="GitHub"><i class="fab fa-github-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="LinkedIn"><i class="fab fa-linkedin fa-2x" style="color:#5b4785;"></i></a> 
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="Twitter"><i class="fab fa-twitter-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "mailto:kracr@iiitd.ac.in" target= _blank aria-label ="Mail"><i class="fas fa-envelope-square fa-2x" style="color:#5b4785;"></i></a>
  </i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

### Research Assistants/ Interns
{% assign number_printed = 0 %}
{% for member in site.data.lab_members.RA_Interns %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="responsive" style="float: left" />
  <button id="myBtn">{{ member.name }}</button>
  <div id="myModal" class="modal">

  <!-- Modal content -->
  <div class="modal-content">
   <span class="close">
    &times;
   </span>
  {{ member.name }}  
  </div>
</div>
  <i>{{ member.info }}
    <br> 
    <a style="color:purple">email: </a>
    {{ member.email}}<br><a style="color:purple;">Research Interests: </a>
    {{ member.research_interest }}
    <br> 
    <a style="padding-left: 2px;" href = "https://github.com/kracr/" target=_blank aria-label="GitHub"><i class="fab fa-github-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="LinkedIn"><i class="fab fa-linkedin fa-2x" style="color:#5b4785;"></i></a> 
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="Twitter"><i class="fab fa-twitter-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "mailto:kracr@iiitd.ac.in" target= _blank aria-label ="Mail"><i class="fas fa-envelope-square fa-2x" style="color:#5b4785;"></i></a>
  </i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

### Alumni
{% assign number_printed = 0 %}
{% for member in site.data.lab_members.Alumni %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">

<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="responsive"  style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}
    <br> 
    <a style="color:purple">email: </a>
    {{ member.email}}<br><a style="color:purple;">Research Interests: </a>
    {{ member.research_interest }}
    <br> 
    <a style="padding-left: 2px;" href = "https://github.com/kracr/" target=_blank aria-label="GitHub"><i class="fab fa-github-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="LinkedIn"><i class="fab fa-linkedin fa-2x" style="color:#5b4785;"></i></a> 
    <a style="padding-left: 2px;" href = "" target= _blank aria-label="Twitter"><i class="fab fa-twitter-square fa-2x" style="color:#5b4785;"></i></a>
    <a style="padding-left: 2px;" href = "mailto:kracr@iiitd.ac.in" target= _blank aria-label ="Mail"><i class="fas fa-envelope-square fa-2x" style="color:#5b4785;"></i></a>
  </i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<script>
// Get the modal
var modal = document.getElementById("myModal");

// Get the button that opens the modal
var btn = document.getElementById("myBtn");

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks the button, open the modal 
btn.onclick = function() {
  modal.style.display = "block";
}

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
  modal.style.display = "none";
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>