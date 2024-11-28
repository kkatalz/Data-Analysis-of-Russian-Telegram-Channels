# Data-Analysis-of-Russian-Telegram-Channels
This project provides an in-depth exploratory data analysis (EDA) of a dataset containing posts from Russian Telegram news channels. The goal of this analysis was to uncover trends, behavioral patterns, and engagement dynamics while investigating sensitive topics, keywords, and toxicity in the content. The analysis serves as inspiration for researchers, developers, and data enthusiasts to explore similar datasets and derive insights.

# Data Source
The data, that is used in the project, was collected from Russian Telegram news channels by university's student and contains various fields such as:
id, date, views, reactions, message, type, sensitive-topic, and toxicity.

# Technology and Tools Used
This project was developed using Python in a Jupyter Notebook environment, employing the following tools and libraries:

- _pandas_ for data manipulation.
- _numpy_ for numerical computations.
- _matplotlib_ and seaborn for creating charts and heatmaps.
- re for regex-based text parsing.
- _Counter_ from _collections_ for keyword analysis.
- _tabulate_ for presenting tabular data.
- **DB Browser** _to explore large CSV files._

# Usage Instructions
While the dataset itself is not included due to the author's intellectual property, this project can serve as inspiration for individuals analyzing similar datasets. The notebook answers key questions and demonstrates how to approach data exploration.

Example Questions You Can Answer:
- How do specific keywords or narratives trend over time?
- Which sensitive topics receive the highest engagement?
- What are the patterns of engagement by time of day or day of the week?
- How does post toxicity impact views or reactions?

If your dataset contains the following columns:
_id, date, views, reactions, to_id, fwd_from, message, type, datetime, message_len, sensitive-topic, toxicity,_ etc., you can adapt this analysis to answer similar questions.

_For comforable browsing usage, it is recommended to download provided .html file._

# Representation of Insights
This project uses a variety of visualizations to represent the insights, including:

- Heatmaps: To explore patterns like monthly post occurrences or views over time.
- Bar Charts: For sensitive topic distributions and engagement by time.
- Pie Charts: To depict toxicity distributions or keyword dominance.
- Bigram Frequency Charts: For identifying recurring word pairs in posts.

Feel free to adapt this project or use it as inspiration for similar datasets. 
