---
title: Embeddable Map Generator
description: Generate your own PlugShare map to embed on your article, blog, or website! Easily preset the viewable area, outlets and network filters with this handy tool.
url: https://developer.plugshare.com/embed
canonical_link: https://developer.plugshare.com/embed
---
<div id="embed">
  <h2>Embeddable Map Generator</h2>
  <p>The map below can be embedded into any article, blog, or website.</p>
  <p id="widget"><iframe src="https://www.plugshare.com/widget2.html" width="800" height="600" allow="geolocation"></iframe></p>

  <div id="parameters">
    <h2>Map Parameters</h2>

    <section>
      <h3>Setting the map region</h3>
      <p>
        If no coordinates are set, the map automatically tries to look for and center on the user's current location (https geolocation required).<br>
        To set a specific region to load, set the latitude & longitude of the location you wish to display.
      </p>
      <form action="#">
        <ul id="helpers">
            <li>Helper Functions (use these to help fill out the 4 inputs below)</li>
            <li>
                <input type="text" name="search" id="search" placeholder="Search Google for Coordinates">
                <input type="submit" id="geocode" value="SEARCH & UPDATE MAP" class="button accept">
            </li>
            <li id="result"><code></code></li>
            <li><input type="number" name="radius" id="radius" min="0" placeholder="Radius" > <span class="label">Map Display Radius in Miles</span></li>
        </ul>
      </form>
      <hr>
      <ul id="coords">
          <li><input type="text" name="latitude" id="latitude" placeholder="latitude"> <span class="label">The latitude of the center coordinate.</span></li>
          <li><input type="text" name="longitude" id="longitude" placeholder="longitude"> <span class="label">The longitude of the center coordinate.</span></li>
          <li><input type="text" name="spanLat" id="spanLat" placeholder="spanLat" value="0.02"> <span class="label">The span in degrees latitude between N and S.</span></li>
          <li><input type="text" name="spanLng" id="spanLng" placeholder="spanLng" value="0.02"> <span class="label">The span in degrees longitude between E and W.</span></li>
      </ul>
    </section>

    <section>
      <h3>Setting the map size</h3>
      <p>Change the map size using the following values:</p>
      <ul id="dimensions">
          <li><input type="text" name="height" id="height" value="600" placeholder="height"> <span class="label">The height of the map widget in pixels.</span></li>
          <li><input type="text" name="width" id="width" value="800" placeholder="width"> <span class="label">The width of the map widget in pixels.</span></li>
      </ul>
    </section>

    <a class="update" href="#">
      <div class="button">
        Update map
      </div>
    </a>
    
    <br><br>

    <section>
      <h3>Filter by outlets</h3>
      <p>By default, all outlet types are shown. Select one or more outlets to restrict results to show locations with at least one of the selected outlet(s) type.</p>
      <div class="helpers">
        <button id="outlet_on">Check All</button>
        <button id="outlet_off">Check None</button>
      </div>
      <ul id="outlets">
        <!-- US/Canada -->
        <label for="outlet1"><li><input type="checkbox" name="outlet" value="1" id="outlet1" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image03.png"> US Wall Outlet</span></li></label>
        <label for="outlet2"><li><input type="checkbox" name="outlet" value="2" id="outlet2" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image08.png"> J-1772</span></li></label>
        <label for="outlet3"><li><input type="checkbox" name="outlet" value="3" id="outlet3" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image04.png"> CHAdeMO</span></li></label>
        <label for="outlet4"><li><input type="checkbox" name="outlet" value="4" id="outlet4" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image00.png"> Tesla Roadster</span></li></label>
        <label for="outlet5"><li><input type="checkbox" name="outlet" value="5" id="outlet5" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image10.png"> NEMA 14-50</span></li></label>
        <label for="outlet6"><li><input type="checkbox" name="outlet" value="6" id="outlet6" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image05.png"> Tesla S HPWC</span></li></label>
        <label for="outlet42"><li><input type="checkbox" name="outlet" value="42" id="outlet42" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image05.png"> Tesla Supercharger</span></li></label>
        <label for="outlet13"><li><input type="checkbox" name="outlet" value="13" id="outlet13" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image02.png"> SAE Combo DC CCS</span></li></label>
        <!-- Worldwide -->
        <label for="outlet7"><li><input type="checkbox" name="outlet" value="7" id="outlet7" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image06.png"> Type 2 (Mennekes)</span></li></label>
        <label for="outlet8"><li><input type="checkbox" name="outlet" value="8" id="outlet8" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image16.png"> Type 3</span></li></label>
        <label for="outlet9"><li><input type="checkbox" name="outlet" value="9" id="outlet9" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image09.png"> BS1363</span></li></label>
        <label for="outlet10"><li><input type="checkbox" name="outlet" value="10" id="outlet10" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image13.png"> Europlug</span></li></label>
        <label for="outlet11"><li><input type="checkbox" name="outlet" value="11" id="outlet11" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image12.png"> UK Commando</span></li></label>
        <label for="outlet12"><li><input type="checkbox" name="outlet" value="12" id="outlet12" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image01.png"> AS3112</span></li></label>
        <label for="outlet14"><li><input type="checkbox" name="outlet" value="14" id="outlet14" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image06.png"> Three Phase 32A (UK)</span></li></label>
        <label for="outlet15"><li><input type="checkbox" name="outlet" value="15" id="outlet15" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image15.png"> Caravan Mains Socket</span></li></label>
        <label for="outlet16"><li><input type="checkbox" name="outlet" value="16" id="outlet16" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image06.png"> China BG/T</span></li></label>
        <label for="outlet17"><li><input type="checkbox" name="outlet" value="17" id="outlet17" checked> <span class="label"><img src="https://assets.plugshare.com/assets/outlets/image17.png"> China BG/T 2</span></li></label>
      </ul>
    </section>

    <section>
      <h3>Filter by networks</h3>
      <p>By default, all networks are shown. Select one or more networks to restrict results to include or exclude locations with at least one of the selected supported network(s).</p>
      <aside class="notice">
        Note: For exclusions, if a location contains both a station to exclude and a station of another network or a non-networked station which is not specifically excluded, the location will still appear in the results.
      </aside>
      <div id="network_filter_type">
        <label for="network_include">
          <div class="network">
            <input type="radio" name="type" value="include" id="network_include" checked> Include
          </div>
        </label>
        <label for="network_exclude">
          <div class="network">
            <input type="radio" name="type" value="exclude" id="network_exclude"> Exclude
          </div>
        </label>
      </div>
      <div class="helpers">
        <button id="network_on">Check All</button>
        <button id="network_off">Check None</button>
      </div>
      <ul id="networks">
        <!-- when updating this list, make sure to update networks length in default.html -->
        <label for="network59"><li><input type="checkbox" name="network" value="59" id="network59" checked> <span class="label">Allego</span></li></label>
        <label for="network49"><li><input type="checkbox" name="network" value="49" id="network49" checked> <span class="label">BC Hydro EV</span></li></label>
        <label for="network2"><li><input type="checkbox" name="network" value="2" id="network2" checked> <span class="label">Blink</span></li></label>
        <label for="network45"><li><input type="checkbox" name="network" value="45" id="network45" checked> <span class="label">bp pulse</span></li></label>
        <label for="network48"><li><input type="checkbox" name="network" value="48" id="network48" checked> <span class="label">Chargefox</span></li></label>
        <label for="network36"><li><input type="checkbox" name="network" value="36" id="network36" checked> <span class="label">ChargeNet</span></li></label>
        <label for="network1"><li><input type="checkbox" name="network" value="1" id="network1" checked> <span class="label">ChargePoint</span></li></label>
        <label for="network6"><li><input type="checkbox" name="network" value="6" id="network6" checked> <span class="label">Circuit Electrique</span></li></label>
        <label for="network47"><li><input type="checkbox" name="network" value="47" id="network47" checked> <span class="label">Electrify America</span></li></label>
        <label for="network54"><li><input type="checkbox" name="network" value="54" id="network54" checked> <span class="label">Electrify Canada</span></li></label>
        <label for="network46"><li><input type="checkbox" name="network" value="46" id="network46" checked> <span class="label">EV Connect</span></li></label>
        <label for="network19"><li><input type="checkbox" name="network" value="19" id="network19" checked> <span class="label">EVgo</span></li></label>
        <label for="network60"><li><input type="checkbox" name="network" value="60" id="network60" checked> <span class="label">Evie Networks</span></li></label>
        <label for="network57"><li><input type="checkbox" name="network" value="57" id="network57" checked> <span class="label">EVUp</span></li></label>
        <label for="network52"><li><input type="checkbox" name="network" value="52" id="network52" checked> <span class="label">Fastned</span></li></label>
        <label for="network7"><li><input type="checkbox" name="network" value="7" id="network7" checked> <span class="label">FLO</span></li></label>
        <label for="network4"><li><input type="checkbox" name="network" value="4" id="network4" checked> <span class="label">GE WattStation</span></li></label>
        <label for="network26"><li><input type="checkbox" name="network" value="26" id="network26" checked> <span class="label">Greenlots</span></li></label>
        <label for="network51"><li><input type="checkbox" name="network" value="51" id="network51" checked> <span class="label">Ionity</span></li></label>
        <label for="network55"><li><input type="checkbox" name="network" value="55" id="network55" checked> <span class="label">IVY</span></li></label>
        <label for="network41"><li><input type="checkbox" name="network" value="41" id="network41" checked> <span class="label">myEVroute</span></li></label>
        <label for="network58"><li><input type="checkbox" name="network" value="58" id="network58" checked> <span class="label">OpConnect</span></li></label>
        <label for="network53"><li><input type="checkbox" name="network" value="53" id="network53" checked> <span class="label">Petro-Canada</span></li></label>
        <label for="network3"><li><input type="checkbox" name="network" value="3" id="network3" checked> <span class="label">SemaConnect</span></li></label>
        <label for="network5"><li><input type="checkbox" name="network" value="5" id="network5" checked> <span class="label">Sun Country</span></li></label>
        <label for="network8"><li><input type="checkbox" name="network" value="8" id="network8" checked> <span class="label">Supercharger</span></li></label>
        <label for="network35"><li><input type="checkbox" name="network" value="35" id="network35" checked> <span class="label">Tesla Destination</span></li></label>
        <label for="network25"><li><input type="checkbox" name="network" value="25" id="network25" checked> <span class="label">Volta</span></li></label>
        <label for="network9"><li><input type="checkbox" name="network" value="9" id="network9" checked> <span class="label">Webasto</span></li></label>
      </ul>
    </section>

    <a class="update" href="#">
      <div class="button">
        Update map
      </div>
    </a>
  </div>

  <h3>Embed Code</h3>
  <div id="terms">
    <p>Please read and accept the <a href="http://company.plugshare.com/terms.html" target="_blank">Terms of Use</a> to view the embed code</p>
    <div class="button accept" id="accept_button">
      I ACCEPT
    </div>
  </div>
  <div id="snippet">
    <p>Insert the following code snippet into your website. For best results, it is recommended that you set a width no less than 500 and a height no less than 600.</p>
    <textarea id="code" rows="5" cols="100" readonly="readonly"></textarea>
    <div class="button-margin">
      <div class="button accept" id="copy_button">
        Copy
      </div>
    </div>
  </div>

  <div id="notice">
    Deprecation Notice: For embed maps that default to user's location, Google Chrome requires adding <span class="code">allow="geolocation"</span> to your embed code.<br>
    Please add the tag to your existing embed code or use the generator to generate updated embed code.<br>
    <!-- For more information, <a href="https://sites.google.com/a/chromium.org/dev/Home/chromium-security/deprecating-permissions-in-cross-origin-iframes" target="_blank">click here</a>. -->
  </div>
  
  <div id="cta">
    <div class="prompt">
      Questions?
    </div>
    <a href="https://recargo.freshdesk.com/support/solutions/folders/29000052288">
      <div class="button">
        See our FAQ
      </div>
    </a>
  </div>

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