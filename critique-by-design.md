[Home Page](https://ananthulalohitaksha.github.io/lohitaksha-ananthula-portfolio/) | [Global Debt Dynamics](./visualizing-government-debt.md) | [Critique by Design](./critique-by-design.md) | [Phase I: Discovery](./final-project-part-one.md) | [Phase II: Research](./final-project-part-two.md) | [Phase III: Synthesis](./final-project-part-three.md)

# Critique by Design: Coffee Caffeine Tracker

## Step 1: The Design Context

While exploring various articles on the Makeover Monday website, I came across the "High Street Coffee Caffeine Content Compared" visualization, which illustrated caffeine levels across popular coffee chains. I selected this particular data visualization as I was looking for a graphic that conveyed an important message but lacked effective visualization. The visualization stood out because it provided valuable insights for coffee drinkers, helping them understand how much caffeine they consume from different coffee chains.

<img src="Original%20Visualization.png" alt="Original Visualization" width="900" />

Source: [Which?](https://www.which.co.uk/news/article/caffeine-levels-in-high-street-coffees-vary-significantly-which-finds-ay7cA4G1zh1S)  

## Step 2: Heuristic Evaluation & Critique

As I assessed the "High Street Coffee Caffeine Content" visualization, I realized it effectively conveyed important information but still had areas for improvement. Here is my critique-

**_Observations_:**

Looking at the high street coffee caffeine content visualization, one thing that immediately stood out to me was the huge difference in caffeine levels between Costa's cappuccino (325 mg) and Starbucks' version (66 mg). On the other hand, I really liked how the table is presented in a neat and organized manner, with coffee chain names as rows and coffee types as columns, making comparisons easier. The use of a blue background with white text ensures good readability and creates an effective contrast.
However, I noticed a few issues. The filter/brewed coffee columns for Café Nero and Costa (Signature Blend) are missing, creating an impression of incompleteness. I also believe the visualization could have been improved by including the recommended daily caffeine intake for adults, as this would help compare the caffeine content of each drink to the suggested limit. Lastly, the visualization currently displays caffeine content in mg alongside drink size in ml, but this isn't very intuitive. Readers might find it clearer if it showed how much caffeine each drink contains.

**_Primary Audience_:**

The primary audience appears to be consumers who regularly purchase coffee from high street chains and want to be informed about caffeine content in their drinks.
This visualization is moderately effective for the audience because it provides clear, factual information in an organized format. The table layout makes it easy to compare caffeine levels across different chains and drink types. However, it could better serve the audience by making the information more intuitive and visually engaging. The current approach requires calculations to understand relative differences and lacks information on which options might exceed recommended caffeine content per day. I also believe that most coffee consumers would find it easier to understand caffeine content in terms of each drink's caffeine amount, rather than comparing caffeine content in mg and drink size in ml.

**_Recommendations for improving the current visualization:_**

In my redesign, I plan to move from a table format to a horizontal bar chart, which can make the information more visually engaging and easier to compare at a glance. I might explore using coffee chain logos to make the visualization more appealing. I also plan to reorganize the data by grouping the coffee drinks based on the highest caffeine content, rather than sorting them alphabetically by chain. To provide better context, I would include a reference line indicating the FDA/health authority’s recommended caffeine limit of 400 mg per day. Furthermore, I plan on incorporating a dropdown filter that allows users to select the type of coffee, the desired number of cups, and even customize the drink size. This would involve some mathematical calculations to ensure accuracy. I believe these changes could enhance both the clarity and the overall impact of the visualization.

## Step 3: Rapid Prototyping & Low-Fi Sketch

As I worked through my critique of the "High Street Coffee Caffeine Content" visualization, I initially thought it would be fairly easy to improve. However, as I started redesigning it, I realized that the changes I wanted to make, especially with the custom calculations and dropdown menus, felt more challenging than expected. Despite these challenges, I created a sketch for my redesign. My goal was to move away from the table format and use a more intuitive bar chart.

However, I didn’t post my redesign on Tableau Public yet, as I wasn’t fully confident in the final version. I wanted to take the time to gather feedback by conducting interviews and adding my own thoughts further to work on the final redesign. Here is my sketch:

<img src="Redesign%20Draft1.png" alt="Redesign Draft1" width="900" />

## Step 4: User Research & Usability Testing

I interviewed two students in their early 20s—one from the Master of Information Systems Management program and another, an undergraduate Computer Science student.

I conducted the interviews based on the following questions:

- Can you tell me what you think this is?
- Can you describe to me what this is telling you?
- Is there anything you find surprising or confusing?
- Who do you think is the intended audience for this?
- Is there anything you would change or do differently?

**Results-**

**Interviewee 1-**

- Can you tell me what you think this is?

A bar chart showing how much caffeine each type of coffee contains across different chains.

- Can you describe to me what this is telling you?

A visualization that helps determine whether we are hitting, exceeding, or staying within the recommended caffeine intake by comparing the same type of coffee across different chains.

- Is there anything you find surprising or confusing?

The write-up below the title mentions what is considered a safe caffeine intake per day for adults. However, the threshold is just a line, which makes it slightly confusing. X-axis labels are also missing.

- Who do you think is the intended audience for this?

Since popular coffee chains are included, I believe this is meant for regular coffee drinkers who want to keep track of their caffeine intake.

- Is there anything you would change or do differently?

Add an axis label and define the threshold with a number. The dropdown menu for drink types has large size options, which don't look great. A more effective title would make it more intuitive for the reader to understand the message.

**Interviewee 2-**

- Can you tell me what you think this is?

A visualization comparing different coffee brands, coffee types, and caffeine content.

- Can you describe to me what this is telling you?

Along with the visualization and filter options, I understand that we can choose the number of cups or enter the drink size and coffee type to see the caffeine content across different chains.

- Is there anything you find surprising or confusing?

I found the threshold line slightly confusing since there is no value.

- Who do you think is the intended audience for this?

Since it includes well-known coffee chains, it seems targeted at health-conscious individuals who want to monitor their caffeine intake when buying from these chains.

- Is there anything you would change or do differently?

Define the threshold with a numerical value. Use a different color scheme to highlight when caffeine intake exceeds the recommended limit. While experimenting with different drink sizes, I noticed that the caffeine content value sometimes extends beyond the bar, making it hard to read. To improve clarity, placing the caffeine content outside the bars could help.
 
**Synthesis:**

Both the interviewees found the threshold line slightly confusing due to the lack of x-axis labels and numerical values. One of them also pointed out that the dropdown menu design could be improved for a more polished look. One interviewee suggested using color differentiation to indicate when caffeine intake exceeds the limit, which could make the visualization more intuitive. I felt that all these inputs were valuable and something I could incorporate to enhance the visual appeal.
Based on the feedback, I plan to implement some design changes to improve the visualization. Adding x-axis labels and a numerical value to the threshold line will provide better context. Using color differentiation to highlight excessive caffeine intake will make the visualization more intuitive. These improvements will enhance clarity and the overall effectiveness of the visualization for consumers tracking their caffeine intake.

## Step 5: Final Synthesis & Deployment

<img src="Final%20Design.png" alt="Final Design" width="900" />

[Tableau Link-](https://public.tableau.com/views/CritiqueandRedesign_Lohitaksha/BarChart_FinalVersion?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

The final step of this project involved combining my critique, interview feedback, and personal insights to refine my data visualization. Each stage from initial critique to redesign sketches and user interviews played a role in shaping my final visualization. One of my primary objectives was to allow users to interact with the data by selecting their drink size, coffee type, and number of cups to determine their actual daily caffeine intake. More importantly, I wanted to help them understand whether their intake exceeded the recommended threshold. The original table format only provided caffeine content per drink size, but this information was inconsistent across different coffee chains. Additionally, there were missing data points for brewed/filter coffee from Café Nero and Costa. To ensure clarity, I decided to exclude the brewed/filter coffee category rather than present incomplete information. This allowed me to focus on a clearer comparison between two specific coffee types across five major brands.

For my sketch, to enhance the visual appeal and usability of my redesign, I used a custom coffee-inspired color palette that matched the theme. One of my biggest initial challenges was incorporating calculations for drink size, coffee type, and number of cups. To address this, I referred to a video by Andy Kriebel on redesigning the same visualization, which provided insights into similar calculations. I was able to compute Caffeine Intake (mg/day) using the formula: [Caffeine (mg/ml)] × [Drink Size] × [Number of Cups]. Once I had this measure, I worked on integrating a threshold filter that would indicate whether the user’s caffeine intake exceeded the recommended daily limit. I achieved this by implementing a threshold reference line—when users hover over a bar, a tooltip displays whether they have surpassed the limit.

Another major hurdle arose when I noticed inconsistencies in caffeine content values based on different drink sizes from the original dataset. Revisiting Andy Kriebel’s video helped me realize the importance of setting a filter condition to ensure that the correct caffeine values were displayed based on user selections. Initially, I considered replacing coffee brand names with logos, but I abandoned this idea as it disrupted the overall color scheme and cluttered the visualization.

Based on feedback from my interviews, I made several key improvements to the initial sketch. First, I added X-axis labels and set the axis range to automatic, ensuring that if a user entered an unusually high number of coffee cups, the visualization wouldn’t appear distorted. I also refined the title to "Tracking Caffeine Intake: Does Your Single-Shot Espresso or Cappuccino Exceed the Daily Limit?", making the purpose of the visualization clearer. To add credibility, I incorporated the FDA’s recommended daily caffeine limit. Additionally, I implemented a red-to-blue color diverging palette and set the center at 400 mg. If caffeine intake stayed within the limit, bars appeared blue; if it exceeded the limit, they turned red. This change made it visually intuitive for users to assess their caffeine consumption. Another important modification was adjusting the caffeine intake labels. Initially, I placed the values inside the bars, but I soon realized that Tableau’s automated text color adjustment, switching between black and white depending on the background made some values difficult to read. Additionally, when the bars were too small, the values would sometimes extend beyond the bar, making the visualization look cluttered and less effective. Instead, I moved the values outside the bars to ensure consistent readability.

There were a few changes I considered but ultimately did not implement. One of these was using color coding for "low," "moderate," and "high" caffeine levels. I initially thought about categorizing caffeine intake levels but realized that defining these thresholds subjectively might not be applicable to all users. Another suggested change by one of the interviewees was to adjust the dropdown menu size for better readability. However, after several attempts, I realized that this was likely an automatic Tableau setting that I couldn't really change.

Overall, this assignment was an engaging and insightful experience. It allowed me to critically evaluate an existing visualization, explore different design techniques, and refine my work based on feedback. By experimenting with Tableau’s interactive features, I gained a deeper understanding of data visualization best practices. I hope my final design will be useful for coffee drinkers who want to monitor their caffeine intake. The interactive elements make it easy for users to personalize their input and immediately see whether they are consuming a safe amount of caffeine. Lastly, I learned to balance aesthetics with clarity for an effective, insightful visualization.

## References

U.S. Food and Drug Administration. (n.d.). *Spilling the beans: How much caffeine is too much?* [Webpage]. U.S. Food and Drug Administration. [https://www.fda.gov/consumers/consumer-updates/spilling-beans-how-much-caffeine-too-much](https://www.fda.gov/consumers/consumer-updates/spilling-beans-how-much-caffeine-too-much)

Which?. (2023, January 31). *Caffeine levels in high street coffees vary significantly, Which? finds.* [News article]. Which?. [https://www.which.co.uk/news/article/caffeine-levels-in-high-street-coffees-vary-significantly-which-finds-ay7cA4G1zh1S](https://www.which.co.uk/news/article/caffeine-levels-in-high-street-coffees-vary-significantly-which-finds-ay7cA4G1zh1S)

Kriebel, A. (2023). *How caffeine addiction changed history* [Video]. YouTube. [https://www.youtube.com/watch?v=ybc_8PI0Nus&list=PLX-uPHRG0cLb697Ie-ZGSObRLLNhxzJGK&index=56](https://www.youtube.com/watch?v=ybc_8PI0Nus&list=PLX-uPHRG0cLb697Ie-ZGSObRLLNhxzJGK&index=56)


