<!DOCTYPE html>
<html>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <body>

 <center>
<form action="https://developer.nrel.gov/api/pvwatts/v5.json?api_key=" method="get" target="_blank">
<br>
 <input type="hidden" name="api_key" value="jCtAj6gJCBngSY1vFYFfvU96bY85SAEDzzlXayPC">
 Location (enter location name): <input type="text" name="address"><br>
  <br>
 Timestamp (<code>monthly</code> or <code>hourly</code>): <input type="text" name="timeframe"><br>
 <br> 
 Radius (miles): <input type="number" name="radius"><br>
 <br>
 System Capacity (kW): <input type="number" name="system_capacity"><br>
 <br>
 Module Type (<code>0—</code>Standard, <code>1</code>—Premium, <code>2</code>—Thin film): <input type="number" name="module_type"><br>
 <br>
 System Losses (-5% – 99%): <input type="number" name="losses"><br>
 <br>
 Array Type (<code>0</code>—Fixed - Open Rack, <code>1</code>—Fixed - Roof Mounted, <code>2</code>—1-Axis, <code>3</code>—1-Axis Backtracking, <code>4</code>—2-Axis): <input type="number" name="array_type"><br>
 <br>
 Tilt (0–90 degrees): <input type="number" name="tilt"><br>
 <br>
 Azimuth (0–360 degrees): <input type="number" name="azimuth"><br>
 <br>
 Solar Dataset (<code>tmy2</code>—TMY2, <code>tmy3</code>—TMY3, <code>intl</code>—International dataset, <code>IN</code>—India dataset): <input type="text" name="dataset"><br>
 <br>
  <input type="submit" value="Submit">
  
</form>
 </center>


</body>
</html>
