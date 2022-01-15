---
title: "Contact"
permalink: "/contact.html"
---

<div class="alert alert-danger" role="alert">
  <h4 class="alert-heading">Warning</h4>
  <p>Masih dalam tahap pengemebnagan.</p>
  <hr>
  <p class="mb-0">Saat ini kontak sedang tidak bisa dipakai.</p>
</div>
<!-- <form action="https://formspree.io/{{site.email}}" method="POST">    -->
<form action="#" method="POST">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>
