---
title: "تماس با ما"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">لطفا پیام خود را در فرم زیر وارد کنید. در اولین فرصت به آن پاسخ خواهیم داد</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="نام*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="ایمیل*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="پیام*" required></textarea>    
<input class="btn btn-success" type="submit" value="ارسال">
</form>