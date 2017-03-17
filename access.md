<form action="https://formspree.io/joe@recargo.com" method="POST" id="access">
  <fieldset>
    <legend><h2>API Request Form</h2></legend>
    <h3>Register for an API key to access api.plugshare.com</h3>
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
        <input type="text" name="phone" id="phone" value="" placeholder="Business Phone" required>
      </div>
      <div class="input-field">
        <label for="email">Email:</label><br>
        <input type="email" name="email" id="email" value="" placeholder="Email" required>
      </div>
      <input type="hidden" name="_next" value="thanks" />
    </div>
    <input type="submit" value="Request Access">
  </fieldset>
</form>