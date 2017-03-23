<div id="embed">
  <h2>Dealer Program - Embedded Map Generator</h2>
  <p>The map below can be embedded into any article, blog, or website.</p>
  <p id="widget"><iframe src="https://staging.plugshare.com/widget2.html?allowEmbedFilters=true&latitude=33.9924&longitude=-118.4722&spanLat=0.02&spanLng=0.02" width="800" height="600"></iframe></p>

  <div id="parameters">
    <h2>Map Parameters</h2>

    <h3>Setting the map size</h3>
    <p>Change the map size using the following values:</p>
    <ul id="dimensions">
        <li><input type="text" name="height" id="height" value="600" placeholder="height"> <span class="label">The height of the map widget in pixels.</span></li>
        <li><input type="text" name="width" id="width" value="800" placeholder="width"> <span class="label">The width of the map widget in pixels.</span></li>
    </ul>

    <h3>Setting the map region</h3>
    <p>By default, the map automatically zooms to the user's current location. To set a specific region to load, set <b>all</b> of the following values:</p>
    <aside class="notice">
      Note: You must provide all 4 coordinate attributes before you can apply additional filters.
    </aside>
    <ul id="coords">
        <li><input type="text" name="latitude" id="latitude" placeholder="latitude" value="33.9924"> <span class="label">The latitude of the center coordinate.</span></li>
        <li><input type="text" name="longitude" id="longitude" placeholder="longitude" value="-118.4722"> <span class="label">The longitude of the center coordinate</span></li>
        <li><input type="text" name="spanLat" id="spanLat" placeholder="spanLat" value="0.02"> <span class="label">The distance in latitude between N and S.</span></li>
        <li><input type="text" name="spanLng" id="spanLng" placeholder="spanLng" value="0.02"> <span class="label">The distance in longitude between E and W.</span></li>
    </ul>

    <div class="button">
      <a class="update" href="#">Update map</a>
    </div><br><br>

    <h3>Filter by outlets</h3>
    <p>By default, all outlet types are shown. Select one or more outlets to restrict results to show locations with at least one of the selected outlet(s) type.</p>
    <ul id="outlets">
        <label for="outlet1"><li><input type="checkbox" name="outlet" value="1" id="outlet1"> <span class="label"><img src="http://developers.plugshare.com/images/image03.png"> US Wall Outlet</span></li></label>
        <label for="outlet2"><li><input type="checkbox" name="outlet" value="2" id="outlet2"> <span class="label"><img src="http://developers.plugshare.com/images/image08.png"> J-1772</span></li></label>
        <label for="outlet3"><li><input type="checkbox" name="outlet" value="3" id="outlet3"> <span class="label"><img src="http://developers.plugshare.com/images/image04.png"> CHAdeMO</span></li></label>
        <label for="outlet4"><li><input type="checkbox" name="outlet" value="4" id="outlet4"> <span class="label"><img src="http://developers.plugshare.com/images/image00.png"> Tesla Roadster</span></li></label>
        <label for="outlet5"><li><input type="checkbox" name="outlet" value="5" id="outlet5"> <span class="label"><img src="http://developers.plugshare.com/images/image10.png"> NEMA 14-50</span></li></label>
        <label for="outlet6_0"><li><input type="checkbox" name="outlet" value="6_0" id="outlet6_0"> <span class="label"><img src="http://developers.plugshare.com/images/image05.png"> Tesla S HPWC</span></li></label>
        <label for="outlet6_1"><li><input type="checkbox" name="outlet" value="6_1" id="outlet6_1"> <span class="label"><img src="http://developers.plugshare.com/images/image05.png"> Tesla Supercharger</span></li></label>
        <!-- <li><input type="checkbox" name="outlet" value="7"> <span class="label"><img src="http://developers.plugshare.com/images/image06.png"> Type 2 (Mennekes)</span></li>
        <li><input type="checkbox" name="outlet" value="8"> <span class="label"><img src=""> Type 3</span></li>
        <li><input type="checkbox" name="outlet" value="9"> <span class="label"><img src="http://developers.plugshare.com/images/image09.png"> BS1363</span></li>
        <li><input type="checkbox" name="outlet" value="10"> <span class="label"><img src="http://developers.plugshare.com/images/image13.png"> Europlug</span></li>
        <li><input type="checkbox" name="outlet" value="11"> <span class="label"><img src="http://developers.plugshare.com/images/image12.png"> UK Commando</span></li>
        <li><input type="checkbox" name="outlet" value="12"> <span class="label"><img src="http://developers.plugshare.com/images/image01.png"> AS3112</span></li> -->
        <label for="outlet13"><li><input type="checkbox" name="outlet" value="13" id="outlet13"> <span class="label"><img src="http://developers.plugshare.com/images/image02.png"> SAE Combo DC CCS</span></li></label>
        <!-- <li><input type="checkbox" name="outlet" value="14"> <span class="label"><img src=""> Three Phase 32A (UK)</span></li> -->
    </ul>

    <h3>Filter by networks</h3>
    <p>By default, all networks are shown. Select one or more networks to restrict results to include or exclude locations with at least one of the selected network(s).</p>
    <aside class="notice">
      Note: For exclusions, if a location has both a ChargePoint station and a station of another network or a non-networked station it will still be eligible to be returned.
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
    <ul id="networks">
      <label for="network7"><li><input type="checkbox" name="network" value="7" id="network7"> <span class="label">AddEnergie</span></li></label>
      <label for="network9"><li><input type="checkbox" name="network" value="9" id="network9"> <span class="label">AeroVironment</span></li></label>
      <label for="network2"><li><input type="checkbox" name="network" value="2" id="network2"> <span class="label">Blink</span></li></label>
      <label for="network33"><li><input type="checkbox" name="network" value="33" id="network33"> <span class="label">CarCharging</span></li></label>
      <label for="network20"><li><input type="checkbox" name="network" value="20" id="network20"> <span class="label">Chademo</span></li></label>
      <label for="network24"><li><input type="checkbox" name="network" value="24" id="network24"> <span class="label">ChargeMap</span></li></label>
      <label for="network36"><li><input type="checkbox" name="network" value="36" id="network36"> <span class="label">ChargeNet</span></li></label>
      <label for="network1"><li><input type="checkbox" name="network" value="1" id="network1"> <span class="label">ChargePoint</span></li></label>
      <label for="network6"><li><input type="checkbox" name="network" value="6" id="network6"> <span class="label">Circuit Electrique</span></li></label>
      <label for="network18"><li><input type="checkbox" name="network" value="18" id="network18"> <span class="label">Clever</span></li></label>
      <label for="network35"><li><input type="checkbox" name="network" value="35" id="network35"> <span class="label">Destination</span></li></label>
      <label for="network32"><li><input type="checkbox" name="network" value="32" id="network32"> <span class="label">DOE AFDC</span></li></label>
      <label for="network15"><li><input type="checkbox" name="network" value="15" id="network15"> <span class="label">Endesa</span></li></label>
      <label for="network23"><li><input type="checkbox" name="network" value="23" id="network23"> <span class="label">Enel Drive</span></li></label>
      <label for="network16"><li><input type="checkbox" name="network" value="16" id="network16"> <span class="label">ESB</span></li></label>
      <label for="network19"><li><input type="checkbox" name="network" value="19" id="network19"> <span class="label">EVgo</span></li></label>
      <label for="network40"><li><input type="checkbox" name="network" value="40" id="network40"> <span class="label">EVPoint</span></li></label>
      <label for="network4"><li><input type="checkbox" name="network" value="4" id="network4"> <span class="label">GE WattStation</span></li></label>
      <label for="network39"><li><input type="checkbox" name="network" value="39" id="network39"> <span class="label">GreenFrontiers</span></li></label>
      <label for="network26"><li><input type="checkbox" name="network" value="26" id="network26"> <span class="label">Greenlots</span></li></label>
      <label for="network34"><li><input type="checkbox" name="network" value="34" id="network34"> <span class="label">JNSH</span></li></label>
      <label for="network22"><li><input type="checkbox" name="network" value="22" id="network22"> <span class="label">Lastestasjoner</span></li></label>
      <label for="network29"><li><input type="checkbox" name="network" value="29" id="network29"> <span class="label">OpConnect</span></li></label>
      <label for="network11"><li><input type="checkbox" name="network" value="11" id="network11"> <span class="label">OpenChargeMap</span></li></label>
      <label for="network14"><li><input type="checkbox" name="network" value="14" id="network14"> <span class="label">Oplaadpalen</span></li></label>
      <label for="network10"><li><input type="checkbox" name="network" value="10" id="network10"> <span class="label">PlugShare Stripe</span></li></label>
      <label for="network31"><li><input type="checkbox" name="network" value="31" id="network31"> <span class="label">RechargeAccess</span></li></label>
      <label for="network13"><li><input type="checkbox" name="network" value="13" id="network13"> <span class="label">RWE</span></li></label>
      <label for="network3"><li><input type="checkbox" name="network" value="3" id="network3"> <span class="label">Semaconnect</span></li></label>
      <label for="network30"><li><input type="checkbox" name="network" value="30" id="network30"> <span class="label">Shorepower</span></li></label>
      <label for="network5"><li><input type="checkbox" name="network" value="5" id="network5"> <span class="label">Sun Country</span></li></label>
      <label for="network8"><li><input type="checkbox" name="network" value="8" id="network8"> <span class="label">Tesla SuperCharger</span></li></label>
      <label for="network17"><li><input type="checkbox" name="network" value="17" id="network17"> <span class="label">Uppladdning</span></li></label>
      <label for="network25"><li><input type="checkbox" name="network" value="25" id="network25"> <span class="label">Volta</span></li></label>
    </ul>

    <div class="button">
      <a class="update" href="#">Update map</a>
    </div>
  </div>

  <h3>Code</h3>
  <p>Insert the following code snippet into your website. For best results, it is recommended that you set a width no less than 500 and a height no less than 600.</p>

  <textarea id="code" rows="4" cols="100" disabled></textarea>
</div>