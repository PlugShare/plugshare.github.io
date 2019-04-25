---
title: API Request Form
description: Commercial licenses only. Register for an API key to access api.plugshare.com
url: https://developer.plugshare.com/access
canonical_link: https://developer.plugshare.com/access
---
<form action="https://formspree.io/info@plugshare.com" method="POST" id="access">
  <fieldset>
    <legend><h2>API Request Form (Commercial Licenses Only)</h2></legend>
    <h3>Register for an API key to access api.plugshare.com</h3>
    <h4 class="warning">Note: We currently do not support personal or non-commercial licenses to use our data</h4>
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
        <label for="type">Which type of license are you looking for?</label><br>
        <select name="type" id="type" required>
          <option value="navigation">In-Vehicle Navigation App</option>
          <option value="mobile">Mobile App</option>
          <option value="website">Website</option>
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
      <div style="font-weight: bold; color: red; clear: left;">
        Sub-licensing the data/API is not permitted.
      </div>
      <input type="hidden" name="_next" value="thanks" />
    </div>
    <input type="submit" value="Request Access">
  </fieldset>
</form>