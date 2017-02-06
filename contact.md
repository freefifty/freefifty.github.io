---
layout: page
title: 
subtitle:
css: "/css/post.css"
---

<div id="aboutme-section">

<p class='align-center'> We'd love to hear from you!
</p>

<p>
Claim <b>your</b> free 50 hours of data science work for <b>YOUR DO-GOOD PROJECT</b>.
<br/>
<br/>
You can <span class="fa fa-envelope about-icon"></span> <a id = 'text-link-colour' href="mailto:estambolieva@gmail.com?subject=freefifty.github.io: new incoming e-mail">email us</a>  OR use this form <span class="fa fa-arrow-down about-icon"></span> :</p>

<form action="https://formspree.io/estambolieva@gmail.com" method="POST" class="form" id="contact-form">
  <div class="row">
    <div class="col-xs-6">
      <input type="email" name="_replyto" class="form-control input-lg" placeholder="Email" title="Email">
    </div>
    <div class="col-xs-6">
      <input type="text" name="name" class="form-control input-lg" placeholder="Name" title="Name">
    </div>
  </div>
  
  <br/>
  <input type="hidden" name="_subject" value="freefifty.github.io: a new incoming message">
  <textarea type="text" name="content" class="form-control input-lg" placeholder="Message" title="Message" required="required" rows="3"></textarea>
  <input type="text" name="_gotcha" style="display:none">
  <input type="hidden" name="_next" value="./message-sent" />

  <br/>
  <button type="submit" class="btn btn-lg btn-primary">Submit</button>
</form>

</div>
