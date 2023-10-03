---
title: API Request Form
description: Commercial licenses only. Register for an API key to access api.plugshare.com
url: https://developer.plugshare.com/access
canonical_link: https://developer.plugshare.com/access
---
<form action="https://formspree.io/f/xpzkqavv" method="POST" id="access">
  {% raw %}
  <input name="subject" type="hidden" value="{{ company }} - {{ region }} - API" />
  {% endraw %}
  <fieldset>
    <legend><h2>API Request Form (Commercial Licenses Only)</h2></legend>
    <h3>Register for an API key to access api.plugshare.com</h3>
    <h4>Thank you for your interest in obtaining an evaluation license to access the PlugShare API for EV charging station data.</h4>
    <h4>To help us better understand your needs, please tell us about your project using the form below.</h4>
    <h4 class="warning" style="margin-top: 10px;">Note: Due to the volume of inquiries we receive and our limited developer support resources, we do not provide personal or non-commercial licenses to use our data at this time.</h4>
    <div class="fields">
      <div class="input-field">
        <label for="first_name">First Name:</label><br>
        <input type="text" name="first_name" id="first_name" value="" placeholder="First Name" required>
      </div>
      <div class="input-field">
        <label for="last_name">Last Name:</label><br>
        <input type="text" name="last_name" id="last_name" value="" placeholder="Last Name" required>
      </div>
      <div class="input-field">
        <label for="company">Company Name:</label><br>
        <input type="text" name="company" id="company" value="" placeholder="Company Name" required>
      </div>
      <div class="input-field">
        <label for="phone">Business Phone:</label><br>
        <input type="tel" name="phone" id="phone" value="" placeholder="Business Phone" required>
      </div>
      <div class="input-field">
        <label for="email">Business Email:</label><br>
        <input type="email" name="email" id="email" value="" placeholder="Business Email" required>
      </div>
      <div class="input-field">
        <label for="description">What is the proposed use of the data/API?</label><br>
        <textarea rows="4" cols="50" name="description" id="description" required></textarea>
      </div>
      <div class="input-field">
        <label for="type">Which type of application are you developing?</label><br>
        <select name="type" id="type" required>
          <option value="" disabled selected></option>
          <option value="mobile">Mobile App</option>
          <option value="website">Website</option>
          <option value="navigation">In-Vehicle Navigation App</option>
          <option value="navigation">Multiple Platforms</option>
        </select>
      </div>
      <div class="input-field" style="clear: left;">
        <label for="users">How many users will there be?</label><br>
        <input type="text" name="users" id="users" value="" placeholder="number or range" required>
      </div>
      <div class="input-field">
        <label for="region">Where will the data be used?</label><br>
        <input type="text" name="region" id="region" value="" placeholder="Region: US, Europe, etc." required>
      </div>
      <div class="input-field">
        <label for="budget">What is your budget for acquiring and using data for this project?</label><br>
        <input type="text" name="budget" id="budget" value="" placeholder="number or range" required>
      </div>
      <div class="input-field">
        <label for="timeline">What is your timeline for evaluating data for this project, and when do you plan to launch a production version?</label><br>
        <input type="text" name="timeline" id="timeline" value="" placeholder="" required>
      </div>
      <input type="hidden" name="_next" value="thanks" />
    </div>
    <input type="submit" value="Request Access">
  </fieldset>
</form>