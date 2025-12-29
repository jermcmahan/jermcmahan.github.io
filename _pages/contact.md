---
layout: page
permalink: /Contact/
title: Contact
nav: true
nav_order: 5
description: 
---

<style>
  /* =========================================
     CONTACT PAGE STYLING
     ========================================= */
  /* Force the default page title to center */
  .post-title {
    text-align: center;
  }

  /* 1. SOCIAL ICONS (Refined) */
  .big-social-icons {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 30px;
    margin-top: 20px;
    margin-bottom: 40px; /* More breathing room below icons */
  }

  .big-social-icons a {
    color: #333 !important;     /* Softer dark grey (less harsh than #000) */
    font-size: 2.5rem;          /* Slightly refined size */
    text-decoration: none;
    transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
  }

  .big-social-icons a:hover {
    color: var(--global-theme-color) !important;
    transform: translateY(-4px); /* Lift effect matching your cards */
  }
  
  .big-social-icons i { font-size: inherit; }


  /* 2. THE CONTACT CARD (Matches Research/Pubs) */
  .contact-card {
    background-color: #ffffff;
    padding: 40px;              /* Generous padding */
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.03), 
                0 1px 3px rgba(0, 0, 0, 0.05);
    border: 1px solid rgba(0,0,0,0.05);
  }

  /* 3. THEME-STYLED FORM INPUTS */
  /* Remove default Bootstrap Blue glow and use Theme Color */
  .form-control {
    background-color: #f9f9f9;  /* Light grey background for fields */
    border: 1px solid #eee;
    padding: 15px;              /* Taller, more comfortable inputs */
    border-radius: 8px;
  }

  .form-control:focus {
    background-color: #fff;
    border-color: var(--global-theme-color);
    box-shadow: 0 0 0 2px rgba(0,0,0,0.05); /* Subtle ring instead of blue glare */
  }
  
  /* Label styling */
  label {
    font-weight: 600;
    font-size: 0.9rem;
    color: #555;
    margin-bottom: 8px;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  /* 4. THEME BUTTON */
  .btn-theme-submit {
    background-color: var(--global-theme-color);
    color: #fff;
    padding: 12px 30px;
    border-radius: 30px;        /* Pill shape */
    font-weight: bold;
    border: none;
    transition: all 0.3s ease;
    width: 100%;                /* Full width on mobile */
  }

  .btn-theme-submit:hover {
    background-color: #333;     /* Darken on hover */
    color: #fff;
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  }

  /* Desktop tweak: Button goes back to normal width */
  @media (min-width: 768px) {
    .btn-theme-submit { width: auto; }
  }
</style>

<div class="row mt-4">
    <div class="col-md-8 mx-auto text-center">
        
        <p style="font-size: 1.3rem; line-height: 1.6; color: #555;">
            Reach me at <a href="mailto:jeremymmcmahan@gmail.com" style="color: var(--global-theme-color); font-weight: bold; text-decoration: none;">jeremymmcmahan@gmail.com</a><br>
            or use the form below.
        </p>

        <div class="big-social-icons">
            {% include social.liquid %}
        </div>

    </div>
</div>

<div class="row">
    <div class="col-md-8 mx-auto">
        
        <div class="contact-card">
            <h3 class="mb-4" style="font-weight: bold; color: #333;">Send a message</h3>
            
            <form action="https://formspree.io/f/xlgrvkyd" method="POST">
                
                <div class="form-group">
                    <label for="email">Your Email</label>
                    <input type="email" name="email" class="form-control" id="email" placeholder="name@example.com" required>
                </div>

                <div class="form-group mt-4">
                    <label for="message">Message</label>
                    <textarea name="message" class="form-control" id="message" rows="6" required></textarea>
                </div>

                <div class="text-right mt-4">
                    <button type="submit" class="btn btn-theme-submit">
                        <i class="fas fa-paper-plane mr-2"></i> Send Message
                    </button>
                </div>
                
            </form>
        </div>

    </div>
</div>