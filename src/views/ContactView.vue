<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <!-- Begin Li's Breadcrumb Area -->
  <div class="breadcrumb-area">
    <div class="container">
      <div class="breadcrumb-content">
        <ul>
          <li><RouterLink to="/">Home</RouterLink></li>
          <li class="active">Contact</li>
        </ul>
      </div>
    </div>
  </div>
  <!-- Li's Breadcrumb Area End Here -->
  <!-- Begin Contact Main Page Area -->
  <div class="contact-main-page mt-60 mb-40 mb-md-40 mb-sm-40 mb-xs-40">
    <div class="container mb-60">
      <iframe
        id="google-map"
        title="Google Map"
        src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15676.511492091135!2d106.640723!3d10.801517!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x317529502711460f%3A0xb7ce4406b2d0bb8b!2sNashTech%20Ho%20Chi%20Minh%20City!5e0!3m2!1sen!2s!4v1689063591814!5m2!1sen!2s"
        width="800"
        height="600"
        style="border: 0"
        allowfullscreen
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
      ></iframe>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-lg-5 offset-lg-1 col-md-12 order-1 order-lg-2">
          <div class="contact-page-side-content">
            <h3 class="contact-page-title">Contact Us</h3>
            <p class="contact-page-message mb-25">
              Claritas est etiam processus dynamicus, qui sequitur mutationem consuetudium lectorum.
              Mirum est notare quam littera gothica, quam nunc putamus parum claram anteposuerit
              litterarum formas human.
            </p>
            <div class="single-contact-block">
              <h4><i class="fa fa-fax"></i> Address</h4>
              <p>123 Main Street, Anytown, CA 12345 – USA</p>
            </div>
            <div class="single-contact-block">
              <h4><i class="fa fa-phone"></i> Phone</h4>
              <p>Mobile: (08) 123 456 789</p>
              <p>Hotline: 1009 678 456</p>
            </div>
            <div class="single-contact-block last-child">
              <h4><i class="fa fa-envelope-o"></i> Email</h4>
              <p>yourmail@domain.com</p>
              <p>support@hastech.company</p>
            </div>
          </div>
        </div>
        <div class="col-lg-6 col-md-12 order-2 order-lg-1">
          <div class="contact-form-content pt-sm-55 pt-xs-55">
            <h3 class="contact-page-title">Tell Us Your Message</h3>
            <div class="contact-form">
              <form
                id="contact-form"
                action="http://demo.hasthemes.com/limupa-v3/limupa/mail.php"
                method="post"
              >
                <div class="form-group">
                  <label>Your Name <span class="required">*</span></label>
                  <input type="text" name="customerName" id="customername" required />
                </div>
                <div class="form-group">
                  <label>Your Email <span class="required">*</span></label>
                  <input type="email" name="customerEmail" id="customerEmail" required />
                </div>
                <div class="form-group">
                  <label>Subject</label>
                  <input type="text" name="contactSubject" id="contactSubject" />
                </div>
                <div class="form-group mb-30">
                  <label>Your Message</label>
                  <textarea name="contactMessage" id="contactMessage"></textarea>
                </div>
                <div class="form-group">
                  <button type="submit" value="submit" id="submit" class="li-btn-3" name="submit">
                    send
                  </button>
                </div>
              </form>
            </div>
            <p class="form-messege"></p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Contact Main Page Area End Here -->
</template>
