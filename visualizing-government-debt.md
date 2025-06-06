| [Home Page](https://chrisbori.github.io/My-Online-Portfolio/) | [Eval-AI Model Check](https://chrisbori.github.io/My-Online-Portfolio/eval-ai) | [Puerto Rico's Act 22](https://chrisbori.github.io/My-Online-Portfolio/final-project-part-three) | [Visualizing Debt](https://chrisbori.github.io/My-Online-Portfolio/visualizing-government-debt) | [Everybody Poops](https://chrisbori.github.io/My-Online-Portfolio/critique-by-design) |

# Visualizing Government Debt
This data, sourced from the Organisation for Economic Co-operation and Development (OECD), lists the government debts of 42 countries as percentages of their GDPs from 1995 to 2022. For these visualizations, I excluded Colombia because of insufficient data. In the three charts below, we see three different methods of visualization telling a data story about government debt. My professor chose the first two data visualization types while I chose the third one, though I did develop all the visualizations. 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OECD Data Viewer</title>
    <style>
        iframe {
            width: 100%;
            height: 600px;
            border: none;
        }
    </style>
</head>
<body>
    <iframe src="https://data-viewer.oecd.org?chartId=df4d404b-916b-43d1-b8b5-7c1eff05c684" allowfullscreen></iframe>
    <p>If the chart does not load, click <a href="https://data-viewer.oecd.org?chartId=df4d404b-916b-43d1-b8b5-7c1eff05c684" target="_blank" rel="noopener noreferrer">here</a> to view it.</p>
</body>
</html>


The bar chart, which the [OECD](https://data.oecd.org/) website produced for us, shows the government debts by country in ascending order on 2018. This visually communicates the vast variability of debt between countries. It also shows how much higher Japan and Greece's government debts are in contrast with the other countries. However, I also want to see how debt has changed across time while still seeing each country. A bar chart would be difficult to read/digest in such a context. For this reason, I produced the second visualization.

<div class='tableauPlaceholder' id='viz1706495489048' style='position: relative'><noscript><a href='#'><img alt='Visualizing the increase in government debt as a percentage of GDP ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingtheincreaseingovernmentdebtasapercentageofGDP&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='VisualizingtheincreaseingovernmentdebtasapercentageofGDP&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingtheincreaseingovernmentdebtasapercentageofGDP&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1706495489048');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


The highlight table shows each country's GDP from 1995 to 2022. I chose a diverging color palette, from blue (lowest) to orange (highest) and 100 set as the neutral / perfect in between. The color palette gives us a visual representation of the variability in debt between countries (much like the bar chart does with the heights of the rectangles). We also show the data in descending order to provide a readable visual story. On top of visibly seeing the variability between countries, this method allows us to see variability across time. The chart shows that government debt has generally been increasing overtime across the board. 

<div class='tableauPlaceholder' id='viz1706500011331' style='position: relative'><noscript><a href='#'><img alt='Changes in the government debts of the most and least indebted countries after the pandemic ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ch&#47;Changesinthegovernmentdebtsofthemostandleastindebtedcountriesafterthepandemic&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Changesinthegovernmentdebtsofthemostandleastindebtedcountriesafterthepandemic&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ch&#47;Changesinthegovernmentdebtsofthemostandleastindebtedcountriesafterthepandemic&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1706500011331');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


The third method of data visualization is a line chart (the one I chose). I was playing around with the data trying to identify stories that peaked my interest. Then I thought about the pandemic, and I wondered if there may have been a shift in governemnt debts after 2020. As a result, I took a confirmatory approach: **My goal was to confirm whether the pandemic had a short term impact on government debt. As part of the story, I also wanted to know if the impact was different between the most and least indebted countries.** 

**My approach:** I filtered the data to only show the top 5 and bottom 5 countries in the array. I chose a dark red for the top 5 (because debt = bad/loss and red = bad/loss) and a light pink for the bottom 5 (which I think makes intuitive sense). I placed a dotted line on 2020 labeled "Pandemic". I also chose to only include 2016-2022 to more clearly see the pandemic as the main character of the story. I chose a line chart because lines show trends, i.e., a line more clearly shows shifts over time in a visual manner. The highlight table can show this shift through the color gradient, but only to a limited extent. It can be hard for the audience to get a sense of how different each color shade is from each other. A bar chart can help with this, but because time is essential for my confirmatory experiment, it would not work. Therefore, I chose a line chart.

**Note:** Before describing the story told by my chart, I want to note a weakness in my approach. I'm not sure if the 2020 data for each country was collected as of the beginning, middle or end of the year. In other words, I don't know if it reflects debt after or before the pandemic or if data timing differs by country. That being said, I assume the data was collected at the end of 2020. 

**My conclusion:** The third chart shows a quick increase in government debt for the top 5 countries right after the pandemic, followed by a quick decrease in the following two years. Japan seems to be an outlier, since their debt remained relatively constant after the pandemic spike. However, the bottom 5 countries experienced a relatively small and seemingly constant positive shift in debt after the pandemic (the plot thickens... literally). Now, I did not perform statistical validation of significance, but it would be interesting to research the difference in impact between countries with high debts and countries with low debts this plot might show. 

| [Home Page](https://chrisbori.github.io/My-Online-Portfolio/) | [Eval-AI Model Check](https://chrisbori.github.io/My-Online-Portfolio/eval-ai) | [Puerto Rico's Act 22](https://chrisbori.github.io/My-Online-Portfolio/final-project-part-three) | [Visualizing Debt](https://chrisbori.github.io/My-Online-Portfolio/visualizing-government-debt) | [Everybody Poops](https://chrisbori.github.io/My-Online-Portfolio/critique-by-design) |
