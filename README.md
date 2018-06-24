# wview-rainmeter
Displays information from your Wview or other weather station. 

A modification to the wview (or whatever) html template is required, so that the script can scrape it.

Edit /etc/wview/html/readings.htx and add this line: (View full page as it's not html friendly)

autotemp,<!--outsideTemp-->,<!--hiOutsideTemp-->,<!--lowOutsideTemp-->,<!--dailyRain-->,<!--hiRainRate-->,<!--monthlyRain-->,<!--windSpeed-->,<!--windDirection-->,<!--windBeaufortScale-->,<!--barometer-->,<!--outsideHumidity-->,<!--stationDate-->,<!--stationTime-->,<!--insideTemp-->
