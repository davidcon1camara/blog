---
title: "Contact"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Por favor envianos un mensaje {{site.name}}. Te responderemos pronto</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Nombre*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Tu mensaje*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>
