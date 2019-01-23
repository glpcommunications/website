---
title: Contact Us
image: ''
date: 2017-10-23 07:32:18
---
{% raw %}
<form name="contact" netlify action="/thanks">
  <div class="form-group">
    <label for="name">Your name</label>
    <input type="text" class="form-control" id="name" name="name" placeholder="Enter your name">
  </div>
  <div class="form-group">
    <label for="email">Email address</label>
    <input type="email" class="form-control" id="email" name="email" aria-describedby="emailHelp" placeholder="Enter email">
    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  <div class="form-group">
    <label for="reason">What can we help you with?</label>
    <select class="form-control" id="reason" name="reason">
      <option value="Service Call" selected>Service Call</option>
      <option value="Sales">Sales</option>
      <option value="Something else">Something else</option>
    </select>
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea class="form-control" id="message" rows="3" name="message"></textarea>
  </div>
  <div data-netlify-recaptcha="true"></div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
{% endraw %}