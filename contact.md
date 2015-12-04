---
layout: page
title: Contact
permalink: /contact/
order: 4
---



<div class="container-fluid">
  <div class="row">
    <div class="col-md-12 icons">
      <img src="{{ '/img/mail.png' | prepend: site.url }}" data-toggle="tooltip" data-placement="right" title="Contactez-moi !">
    </div>
  </div>
  <div class="row header-page">
    <div class="col-md-12">
      <p>
        Quels que soient vos besoins ou vos objectifs, n'hésitez pas à me contacter et nous verrons comment je peux vous accompagner dans vos projets. <a href="mailto:amandine.dupays@gmail.com?subject=Prise de contact">Envoyez moi un email</a> ou bien remplissez le formulaire ci-dessous et je ne tarderais pas à vous répondre !
      </p>
    </div>  
  </div>    
  <div class="row">
    <div class="col-md-12">  
    <form action="//formspree.io/amandine.dupays@gmail.com" role="form" method="POST">
      <div class="form-group">
        <label for="name">Votre nom *</label>
        <input type="text" name="name" class="form-control" required="required">
      </div>
      <div class="form-group">
        <label for="_replyto">Votre adresse email *</label>
        <input type="email" name="_replyto" class="form-control" required="required">
      </div>
      <div class="form-group">
        <label for="message">En quoi puis-je vous aider ? *</label>
        <textarea name="body" class="form-control" rows="4" width="100%" required="required"></textarea>
      </div>
      <div>
        <input type="hidden" name="_next" value="//adupays.github.io">
        <input type="submit" class="btn btn-lg btn-primary" value="Envoyer">
      </div>
    </form>
    </div>  
  </div>
</div>