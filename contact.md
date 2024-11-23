---
layout: page
title: "Contact Us"
description: Contact Information.
permalink: /contact/
nav: contact
verify: yes
---
<div class="container-fluid bg-offblack leaves pt-md-0 py-sm-0 g-0">
    <div class="row g-0 text-white pb-5">
        <div class="col-md-12 col-lg-6">
            <img src="/assets/img/photos/coffee/coffee-top-down.jpg" alt="we love our customers" class="img-fluid mb-4 animate__animated animate__fadeIn">
        </div>
        <div class="col-md-12 col-lg-6 animate__animated animate__fadeIn pt-4 px-5">
            <h3 class="text-uppercase text-center fw-bold mt-4 mb-4">Contact <span class="fw-light">Us</span></h3>
            <form id="fs-frm" name="complaint-form" accept-charset="utf-8" action="https://formspree.io/f/mzzbvoww" method="post">
            <div class="d-flex flex-column">
                <fieldset id="fs-frm-inputs">  
                    <div>
                        <div class="d-flex align-items-baseline flex-wrap justify-content-between">
                            <div class="w-md-50 w-sm-100">
                                <label for="name"><h5 class="text-uppercase fw-light color-accent-2"><i class="fa-solid fa-address-card"></i> Name</h5></label>
                                <input type="text" name="name" id="name" class="w-100 p-2 mb-4 form-input rounded-3" required="" autocomplete="on">
                            </div>
                            <div class="w-md-50 w-sm-100">
                                <label for="email-address"><h5 class="text-uppercase fw-light color-accent-2"><i class="fa-solid fa-envelope"></i> Email</h5></label>
                                <input type="email" name="_replyto" id="email-address" class="w-100 p-2 mb-4 form-input rounded-3" required="">
                            </div>
                        </div>
                    </div>
                    <div class="mb-4">
                        <label for="message"><h5 class="text-uppercase fw-light color-accent-2"><i class="fa-solid fa-message"></i> Message</h5></label>
                        <textarea rows="4" name="message" id="message" class="w-100 rounded-3 fc-1 p-2 form-textarea" required=""></textarea>
                    </div>
                    <div>
                        <label for="phone"><h5 class="text-uppercase fw-light color-accent-2"><i class="fa-solid fa-envelope"></i> Phone Number <span class="opacity-50">(Optional)</span></h5></label>
                        <input type="telephone" name="phone" id="phone" class="w-100 p-2 mb-4 form-input rounded-3" placeholder="(555) 555-1212" autocomplete="on">
                    </div>
                    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
                </fieldset>
                </div>
                <input type="text" name="_gotcha" class="d-none">
                <button type="submit" value="Send" class="btn bg-light text-white border-2 rounded-3 px-4 pt-3 mt-4 w-50"><h6 class="text-black text-uppercase"><i class="fa-solid fa-paper-plane pe-1"></i> Send</h6></button>
            </form>
        </div>
    </div>
</div>