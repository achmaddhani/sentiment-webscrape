# Sentiment Analysis of Prabowo-Gibran's Presidential Candidacy Divergent Perspectives from Twitter and Online News Portals in Indonesia

## Objective 🎯

**Background:**

The sentiment analysis aims to gauge both the public opinion where feelings expressed on social media platforms, specifically Twitter and the news media outlet where information flows regarding these candidates' current political alliance and their active participation in the ongoing election campaign, leading up to the presidential and vice-presidential election scheduled for February 2024.

### 5W1H Key Factors 🤔:

**Who:**
- Prabowo Subianto and Gibran Rakabuming Raka, potential presidential and vice-presidential candidates.
- Google search on news published regarding the candidates
- Twitter users expressing opinions and sentiments about these potential candidates.

**What:**
- Sentiment analysis on Twitter and Google Search data discussing the alliance and active participataion of Prabowo and Gibran in the 2024 Indonesian election.
- Scrape tweets, scrape news title, analyzing the sentiment expressed, and understanding both the public opinion and the news outlet regarding this political alliance.

**When:**
- During the campaign leading up to the 2024 Indonesian election.
- Period of data collection is November 15th - December 15th of 2023.

**Where:**
- Twitter platform, particularly tweets written in Bahasa Indonesia, discussing #PrabowoGibran2024 or related hashtags.
- Google Search results of news based on the search keyword **Prabowo Gibran**
- Focus might extend to specific regions within Indonesia where opinions may vary.

**Why:**
- To understand public sentiment, feelings, and opinions toward the candidacy of Gibran and Prabowo.
- To provide insights into the potential political alliance's reception among the electorate.

**How:**
- Collecting tweets and news related to Prabowo Gibran and conducting sentiment analysis.
- Using Natural Language Processing (NLP) techniques to analyze the sentiment of tweets.
- Aggregating data, processing, and interpreting sentiment scores to derive insights.

**Problem Statement:**

Analyzing the sentiment polarity and intensity of both Twitter discussions and News published surrounding the Gibran-Prabowo alliance in preparation for the 2024 Indonesian election. The objective is to comprehend how public sentiment might impact their candidacy and overall political prospects as they actively engage in the ongoing election campaign leading up to the presidential and vice-presidential election scheduled for February 2024.

## Workflow 🛠️

- Brainstorming and Dataset Design
- Platform Exploration and Scraping
- Data Cleaning
- Exploring Benchmark Models in Natural Language Processing
- Text Processing
- Sentiment Analysis
- Data Engineering
- EDA
- Visualization and Dashboard

## Tableau links 📊

### Twitter Sentiment Analysis

- Dashboard 1 -> [Phrases and Hashtags Wordclouds](https://public.tableau.com/app/profile/faris.arief.mawardi/viz/prabowo-gibran_twitter_sentiment_analysis_1/DashboardI?publish=yes)
- Dashboard 2 -> [Sentiments Distributions and Topic Exposure Analysis](https://public.tableau.com/app/profile/faris.arief.mawardi/viz/prabowo-gibran_twitter_sentiment_analysis_2/Dashboard2?publish=yes)
- Dashboard 3 -> [Twitter Accounts Analysis](https://public.tableau.com/app/profile/faris.arief.mawardi/viz/prabowo-gibran_twitter_sentiment_analysis_3/Dashboard3?publish=yes)
- Dashboard 4 -> [Analysis of the Top 5 Twitter Accounts with the Highest Contribution of Tweets by Sentiment Category](https://public.tableau.com/app/profile/faris.arief.mawardi/viz/prabowo-gibran_twitter_sentiment_analysis_4/Dashboard4?publish=yes)

### Media Sentiment Analysis

- Dashboard 1 -> [Keyword (Word Cloud) and Sentiment Exposure Analysis](https://public.tableau.com/app/profile/achmad.dhani/viz/Prabowo-Gibran_Media_Analysis_Vis_1/Dashboard1)
- Dashboard 2 -> [Topic Exposure Analysis](https://public.tableau.com/app/profile/achmad.dhani/viz/Prabowo-Gibran_Media_Analysis_Vis_2/Dashboard2)
- Dashboard 3 -> [Media Outlet Sentiment Analysis](https://public.tableau.com/app/profile/achmad.dhani/viz/Prabowo-Gibran_Media_Analysis_Vis_3/Dashboard3?publish=yes)

## Conclusion 🏁

### Twitter Sentiment Analysis Conclusions:

1. **Main Discussion Themes and Focus:**
   - The discussions on Prabowo-Gibran primarily revolve around support for their victory or progress, religious or spiritual affiliations, and connections with specific political parties.

2. **Variation in Sentiment Levels:**
   - Significant variations in sentiments within the discussions, ranging from positive and neutral to negative, indicate a diverse range of opinions. Certain accounts contribute significantly to each sentiment category.

3. **Fluctuations in Tweeting Activity:**
   - Daily tweet patterns exhibit significant fluctuations, with sharp increases and decreases on different days, suggesting certain events or topics gain temporary focus.

4. **Daily and Weekly Activity Patterns:**
   - Tweeting tends to increase and peak on weekends, with lower activity at the start of the workweek, reflecting a dynamic engagement pattern.

5. **Variations in Account Participation:**
   - The number of accounts participating in these discussions varies significantly day-to-day, with periods of both high and low engagement, indicating varying levels of interest.

6. **Impact of High-Follower Accounts:**
   - Verified accounts with a high number of followers tend to receive higher engagement, highlighting the influence of such accounts in shaping discussions.

7. **Importance of Engaging Content:**
   - Engaging, relevant content emerges as a key factor in increasing engagement levels, irrespective of tweet frequency or follower count.

### Media Sentiment Analysis Conclusions:

1. **Neutral Sentiments Dominate Media Coverage:**
   - The 'Neutral' sentiment prevails in the dataset, with 1,925 news publications, suggesting that the majority of news articles about Prabowo and Gibran's candidacy maintain a neutral stance.

2. **Significance of Several Media Platforms:**
   - Certain media portals, such as detikNews, Antaranews.com, Kompas.com, and Politik, stand out with a higher number of publications compared to others, indicating their significance in the media landscape.

3. **Top Publishing Platforms by Sentiment:**
   - Positive sentiment is led by platforms like Tribun Jabar, Tribunnews.com, and Rilis ID. Neutral sentiment is dominated by Antaranews.com, detikNews, and KOMPAS.com. Negative sentiment is observed in outlets like Kilat, JPNN.com, and KOMPAS.tv.

4. **Most Frequent Keywords:**
   - Prominent phrases like 'prabowo', 'gibran', 'support', 'campaign', 'ganjar', 'presidential election', 'jokowi', and 'anies' reveal a focus on the candidates, their support, competitors, predecessors, and related campaign issues.

## Credits 🙌

- **Twitter Scraping:** [tweet-harvest](https://github.com/helmisatria/tweet-harvest) by Helmi Satria

- **Text Preprocessing:** [NLP_bahasa_resources](https://github.com/louisowen6/NLP_bahasa_resources) by Louis Owen

- **Hugging Face Model:** [indonesian-roberta-base-sentiment-classifier](https://huggingface.co/w11wo/indonesian-roberta-base-sentiment-classifier) by Wilson Wongso

