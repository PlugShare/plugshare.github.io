<div id="embed">
  <h2>Dealer Program - Embedded Map Generator</h2>
  <p>The map below can be embedded into any article, blog, or website.</p>
  <p id="widget"><iframe src="https://www.plugshare.com/widget.html?latitude=&amp;longitude=&amp;spanLat=&amp;spanLng=" width="800" height="600"></iframe></p>

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
    <ul id="coords">
        <li><input type="text" name="latitude" id="latitude" placeholder="latitude"> <span class="label">The latitude of the center coordinate.</span></li>
        <li><input type="text" name="longitude" id="longitude" placeholder="longitude"> <span class="label">The longitude of the center coordinate</span></li>
        <li><input type="text" name="spanLat" id="spanLat" placeholder="spanLat"> <span class="label">The distance in latitude between N and S.</span></li>
        <li><input type="text" name="spanLng" id="spanLng" placeholder="spanLng"> <span class="label">The distance in longitude between E and W.</span></li>
    </ul>

    <h3>Filter by outlets</h3>
    <p>By default, all outlet types are shown. Select one or more outlets to restrict results to show locations with at least one of the selected outlet(s) type.</p>
    <ul id="outlets">
        <li><input type="checkbox" name="outlet" value="1"> <span class="label">1. US Wall Outlet</span></li>
        <li><input type="checkbox" name="outlet" value="2"> <span class="label">2. J-1772</span></li>
        <li><input type="checkbox" name="outlet" value="3"> <span class="label">3. CHAdeMO</span></li>
        <li><input type="checkbox" name="outlet" value="4"> <span class="label">4. Tesla Roadster</span></li>
        <li><input type="checkbox" name="outlet" value="5"> <span class="label">5. NEMA 14-50</span></li>
        <li><input type="checkbox" name="outlet" value="6.0"> <span class="label">6.0 Tesla S HPWC</span></li>
        <li><input type="checkbox" name="outlet" value="6.1"> <span class="label">6.1 Tesla Supercharger</span></li>
        <li><input type="checkbox" name="outlet" value="7"> <span class="label">7. Type 2 (Mennekes)</span></li>
        <li><input type="checkbox" name="outlet" value="8"> <span class="label">8. Type 3</span></li>
        <li><input type="checkbox" name="outlet" value="9"> <span class="label">9. BS1363</span></li>
        <li><input type="checkbox" name="outlet" value="10"> <span class="label">10. Europlug</span></li>
        <li><input type="checkbox" name="outlet" value="11"> <span class="label">11. UK Commando</span></li>
        <li><input type="checkbox" name="outlet" value="12"> <span class="label">12. AS3112</span></li>
        <li><input type="checkbox" name="outlet" value="13"> <span class="label">13. SAE Combo DC CCS</span></li>
        <li><input type="checkbox" name="outlet" value="14"> <span class="label">14. Three Phase 32A (UK)</span></li>
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
        <li><input type="checkbox" name="network" value="1"> <span class="label">1. ChargePoint</span></li>
        <li><input type="checkbox" name="network" value="2"> <span class="label">2. Blink</span></li>
        <li><input type="checkbox" name="network" value="3"> <span class="label">3. Semaconnect</span></li>
        <li><input type="checkbox" name="network" value="4"> <span class="label">4. GE WattStation</span></li>
        <li><input type="checkbox" name="network" value="5"> <span class="label">5. Sun Country</span></li>
        <li><input type="checkbox" name="network" value="6"> <span class="label">6. Circuit Electrique</span></li>
        <li><input type="checkbox" name="network" value="7"> <span class="label">7. AddEnergie</span></li>
        <li><input type="checkbox" name="network" value="8"> <span class="label">8. Tesla Supercharger</span></li>
        <li><input type="checkbox" name="network" value="9"> <span class="label">9. AeroVironment</span></li>
        <li><input type="checkbox" name="network" value="11"> <span class="label">11. OpenChargeMap</span></li>
        <li><input type="checkbox" name="network" value="13"> <span class="label">13. RWE</span></li>
        <li><input type="checkbox" name="network" value="14"> <span class="label">14. Oplaadpalen</span></li>
        <li><input type="checkbox" name="network" value="15"> <span class="label">15. Endesa</span></li>
        <li><input type="checkbox" name="network" value="16"> <span class="label">16. ESB</span></li>
        <li><input type="checkbox" name="network" value="17"> <span class="label">17. Uppladdning</span></li>
        <li><input type="checkbox" name="network" value="18"> <span class="label">18. Clever</span></li>
        <li><input type="checkbox" name="network" value="19"> <span class="label">19. EVgo</span></li>
        <li><input type="checkbox" name="network" value="22"> <span class="label">22. Lastestasjoner</span></li>
        <li><input type="checkbox" name="network" value="23"> <span class="label">23. Enel Drive</span></li>
        <li><input type="checkbox" name="network" value="25"> <span class="label">25. Volta</span></li>
        <li><input type="checkbox" name="network" value="26"> <span class="label">26. Greenlots</span></li>
        <li><input type="checkbox" name="network" value="34"> <span class="label">34. JNSH</span></li>
    </ul>

    <div class="button">
      <a id="update" href="#">Update map</a>
    </div>
  </div>

  <h3>Code</h3>
  <p>Insert the following code snippet into your website. For best results, it is recommended that you set a width no less than 500 and a height no less than 600.</p>

  <textarea id="code" rows="2" cols="100" disabled></textarea>
</div>