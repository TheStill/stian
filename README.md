<!DOCTYPE html><html><head><meta charset="utf-8"><title>Untitled Document.md</title><style></style></head><body id="preview">
<h1><a id="Stian__Weather_made_simple_0"></a>Stian - Weather made simple</h1>
<h1><a id="Overview_2"></a>Overview</h1>
<p>Using stian you will be able fetch various weather forecasts the website <a href="http://darksky.net">darksky.net</a>. These include current weather, daily weather, hourly weather and weather info by the minute.</p>
<h1><a id="Install_6"></a>Install</h1>
<p>pip install stian</p>
<h1><a id="Usage_10"></a>Usage</h1>
<p>import stian</p>
<p>current_conditions = stian.CurrentWeather()</p>
<p>Next we fetch the current weather condions.<br>
current_conditions.update(“API_Key”, Latitude, Longitude)</p>
<p>API_Key = Your API Key from <a href="http://darksky.net">darksky.net</a>.<br>
Latitude and Longiude of your requested location in degrees.<br>
e.g. 55.851976, -4.109991</p>
<p>Now to get for instance the temperature.<br>
print(current_conditions.current_temperature())</p>

</body></html>