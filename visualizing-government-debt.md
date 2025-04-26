| [Home Page](https://ananthulalohitaksha.github.io/lohitaksha-ananthula-portfolio/) | [Data Viz Examples](dataviz-examples) | [Visualizing Government Debt](visualizing-government-debt) | [Critique By Design](critique-by-design) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) |

# Global Government Debt Comparison

## Part 1: Working with web-based visualization tools and data
This is the original visualization from the OECD website-

<img src="Part%20one.png" alt="Part One" width="800" />

## Part 2: Working with Tableau
Heatmap of GDP-to-Debt Ratio Over Time-
<div class='tableauPlaceholder' id='viz1742775716886' style='position: relative'>
    <noscript>
        <a href='https://public.tableau.com/views/VisualizingGovernmentDebt_17426937908540/Sheet1'>
            <img alt='Historical Overview: Government Debt-to-GDP Ratio (1995-2019) General government debt | OECD. Accessed March 22, 2025 https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2023' 
                 src='https://public.tableau.com/static/images/Vi/VisualizingGovernmentDebt_17426937908540/Sheet1/1_rss.png' 
                 style='border: none;' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='VisualizingGovernmentDebt_17426937908540/Sheet1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/Vi/VisualizingGovernmentDebt_17426937908540/Sheet1/1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
        <param name='filter' value='publish=yes' />
    </object>
</div>

<script type='text/javascript'>
    var divElement = document.getElementById('viz1742775716886');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Part 3: Create your own visualization
After reviewing the original dataset and visualization, the first thought that came to my mind was to analyze the impact of the global financial crisis (2007-2008) and its aftermath on the debt-to-GDP ratio from 2009 to 2012. Initially, I considered focusing on the five most impacted countries, but then I realized that the dataset would be too small. Therefore, I decided to include all countries and observe the broader impact.

I chose a bubble chart to visualize the data. The title of the chart is: "Government Debt Trends: The Global Financial Crisis and Its Aftermath (2009-2012)". This title captures the essence of the analysis. I also added a filter for specific years, allowing users to explore individual years or view the data for all years combined. When multiple years are studied, I used the average aggregation.

For the color scheme, I chose a red-blue diverging palette, with red representing higher debt ratios, orange indicating medium debt ratios, and blue signifying lower ones. This helps distinguish high, medium, and low debt burdens. Additionally, I sorted the countries by their debt-to-GDP ratios in descending order. This sorting places the most impacted countries at the center of the chart, with countries less impacted by the crisis surrounding them.

One key observation is that Japan had a consistently increasing debt-to-GDP ratio. I closely studied the trends from 2007–2012, the period surrounding the global financial crisis. Through an article, I found that Japan’s economic challenges were largely due to a huge decline in export demand, particularly in motor vehicles. This decline was caused by reduced consumer spending in key markets like the U.S.

Overall, the visualization provides a comprehensive view of government debt trends during the global financial crisis and its effects in the years that followed.

<div class='tableauPlaceholder' id='viz1742776287865' style='position: relative; width: 100%; margin: 0 auto; display: block;'>
    <noscript>
        <a href='#'>
            <img alt='Government Debt Comparison: The Global Financial Crisis and Its Aftermath (2009-2012) Government debt-to-GDP ratios measure the size of a country\'s debt relative to its economic output, providing insight into its fiscal health. During the aftermath of the ' 
                 src='https://public.tableau.com/static/images/Bo/Book1_17427761344300/Sheet1/1_rss.png' 
                 style='border: none;' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none; width: 100%; height: 100%;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='Book1_17427761344300/Sheet1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/Bo/Book1_17427761344300/Sheet1/1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
    </object>
</div>

<script type='text/javascript'>
    var divElement = document.getElementById('viz1742776287865');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';  // Maintain 75% height ratio
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


## References
1. OECD. Accessed March 22, 2025 https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2023Links to an external site.
2. Jun SAITO    &nbsp Senior Research Fellow, & SAITO, J. (2018, October 1). Why was Japan struck so hard by the 2008 crisis?. 公益社団法人　日本経済研究センター:Japan Center for Economic Research. https://www.jcer.or.jp/english/why-was-japan-struck-so-hard-by-the-2008-crisisLinks to an external site
