<div id="embed">
  <h2>Dealer Program - Embedded Map Generator</h2>
  <p>The map below can be embedded into any article, blog, or website.</p>
  <p id="widget"><iframe src="https://www.plugshare.com/widget.html?latitude=33.9924&longitude=-118.4722&spanLat=0.02&spanLng=0.02" width="800" height="600"></iframe></p>

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

    <h3>Filter by outlets</h3>
    <p>By default, all outlet types are shown. Select one or more outlets to restrict results to show locations with at least one of the selected outlet(s) type.</p>
    <ul id="outlets">
        <li><input type="checkbox" name="outlet" value="1"> <span class="label"><img src="http://developers.plugshare.com/images/image03.png"> US Wall Outlet</span></li>
        <li><input type="checkbox" name="outlet" value="2"> <span class="label"><img src="http://developers.plugshare.com/images/image08.png"> J-1772</span></li>
        <li><input type="checkbox" name="outlet" value="3"> <span class="label"><img src="http://developers.plugshare.com/images/image04.png"> CHAdeMO</span></li>
        <li><input type="checkbox" name="outlet" value="4"> <span class="label"><img src="http://developers.plugshare.com/images/image00.png"> Tesla Roadster</span></li>
        <li><input type="checkbox" name="outlet" value="5"> <span class="label"><img src="http://developers.plugshare.com/images/image10.png"> NEMA 14-50</span></li>
        <li><input type="checkbox" name="outlet" value="6.0"> <span class="label"><img src="http://developers.plugshare.com/images/image05.png"> Tesla S HPWC</span></li>
        <li><input type="checkbox" name="outlet" value="6.1"> <span class="label"><img src="http://developers.plugshare.com/images/image05.png"> Tesla Supercharger</span></li>
        <li><input type="checkbox" name="outlet" value="7"> <span class="label"><img src="http://developers.plugshare.com/images/image06.png"> Type 2 (Mennekes)</span></li>
        <li><input type="checkbox" name="outlet" value="8"> <span class="label"><img src=""> Type 3</span></li>
        <li><input type="checkbox" name="outlet" value="9"> <span class="label"><img src="http://developers.plugshare.com/images/image09.png"> BS1363</span></li>
        <li><input type="checkbox" name="outlet" value="10"> <span class="label"><img src="http://developers.plugshare.com/images/image13.png"> Europlug</span></li>
        <li><input type="checkbox" name="outlet" value="11"> <span class="label"><img src="http://developers.plugshare.com/images/image12.png"> UK Commando</span></li>
        <li><input type="checkbox" name="outlet" value="12"> <span class="label"><img src="http://developers.plugshare.com/images/image01.png"> AS3112</span></li>
        <li><input type="checkbox" name="outlet" value="13"> <span class="label"><img src="http://developers.plugshare.com/images/image02.png"> SAE Combo DC CCS</span></li>
        <li><input type="checkbox" name="outlet" value="14"> <span class="label"><img src=""> Three Phase 32A (UK)</span></li>
    </ul>

    <h3>Filter by networks</h3>
    <p>By default, all networks are shown. Select one or more networks to restrict results to include or exclude locations with at least one of the selected network(s).</p>
    <aside class="notice">
      Note: For exclusions, if a location has both a ChargePoint station and a station of another network or a non-networked station it will still be eligible to be returned.
    </aside>
    <div class="network">
      <input type="radio" name="type" value="include" checked> Include
    </div>
    <div class="network">
      <input type="radio" name="type" value="exclude"> Exclude
    </div>
    <ul id="networks">
        <li><input type="checkbox" name="network" value="7"> <span class="label">AddEnergie</span></li>
        <li><input type="checkbox" name="network" value="9"> <span class="label">AeroVironment</span></li>
        <li><input type="checkbox" name="network" value="2"> <span class="label">Blink</span></li>
        <li><input type="checkbox" name="network" value="1"> <span class="label">ChargePoint</span></li>
        <li><input type="checkbox" name="network" value="6"> <span class="label">Circuit Electrique</span></li>
        <li><input type="checkbox" name="network" value="18"> <span class="label">Clever</span></li>
        <li><input type="checkbox" name="network" value="15"> <span class="label">Endesa</span></li>
        <li><input type="checkbox" name="network" value="23"> <span class="label">Enel Drive</span></li>
        <li><input type="checkbox" name="network" value="16"> <span class="label">ESB</span></li>
        <li><input type="checkbox" name="network" value="19"> <span class="label">EVgo</span></li>
        <li><input type="checkbox" name="network" value="4"> <span class="label">GE WattStation</span></li>
        <li><input type="checkbox" name="network" value="26"> <span class="label">Greenlots</span></li>
        <li><input type="checkbox" name="network" value="34"> <span class="label">JNSH</span></li>
        <li><input type="checkbox" name="network" value="22"> <span class="label">Lastestasjoner</span></li>
        <li><input type="checkbox" name="network" value="11"> <span class="label">OpenChargeMap</span></li>
        <li><input type="checkbox" name="network" value="14"> <span class="label">Oplaadpalen</span></li>
        <li><input type="checkbox" name="network" value="13"> <span class="label">RWE</span></li>
        <li><input type="checkbox" name="network" value="3"> <span class="label">Semaconnect</span></li>
        <li><input type="checkbox" name="network" value="5"> <span class="label">Sun Country</span></li>
        <li><input type="checkbox" name="network" value="8"> <span class="label">Tesla Supercharger</span></li>
        <li><input type="checkbox" name="network" value="17"> <span class="label">Uppladdning</span></li>
        <li><input type="checkbox" name="network" value="25"> <span class="label">Volta</span></li>
    </ul>

    <div class="button">
      <a id="update" href="#">Update map</a>
    </div>
  </div>

  <h3>Code</h3>
  <p>Insert the following code snippet into your website. For best results, it is recommended that you set a width no less than 500 and a height no less than 600.</p>

  <textarea id="code" rows="4" cols="100" disabled></textarea>
</div>