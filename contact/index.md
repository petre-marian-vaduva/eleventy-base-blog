---
layout: layouts/post.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 3
---
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>
<div class="container">
    <div class="row">
        <form name="contact" method="POST" data-netlify="true">
            <p>
                <label class="form-label">Your Name:</label>
                <input type="text" name="name" required class="form-control" />
            </p>
            <p>
                <label class="form-label">Your Email:</label>
                <input type="email" name="email" required class="form-control" />
            </p>
            <p>
                <label class="form-label">Your Role: </label>
                <select name="role[]" class="form-select" required>
                    <option value="leader">Leader</option>
                    <option value="follower">Follower</option>
                </select>
            </p>
            <p>
                <label class="form-label">Message:</label>
                <textarea name="message" class="form-control"></textarea>
            </p>
            <p>
                <button type="submit" class="btn btn-primary">Send</button>
            </p>
        </form>
    </div>
</div>
<div class="tacbox">
  <input id="checkbox" type="checkbox" />
  <label for="checkbox"> I agree to these <a href="#">Terms and Conditions</a>.</label>
</div>
<footer class="bg-light text-center text-lg-start">
  <div class="text-center p-3">
    © 2021 Copyright:
    <a class="text-dark" href="https://www.linkedin.com/in/petre-marian-vaduva-9b4b46201/">Petre-Marian Vaduva</a>
  </div>
</footer>