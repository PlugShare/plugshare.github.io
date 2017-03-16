<div id="content"><h2>Embedding</h2>
<p>The below map can be embedded into any article, blog, or website.</p>
<p id="widget"><iframe src="http://www.plugshare.com/widget.html?latitude=&amp;longitude=&amp;spanLat=&amp;spanLng=" width="800" height="600"></iframe></p>

<h3>Setting the map size.</h3>
<p>Change the map size using the following values.</p>
<ul>
    <li><input type="text" name="height" id="height" value="600"> - The height of the map widget in pixels.</li>
    <li><input type="text" name="width" id="width" value="800"> - The width of the map widget in pixels.</li>
</ul>

<h3>Setting the map region.</h3>
<p>
<input type="checkbox" name="currentlocation" id="currentlocation"> Automatically zoom to user's location
</p>
<p>To adjust the map region (it defaults to the user's current location) set the following values.</p>
<ul>
    <li><input type="text" name="latitude" id="latitude"> - The latitude of the center coordinate.</li>
    <li><input type="text" name="longitude" id="longitude"> - The longitude of the center coordinate</li>
    <li><input type="text" name="spanLat" id="spanLat"> - The distance in latitude between N and S.</li>
    <li><input type="text" name="spanLng" id="spanLng"> - The distance in longitude between E and W.</li>
</ul>

<h3>Code</h3>
<p>Insert the following code snippet into your website. For best results, it is recommended that you set a width no less than 500 and a height no less than 600. You can test the parameters here.</p>

<p><a id="update" href="#" style="text-decoration:underline;">Update code with values entered above</a></p>
<textarea id="code" rows="2" cols="100"></textarea>

<script>
    (function() {
        var updateFunc = function() {
            $("#widget").html($("#code").val());

            var height = $("#height").val();
            var width = $("#width").val();

            var src = 'http://www.plugshare.com/widget.html';

            if (!($('#currentlocation').is(':checked'))) {

                var spanLat = $("#spanLat").val();
                var spanLng = $("#spanLng").val();
                var latitude = $("#latitude").val();
                var longitude = $("#longitude").val();

                src += '?latitude=' + latitude + '&longitude=' + longitude + '&spanLat=' + spanLat + '&spanLng=' + spanLng;
            }

            code = '<iframe src="' + src + '" width="' + width + '" height="' + height + '"></iframe>';

            $("#widget").html(code);
            $("#code").val(code);
        };
    
        updateFunc();

        $("#update").on("click", function(e) {
            e.preventDefault();
            updateFunc();
        });
        $("#reset").on("click", function() {
            $("#widget").html(code);
            $("#code").val(code);
        });

        /*
        //get the very first bounds changed so we can make the first locations request
        google.maps.event.addListener(this.map, "bounds_changed", function() {
            if ($('#chargerCost').is(':checked')) {
                code = '<iframe src="http://www.plugshare.com/widget.html" width="800" height="600"></iframe>';
            } else {
                var center = this.map.getCenter();    
                var bounds = this.map.getBounds();
                var spanLat = bounds.toSpan().lat();
                var spanLng = bounds.toSpan().lng();
                var latitude = center.lat();
                var longitude = center.lng();

                code = '<iframe src="http://www.plugshare.com/widget.html?latitude=' + latitude + '&longitude=' + longitude + '&spanLat=' + spanLat + '&spanLng=' + spanLng + '" width="800" height="600"></iframe>';
            }
        });
*/
    })();
</script>

</div>