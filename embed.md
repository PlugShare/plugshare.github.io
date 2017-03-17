<div id="embed">
  <h2>Embedding</h2>
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

    <div class="button">
      <a id="update" href="#">Update map</a>
    </div>
  </div>

  <h3>Code</h3>
  <p>Insert the following code snippet into your website. For best results, it is recommended that you set a width no less than 500 and a height no less than 600.</p>

  <textarea id="code" rows="2" cols="100" disabled></textarea>
</div>