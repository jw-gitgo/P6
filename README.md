## P6
### Summary
This data visualization explores whether the world is really getting more dangerous to live in (a commonly held belief, from my experience), based on publicly-available data from the World Health Organization.  The key metric used to explore this is the percentage of total deaths that are caused by external factors, as defined by the International Classification of Diseases (ICD) standards.  "External Factors" refers to all causes of death other than internal diseases and symptoms:  transport accidents, household accidents, falls, homicide, warfare, terrorism, intentional self-harm, etc.

### Finding
The finding of the visualization is that the world does NOT actually appear to be getting more dangerous.  For the past 30+ years, the percentage of deaths caused by external factors has remained fairly constant around 8 or 9%.  Given that many countries did not report data, this is certainly not a complete dataset, but as long as it is at least somewhat representative, it paints a much more positive picture than the impression many people get from the media and 24-hour news stations.  While death is rarely a welcome experience, this suggests that 91-92% of the world population at least meet their end in a non-violent manner.

### Design
Initially I tried to show multiple metrics broken down by country (overall death rate, external factor death rate excluding intentional self-harm, intentional self-harm death rate, and expected lifespan), all on the same graph.  While this did seem to suggest some overall trends, the graph was simply too busy, and it was made even more confusing by the fact that some metrics used different units (death rate per 100,000, death rate per 10,000, and age in years).  It also grouped the line colors by metric instead of by country, so it was difficult to compare countries.

My second attempt used the same metrics, but I limited the number of countries, grouped/colored the metrics by country, and allowed the viewer to select and deselect countries in the legend in order to add or remove data from the graph.  I also animated the chart to initially show all the data for a few seconds, then remove everything except for the world averages (the "martini-shaped" narrative structure).  This certainly made the visualization more readable, but the presence of multiple metrics and units still made interpretation difficult.  This led me to produce my final version, which consolidates the death rates into a single ratio, and removes the life expectancy metric.

### Feedback
Respondent A (on first version):  I had to provide some pretty detailed explanation for her to understand the purpose and structure of this visualization.  Once she understood it, she though she could see some fairly interesting trends in the data, but she didn't think it was clear enough to answer the question definitively.

Respondent B (on the second version):  My second critic understood the purpose of the visualization, but he was curious about and somewhat confused by the different metrics.  He also found interpretation difficult because he had to mouse over the data points to understand which metric he was looking at.  He thought that the visualization could potentially answer the question, but it required the viewer to do some digging and quick mental calculations on their own.

Respondent C (on the final version):  I provided minimal explanation this time, but he was still able to understand the purpose and structure of the visualization.  The added subtitles and text also helped to make the data and methodology clear.  I considered his feedback very positive when he almost immediately starting clicking through the visualization out of his own interest.  He agreed that it provided some interesting insights on the question posed.

### Resources
<li>http://dimplejs.org
<li>http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends
<li>https://d3js.org/
<li>http://stackoverflow.com/
<li>http://apps.who.int/healthinfo/statistics/mortality/whodpms/
<li>http://databank.worldbank.org/data/home.aspx

