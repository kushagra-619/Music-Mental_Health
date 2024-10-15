# Music-Mental-Health

## Project Overview
This project explores the relationships between music listening habits, preferences, and mental health factors using survey data. We aimed to uncover insights into how different genres of music, streaming services, and listening habits may be linked to mental well-being. The dataset contains information about respondents' age, music preferences, listening habits, and self-reported mental health scores.

## Goals
Investigate correlations between mental health factors (Anxiety, Depression, Insomnia, OCD).
Analyze the distribution of streaming service preferences across age groups.
Explore relationships between favorite music genres and mental health scores.
Examine how music listening habits correlate with mental health.

## Methodology
We utilized Python for data analysis and visualization, employing libraries such as pandas, numpy, seaborn, matplotlib, and plotly. Additionally, AWS Glue and Athena were used for data manipulation, allowing us to handle, clean, and transform the dataset efficiently. Our approach included:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Data visualization

## Key Findings
1. Mental Health Correlations (From Correlation Matrix): 
- Strong positive correlation (0.73) between Depression and Anxiety.
- Moderate positive correlations between Insomnia and both Anxiety (0.46) and Depression (0.48).
- OCD shows moderate positive correlations with Anxiety (0.45) and Depression (0.41).
- Age has weak negative correlations with most mental health indicators, suggesting slightly lower scores for these indicators as age increases.
- Hours per day listening to music has very weak correlations with mental health indicators, indicating no strong direct relationship.
2. Mental Health Indicators by Favorite Genre: 
- Anxiety: Hip hop and Metal fans show slightly higher median anxiety levels, while Classical and Jazz fans show lower levels.
- Depression: Metal and Rock fans tend to have higher depression scores, while Pop and Classical fans have lower scores.
- Insomnia: Metal and Rock fans report higher insomnia levels, while Classical and Country fans report lower levels.
- OCD: The differences are less pronounced, but Metal fans show slightly higher OCD scores.
3. BPM Distribution by Favorite Genre:
- EDM (Electronic Dance Music) has the highest median BPM, which is expected given the genre's characteristics.
- Classical and Jazz have lower median BPMs, consistent with their typically slower tempos.
- Rock, Metal, and Hip hop show wide BPM ranges, reflecting the diversity within these genres.
4. Music Genre Preferences: 
- Rock was the most popular genre, followed by Pop and Classical.
- A diverse range of genre preferences was observed among respondents.
5. Perceived Music Effects by Favorite Genre:
- Across all genres, most respondents report that music improves their mental health.
- Rock and Metal fans have a notably high proportion of respondents who say music "Improves" their mental health.
- Classical, Jazz, and EDM fans also show a strong tendency towards positive effects.
- The "No effect" category is relatively small across all genres, suggesting that most people perceive some impact from music on their mental health.
6. Music Listening Habits: 
- Many respondents listen to music while working.
- A mix of instrumentalists and non-instrumentalists was found among the respondents.
- Some respondents are composers, while others prefer exploratory listening.
7. Streaming Services and Age Groups
- Spotify was the most popular streaming service across all age groups.
- YouTube was particularly favored by teenagers.
- Apple Music gained more market share among older age groups.
8. Music Listening Habits
- Many respondents listen to music while working.
- A mix of instrumentalists and non-instrumentalists was found among the respondents.
- Some respondents are composers, while others prefer exploratory listening.

## Conclusions
Significant correlations exist between mental health factors, particularly between Anxiety and Depression.
Music preferences and listening habits vary across age groups, with Spotify being the most popular service.
Although some variations in mental health scores exist across genres, no clear causal relationship can be established.
The relationship between music and mental health is complex, influenced by factors such as age, listening habits, and personal responses to music.
Limitations and Future Work
The study is based on self-reported data, which may introduce bias.
The findings demonstrate correlations, not causation. Future studies are needed to explore causal relationships.
Future research could benefit from larger sample sizes and more detailed, experimental designs.
Investigating the impact of specific musical elements (e.g., rhythm, harmony, lyrics) on mental health could offer deeper insights.

## Overall Insights:

There's a clear relationship between different mental health indicators, with anxiety and depression showing the strongest correlation.
Music preferences seem to have some association with mental health indicators, with fans of more intense genres (like Metal and Rock) reporting higher levels of anxiety, depression, and insomnia.
Despite these associations, the vast majority of respondents across all genres report that music improves their mental health, highlighting its potential positive role.
Age has a slight negative correlation with mental health issues, suggesting that older respondents tend to report fewer problems.
The amount of time spent listening to music daily doesn't strongly correlate with mental health indicators, implying that quality and type of music might be more important than quantity.
These findings suggest that while there are associations between music preferences and mental health, music generally has a positive perceived effect across all genres. This information could be valuable for further research into music therapy and the use of music as a tool for mental health management.

## Tools Used
Python: For data analysis and visualization.
AWS Glue and Athena: For efficient data cleaning and manipulation.
Pandas
NumPy
Seaborn
Matplotlib
Plotly

*This project provides a comprehensive look at the intricate relationships between music and mental health, offering insights that could guide future studies in the field.*
