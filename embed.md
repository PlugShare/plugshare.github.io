<div id="embed">
  <h2>Embedding</h2>
  <p>The map below can be embedded into any article, blog, or website.</p>
  <p id="widget"><iframe src="https://www.plugshare.com/widget.html?latitude=33.9924&longitude=-118.4722&spanLat=0.02&spanLng=0.02" width="800" height="600"></iframe></p>

  <div id="parameters">
    <h2>Map Parameters</h2>

    <h3>Setting the map region</h3>
    <p>By default, the map automatically zooms to the user's current location. To set a specific region to load, set <b>all</b> of the following values:</p>
    <ul id="helpers">
        <li>Helper Functions (use these to help fill out the 4 inputs below)</li>
        <li>
          <form action="#">
            <input type="text" name="search" id="search" placeholder="Search Google for Coordinates">
            <input type="submit" id="geocode" value="SEARCH" class="button accept">
          </form>
        </li>
        <li id="result"><code></code></li>
        <li><input type="number" name="radius" id="radius" min="0" placeholder="Radius" > <span class="label">Map Radius in Miles (to help calculate span degrees)</span></li>
    </ul>
    <hr>
    <ul id="coords">
        <li><input type="text" name="latitude" id="latitude" placeholder="latitude" value="33.9924"> <span class="label">The latitude of the center coordinate.</span></li>
        <li><input type="text" name="longitude" id="longitude" placeholder="longitude" value="-118.4722"> <span class="label">The longitude of the center coordinate.</span></li>
        <li><input type="text" name="spanLat" id="spanLat" placeholder="spanLat" value="0.02"> <span class="label">The span in degrees latitude between N and S.</span></li>
        <li><input type="text" name="spanLng" id="spanLng" placeholder="spanLng" value="0.02"> <span class="label">The span in degrees longitude between E and W.</span></li>
    </ul>

    <h3>Setting the map size</h3>
    <p>Change the map size using the following values:</p>
    <ul id="dimensions">
        <li><input type="text" name="height" id="height" value="600" placeholder="height"> <span class="label">The height of the map widget in pixels.</span></li>
        <li><input type="text" name="width" id="width" value="800" placeholder="width"> <span class="label">The width of the map widget in pixels.</span></li>
    </ul>

    <div class="button">
      <a class="update" href="#">Update map</a>
    </div>
  </div>

  <h3>Embed Code</h3>
  <div id="terms">
    <p>Please read and accept the <a href="http://company.plugshare.com/terms/" target="_blank">Terms of Use</a> to view the embed code</p>
    <div class="button accept" id="accept_button">
      I ACCEPT
    </div>
  </div>
  <div id="snippet">
    <p>Insert the following code snippet into your website. For best results, it is recommended that you set a width no less than 500 and a height no less than 600.</p>
    <textarea id="code" rows="5" cols="100" disabled></textarea>
  </div>

  <textarea id="code" rows="2" cols="100" disabled></textarea>

  <!-- <hr>

  <h2>Who's using us?</h2>
  <p>Take a look at some of our partners</p>
  <div id="partners">
    <a href="https://www.ez-charge.com/stations/" target="_blank"><img src="ez-charge-logo.png"></a>
    <a href="http://pluginperks.com/find-a-charging-station/" target="_blank"><img src="drive-electric-orlando-logo.png"></a>
    <a href="https://www.kiachargeup.com/stations/" target="_blank"><img src="kia-chargeup-logo.png"></a>
    <a href="https://pluginamerica.org/get-equipped/find-an-ev-charging-station/" target="_blank"><img src="plugin-america-logo.png"></a>
  </div> -->
</div>