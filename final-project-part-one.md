| [Home Page](https://ananthulalohitaksha.github.io/lohitaksha-ananthula-portfolio/) | [Data Viz Examples](dataviz-examples) | [Visualizing Government Debt](visualizing-government-debt) | [Critique By Design](critique-by-design) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) |

> Important note: this template includes major elements of Part I, but the instructions on Canvas are the authoritative source.  Make sure to read through the assignment page and review the rubric to confirm you have everything you need before submitting.  When done, delete these instructions before submitting.

# Outline
This project explores the nutritional, environmental, and financial benefits of vegetarian-based protein sources. A common myth is that vegetarian diets don’t provide enough protein, but this project aims to clear up that misunderstanding. By examining a variety of plant-based proteins such as lentils, beans, tofu, and paneer, and comparing them to popular animal-based proteins like chicken and beef, the project offers a clear picture of how much protein vegetarian foods can really provide.

The main goal is to show that a well-balanced vegetarian diet can meet daily protein needs. In fact, plant-based proteins offer several health benefits. They can support better overall health, help with weight management, and reduce the risk of chronic diseases such as heart problems, diabetes, and certain types of cancer.
Beyond nutrition, the project also looks at the environmental and cost benefits of choosing vegetarian proteins. It compares the carbon footprint, water usage, and land needed to produce plant products versus meat products. 

To make this shift easier for people, the project includes practical tips for adding more protein-rich vegetarian foods into daily meals. This includes simple meal planning advice and easy ways to incorporate plant-based options into everyday eating. 

Lastly, the project also focuses on people who are considering reducing their meat consumption, even if they’re not going fully vegetarian. Campaigns like “Meatless Mondays” are a great starting point, and this project will support such efforts by providing useful information and encouragement for these people.

**_Story Board_:**

<img src="Story%20Arc.png" alt="Original Visualization" width="900" />

The story begins with a common concern: whether vegetarian diets can truly provide adequate protein. Using evidence and data, I aim to challenge this misconception and demonstrate that a well-planned plant-based diet can meet all nutritional needs. The narrative then explores a detailed nutritional breakdown, comparing plant- and animal-based proteins, with a special focus on essential amino acids and how vegetarians can achieve a complete profile through effective food pairings. Beyond nutrition, the story highlights the health benefits of plant based protein, followed by a look at the environmental advantages, including lower greenhouse gas emissions and more sustainable resource use. Lastly, globally inspired recipes for protein-rich vegetarian meals will be presented to make implementation easy and enjoyable. 

## Initial sketches

**_Sketch 1- A Comparative Analysis of Meat vs. Plant-Based Protein Intake_:**

<img src="Sketch%201.png" alt="Original Visualization" width="900" />

This is a rough sketch I created using Python's matplotlib to visually compare protein content in various food sources using a horizontal bar chart. I plan to add more food sources and incorporate interactive filters, allowing the audience to select and compare protein content based on preferences such as protein type (plant vs. animal), protein content range, food categories (e.g., legumes, meat, dairy), the option to compare multiple foods, and adjust for different serving sizes.

Source: Data points were collected through Google Search.

**_Sketch 2- Essential Amino Acid Profile Comparison: Animal vs. Plant-Based Proteins_:**

<img src="Sketch%202.png" alt="Original Visualization" width="900" />

This is a rough sketch I created using Python's Matplotlib. The stacked area chart compares the amino acid content of various protein sources, including both animal-based and plant-based proteins. Purpose is to highlight how some plant-based proteins may be deficient in certain key amino acids or contain them in lower quantities. This will help the audience understand the challenges of relying only on individual plant-based proteins for complete nutrition.

I plan to include a table in my final project showing strategic food pairings that address these gaps. I also plan to expand the chart to include a wider range of foods, helping users to make more informed dietary decisions.

Note: The y-axis values in this chart were generated using a ChatGPT prompt and are for illustrative purposes only. For the final version, I will use data from the USDA FoodData Central Database.

**_Sketch 3- Health Benefits of Vegetarian Protein Food Options_:**

<img src="Sketch%203.png" alt="Original Visualization" width="900" />

This is a rough sketch I created using Python's Matplotlib. This  is a horizontal bar chart showcasing some key findings from the study "Health Benefits of Vegetarian Diets: An Insight into the Main Topics" by Luciana Baroni, Gianluca Rizzo, Alexey Vladimirovich Galchenko, Martina Zavoli, Luca Serventi, and Maurizio Battino. For my final visualization, I plan to make it more interactive and user-friendly, allowing viewers to explore the data in greater detail. The goal is to help the audience better understand how these statistics were gathered and the benefits of a vegetarian diet.

**_Sketch 4- Green House Gas Emissions by Food Type: Visualizing Environmental Impact_:**

<img src="Sketch%204.png" alt="Original Visualization" width="900" />

This is a rough sketch I created using Python's Matplotlib. Goal is to visualize GHG emissions per kilogram for different foods, with bubble size representing emission levels. While the chart gives a general idea, larger bubbles indicating higher emissions, it’s not easy to read exact values. For the final version, I plan to use the bubble chart visualization on Tableau for better clarity and interactivity. Viewers will be able to hover over each bubble to see detailed data. Lastly, I also plan to incorporate land use and water use for different foods for a more complete environmental comparison.

Source: Ritchie, H., Rosado, P., & Roser, M. (2022). Environmental impacts of food production. Our World in Data. https://ourworldindata.org/environmental-impacts-of-food

**_Sketch 5- Protein-Rich Vegetarian Meal Plan_:**

<img src="Sketch%205.png" alt="Original Visualization" width="900" />

This is a rough infographic in a table format I made on Google Docs. This showcases three high-protein vegetarian meals from around the world. I plan to expand this by incorporating more cuisines from different regions globally. The dish names will be hyperlinked and appear in blue, allowing easy access to the recipe sources. The estimated cost is based on a rough calculation of ingredient prices in U.S. supermarkets.

Sources- 
1. Pallotta, N. (2025). 40 High Protein Vegetarian Meals. The Plant Based School. https://theplantbasedschool.com/high-protein-vegetarian-meals/
2. Momaya, A. (2024, November 22). Protein rich food – vegetarian diet plan, Indian recipes. HealthifyMe. https://www.healthifyme.com/blog/7-high-protein-indian-vegetarian-foods/

# The data 

| Name | URL | Description |
|------|-----|-------------|
|   USDA FoodData Central Database |  U.S. Department of Agriculture, Agricultural Research Service. (n.d.). Downloadable data. FoodData Central. https://fdc.nal.usda.gov/download-datasets​ | The USDA FoodData Central provides nutritional data on various foods, including protein content and quality. Will be helpful in building a comparative chart of protein content in plant-based versus animal-based foods.   |
|  Plant Proteins: Assessing Their Nutritional Quality and Effects on Health and Physical Function    |    Hertzler, S. R., Lieblein-Boff, J. C., Weiler, M., & Allgeier, C. (2020). Plant proteins: Assessing their nutritional quality and effects on health and physical function. Nutrients, 12(12), 3704. https://doi.org/10.3390/nu12123704 |        This article details the amino acid content of various plant proteins, which will help assess the nutritional quality of plant-based protein foods.  |
|   Health Benefits of Vegetarian Diets: An Insight into the Main Topics   |    Baroni, L., Rizzo, G., Galchenko, A. V., Zavoli, M., Serventi, L., & Battino, M. (2024). Health benefits of vegetarian diets: An insight into the main topics. Foods, 13(15), 2398. https://doi.org/10.3390/foods13152398​MDPI+4 |   This research paper outlines the health benefits of vegetarian diets, including reduced risk of chronic diseases and overall health improvements. This will support the health aspect of my project, providing scientific evidence for the benefits of plant-based protein. |
|   Environmental Impacts of Food Production |  Ritchie, H., Rosado, P., & Roser, M. (2022). Environmental impacts of food production. Our World in Data. https://ourworldindata.org/environmental-impacts-of-food​ | This dataset compares the environmental footprint of plant-based versus animal-based protein sources across various metrics, such as greenhouse gas emissions, land use, water use, and eutrophication. It will help me build the bubble chart, showing the sustainability benefits of choosing plant-based foods.   |
|   Protein Rich Food – Vegetarian Diet Plan, Indian Recipes |  Momaya, A. (2024, November 22). Protein rich food – vegetarian diet plan, Indian recipes. HealthifyMe. https://www.healthifyme.com/blog/7-high-protein-indian-vegetarian-foods/​ | This resource provides a list of high-protein vegetarian foods from an Indian cuisine perspective. Since I’m from India, this source is particularly relevant for including culturally specific vegetarian protein options. Audiences can explore meal plans that align with Indian dietary preferences.  |
|   40 High Protein Vegetarian Meals |  Pallotta, N. (2025). 40 High Protein Vegetarian Meals. The Plant Based School. https://theplantbasedschool.com/high-protein-vegetarian-meals/ | This list provides practical meal preparation recipes that incorporate high-protein vegetarian foods. It will serve as a helpful resource for providing meal planning tips to the audience.   |
|   Meatless Monday |  The Monday Campaigns. (n.d.). Meatless Monday. https://www.mondaycampaigns.org/meatless-monday|  I will provide this link at the end of my story for my audience to explore. This link introduces the concept of Meatless Monday and offers helpful resources, including recipes and toolkits. It also provides an option to subscribe to a monthly newsletter and join the movement.  |

# Method and medium

For my final project, I plan to use Shorthand to create a visually engaging, interactive website that presents my research in a storytelling format. I will integrate Tableau for data visualizations, allowing users to explore nutritional, environmental, and financial comparisons more intuitively. Together, these tools will aid in building an informative, user-friendly experience that encourages sustainable, plant-based protein choices.

## AI acknowledgements
For sketches 1 - 4, I used ChatGPT to help write the Python code for generating the visualization.
