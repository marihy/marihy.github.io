---
layout: default
title: titre de page
---
{% include slider.html %}
{% for site in site.post }

{{post.title}




<!-- Page Content -->
<div class="container">
    <div class="row">
        <div class="col-lg-12">
            <h1 class="page-header">
                 Bienvenue, Welcome, Willkommen
            </h1>
        </div>
        {% for post in paginator.posts %}
            <div class="col-md-4">
                <div class="panel panel-default">
                   <div class="panel-heading">
                       <h4><i class="fa fa-fw fa-check"></i>{{ post.title }}</h4>
                   </div>
                   <div class="panel-body">
                     <p>{{ post.content }}</p>
                     <a href="#" class="btn btn-default">Learn More</a>
                   </div>
                </div>
            </div>
        {% endfor %}
    </div> 
    <div class="row">
        <div class="col-lg-12">
            <h2 class="page-header">Mon Portfolio</h2>
        </div>
            
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="visite" src="images/Folio_pizza.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="cv" src="images/Folio_cv.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="bomba" src="images/Folio_bomba.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="cocci" src="images/Folio_cocci.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="apertura" src="images/Folio_apertura.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="pac" src="images/Folio_pac.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="3d" src="images/Folio_3d1.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="3d2" src="images/Folio_3d2.jpg"/>
        </div>
           
    </div>
</div>

