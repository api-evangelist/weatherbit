---
title: "API Update: Hourly AG-Weather API"
url: "https://blog.weatherbit.io/api-update-hourly-agweather-api/"
date: "Wed, 20 Dec 2023 20:20:37 GMT"
author: "Weatherbit Team"
feed_url: "https://blog.weatherbit.io/rss/"
---
<img alt="API Update: Hourly AG-Weather API" src="https://blog.weatherbit.io/content/images/2023/12/soil-water-components.png" /><p>We have a couple of exciting updates regarding our API, and our service offerings.</p><h2 id="hourly-ag-weather-data-api">Hourly Ag-Weather Data API</h2><p>Our <a href="https://www.weatherbit.io/api/ag-weather-api?ref=blog.weatherbit.io">AG-Weather API</a> now returns both hourly, and daily data. This will allow for greater resolution of short term fluctuations in weather conditions that affect agriculture. To use hourly data, simply append the &quot;<strong>&amp;tp=hourly</strong>&quot; URL parameter to </p><pre><code>

https://api.weatherbit.io/v2.0/history/agweather?lat=34.035&amp;lon=-117.846191&amp;start_date=2023-12-16&amp;end_date=2023-12-17&amp;key=API_KEY&amp;tp=hourly

</code></pre><p>Additionally, this API now uses both the GLDAS, and ERA-5 as it&apos;s primary data sources. </p><h2 id="updates-to-evapotranspiration-calculation">Updates to Evapotranspiration Calculation </h2><p>In combination with this update, we have made an update to the way our AgWeather API calculates Reference Evapotranspiration (ET<sub>0</sub>). It now incorporates an updated version of the Penman Monteith Formula described in <a href="https://marais.ch/doc/fao56.pdf?ref=blog.weatherbit.io">https://marais.ch/doc/fao56.pdf</a>, which enables a significantly better calculation of ET<sub>0</sub> particularly in hot/humid conditions. </p><h2 id="conclusion">Conclusion</h2><p>We hope that our users find value in these updates. We are always looking for ways to improve our API. Feel free to reach out to support@weatherbit.io with any questions or concerns.</p>
