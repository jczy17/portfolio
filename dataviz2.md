# Assignment: Visualizing government debt using Tableau
Part 1 The government debt bar chart
<iframe src="https://data.oecd.org/chart/7knd" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7knd" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>

Part 2 The heat map
<div class='tableauPlaceholder' id='viz1706587305716' style='position: relative'><noscript><a href='#'><img alt='Different countries&#39; general government debt-to-GDP ratios Total, % of GDP, 1995-2022 or latest available Source: National Accounts at a Glance ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17065634045110&#47;DifferentCountriesDebt-to-GDPRatios&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_17065634045110&#47;DifferentCountriesDebt-to-GDPRatios' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17065634045110&#47;DifferentCountriesDebt-to-GDPRatios&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1706587305716');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Part 3 Another visualization

Graph 1: Boxplot with linechart
<div class='tableauPlaceholder' id='viz1706588442794' style='position: relative'><noscript><a href='#'><img alt='Different countries&#39; general government debt-to-GDP ratios Total, % of GDP, 1995-2022 or latest available Source: National Accounts at a GlanceGeneral government debt-to-GDP ratio measures the gross debt of the general government as a percentage of GDP. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book2_17065478213190&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book2_17065478213190&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book2_17065478213190&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1706588442794');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Graph 2: Map
<div class='tableauPlaceholder' id='viz1706588376526' style='position: relative'><noscript><a href='#'><img alt='Map of different countries&#39; general government debt-to-GDP ratios Total, % of GDP, 2018 Source: National Accounts at a GlanceGeneral government debt-to-GDP ratio measures the gross debt of the general government as a percentage of GDP. It is a key indic ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book2_17065478213190&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book2_17065478213190&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book2_17065478213190&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1706588376526');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

# Some written summary
When we consider about debt-to-GDP ratios by country, a choropleth map would be effective for geographic distribution (I change the data type of location into the geographic role of Country/Region to create the map) . When it comes to trends over time, a line chart or an area chart can show how the ratio has evolved. And through the boxplot we can immediately find the max, min, median, Q1 and Q4 of each year's data as well as some outliers (eg, JPN) 

Usage of color: I attempt to use a color scale that intuitively represents the data: for instance, darker shades could indicate higher debt-to-GDP ratios, which are often perceived as more severe or concerning (color convention) .The map uses a gradient of blue to indicate the severity of the debt ratio, with darker tones marking higher ratios. The line chart shows the trend over time, with some selected country represented by a unique color but they are all relatively red or yellow. The consistent color make the visual presentation more coherent and help viewers quickly understand the layout and content of the chart.

Clarity: Because hovering over a country on the map or a point on the line chart to see specific ratio values, I don't need to label all of the values on the graph. I intentionally picked and colored several countries as representatives to show the overall trend of the ratio developing overtime and leave others with gray. Using shades of gray and grid lines make it easier for viewers to process the information being presented. As for map, in addition to using consistent blue, I leave the rest of the continent blank colored to make the important graph stand out.

[Take me back to the home page!](README.md)
