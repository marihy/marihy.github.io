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
            <h2 class="page-header">Mes réalisations</h2>
        </div>
<!-- j'aurai du créer un dossier qui contient les images des projets mais je n'ai pas trouvé le bouton pour créer un nouveau dossier directement sur github sans passer par un terminal, mais l'intention y était -->            
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="visite" src="images/visite.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="portrait" src="images/potrait.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="affiches" src="images/affiches.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="site " src="images/paulilles.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="bar" src="images/barcom.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="lancre" src="images/lancre.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="illu" src="images/illu.jpg"/>
        </div>
        <div class="col-md-4 col-sm-6">
            <img class="img-responsive img-portfolio img-hover" alt="projet" src="images/projet.jpg"/>
        </div>
           
    </div>
</div>

