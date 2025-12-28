---
layout: page
permalink: /Contact/
title: Contact
nav: true
nav_order: 5
description: 
---

---
<style>
  /* The Container: Uses Flexbox to center and space items */
  .big-social-icons {
    display: flex;
    justify-content: center; /* Centers them horizontally */
    flex-wrap: wrap;         /* Allows wrapping on mobile */
    gap: 30px;               /* Spacing between icons */
    //margin-top: 10px;        /* Space above the row */
    //margin-bottom: 10px;     /* Space below the row */
  }

  /* The Individual Links/Icons */
  .big-social-icons a {
    color: #000000 !important;  /* Force pure black by default */
    font-size: 3rem;            /* Make them huge (matches About page) */
    text-decoration: none;      /* Remove underlines */
    transition: all 0.3s ease;  /* Smooth hover animation */
    opacity: 1;                 /* Ensure they aren't faded */
  }

  /* Hover Effect: Turn Moss Green and scale up slightly */
  .big-social-icons a:hover {
    color: var(--global-theme-color) !important;  /* Your theme color */
    transform: scale(1.1);      /* Subtle pop effect */
  }
  
  /* Fix for FontAwesome/Academicons to ensure they take the size */
  .big-social-icons i {
    font-size: inherit;
  }
</style>

<div class="row mt-4">
    <div class="col-sm-8">
        <p><span style="font-size: 1.2em">Reach me at <a href = "mailto:jeremymmcmahan@gmail.com">jeremymmcmahan@gmail.com</a> or the form below! </span></p>

        <p><span style="font-size: 1.2em">You can keep up with my research and teaching here:</span></p>
        
        <div class="big-social-icons">{% include social.liquid %}</div>
    </div>
</div>

---

<div class="row mt-4">
    <div class="col-sm-8"> <h3 class="mb-4">Send me a message!</h3>
        
        <form action="https://formspree.io/f/xlgrvkyd" method="POST">
            
            <div class="form-group">
                <label for="email">Your Email</label>
                <input type="email" name="email" class="form-control" id="email" placeholder="name@example.com" required>
            </div>

            <div class="form-group mt-3">
                <label for="message">Message</label>
                <textarea name="message" class="form-control" id="message" rows="5" required></textarea>
            </div>

            <button type="submit" class="btn btn-primary mt-3">Send</button>
        </form>
        
    </div>
</div>