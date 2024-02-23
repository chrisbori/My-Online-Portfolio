| [home page](https://chrisbori.github.io/My-Online-Portfolio/) | [visualizing debt](https://chrisbori.github.io/My-Online-Portfolio/visualizing-government-debt) | [critique by design](https://chrisbori.github.io/My-Online-Portfolio/critique-by-design) | [final project I](final-project-part-one) | [final-project-part-two](https://chrisbori.github.io/My-Online-Portfolio/final-project-part-two) | [final project III](final-project-part-three) |

# Everybody poops, but not everybody washes their hands

## Step 1: Choose a data visualization
I browsed different articles within the Makeover Monday link for about 30 minutes, and many of these were insteresting. However, when I read the title "Everybody poops", I needed to know more. I found the following chart claiming that men are less likely to wash their hands after going to the toilet, which I instantly believed because I know my people (PS: they don't represent me). I chose my target. 

![image](https://github.com/chrisbori/My-Online-Portfolio/assets/157328962/94488024-1aca-4e74-b6bc-834cdd40ede2)

## Step 2: Critique the data vizualization
I already submitted the Google form, but to recap, here were my main critiques:
* the color choice for women stood out more than men, who I believe were supposed to be the main character
* the main objective of the story felt loss in the volume of information provided
* there are more insights for men than for women, which may be dramatizing the contrast between the two

My main objective with the redesign is to better highlight the comparison between the genders (mainly that men wash their hands less).

## Step 3: Sketch out a solution
I came up with three sketches, which I then rated as "simple, but engaging", "simple, but not engaging" and "coolest", respectively. 

![WhatsApp Image 2024-02-04 at 14 24 46_9e88a851](https://github.com/chrisbori/My-Online-Portfolio/assets/157328962/7a21bf78-e7c4-4474-b29c-461471b6618a)

# Step 4: Test the solution
I contacted two friends to give me feedback on my sketch:
* student, mid 20's
* student, 30ish (in Telling Stories w/ Data)

The first critic liked the diverging bar the best. They understood the comparative story I was trying to tell with the first two sketches. However, she was very confused about the third sketch. She also advised adding something to clarify who the data represents (my initial title did not specify this data is from the UK). The second critic gave the same feedback (he also said he was disapointed at men). 

Based on this, I chose the diverging bar chart and decided to include the location/date in the title: "Men in the UK are less likely to wash their hands after going to the toilet in 2017"

# Step 5: Build your solution
<div class='tableauPlaceholder' id='viz1707278002518' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;9R&#47;9RBT8F4KW&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;9RBT8F4KW' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;9R&#47;9RBT8F4KW&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1707278002518');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else { vizElement.style.width='100%';vizElement.style.height='727px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

So, when I looked at the data provided through Makeover Monday, there was much less than I expected. I thought there would be more data (e.g., the original chart included standing wee and sitting wee, but this was not in the file). There were only three scenarios in the data: while at work, while at home, and while out:

![image](https://github.com/chrisbori/My-Online-Portfolio/assets/157328962/2341fa73-64c4-4bb7-bfbc-d2c2f9cf9c14)

I struggled a bit with making the diverging chart (I'm a Tableau amateur), but I figured it out. Initially, I was only going to show the percentage of men and women who always washed their hands per scenario, but then I noticed that people actually reported they _never_ wash their hands. I had to include that in the story (because wild). I added the whole spectrum (always, most of the time, sometimes, rarely, never and don't know) into stacked bars. 

However, then I struggled to find how to make the men side a different color story from the other side. It took me an embarassing amount of time, but I figured out that I needed to make an additional legend for men. I chose blue teal for men and a pinkish purple for women (the more often they washed their hands, the darker the color). I also grayed out the "Don't know" response. 

I decided to merge/rename some of the responses to improve perceptibility:
* always + mostly = Always/Mostly
* sometimes + rarely = Sometimes
* never = You need to do that?

Afterwards, I uniquely labeled the percentages of the "Always/Mostly" responses to emphasize this as the main takeaway. At this point, I realized something awkward: there was not much of a difference between the percetage of men women that always/mostly wash their hands (which contradicts the orginal chart). There are two reasons I think this may be the case:
1. I merged always/mostly. The original chart leaves the always response as a standalone in their stacks.
2. The original chart visually overdramatized the difference between the two genders by including more insights for men than for women (I noted this in my initial critique). 

The story changed, so I changed the title to what it is now: "Were men in the UK really more likely to wash their hands after going to the toilet in 2017?" My sincere apologies to my bretheren; it's all genders being nasty. 

Then I added some finishing touches:
* I removed the column name of the scenarios as well as the axis labels (I think title gave enough for quick interpretation)
* I removed the percentage numbers from the axis to only include 100% and 0%
  - I tried to figure out how to only include one 0 instead of two, but I let it go (this time).
* I removed gridlines and reference lines.

I was going to leave it at that, but I hated the two legend keys. I thought they increased eye travel and reduced perceptibility. I decided to be extra and fix that, so I looked up some YouTube videos and found a fitting solution. I created two additional sheets with copies of each legend. I put each legend in the Marks box and columns input in their respective sheet. Then I made the shapes be squares and played with their sizes until I was satisfied. To add them as legends to the chart, I had to make a dashboard and combine all of the sheets. Once I added the source, I published and called it a night.

I hope you like this!... Well, not that some people don't wash their hands, just the redesign. 
