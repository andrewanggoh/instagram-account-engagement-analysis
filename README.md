# Healthy Snack Brand: Instagram Engagement Analysis
Compiled by Andrew Oksner Anggoh | Tools: R and Tableau

### Table of Contents

- [Project Background](#project-background)
- [Objective](#objective)
- [Dataset Overview](#dataset-overview)
- [Executive Summary](#executive-summary)
- [Insight Deep-Dive](#insight-deep-dive)
   - [Top Posts by Engagement](#top-posts-by-engagement)
   - [Engagement Trends and Growth Rates](#engagement-trends-and-growth-rates)
   - [Engagement by Post Types](#engagement-by-post-types)
   - [Characteristics of High-Engagement Videos](#characteristics-of-high-engagement-videos)
   - [Impact of Video Duration on Completion Rate](#impact-of-video-duration-on-completion-rate)
   - [Impact of Influencer Collaborations on Engagement](#impact-of-influencer-collaborations-on-engagement)
- [Recommendations](#recommendations)
- [Clarifying and Key Questions for Further Analysis](#clarifying-and-key-questions-for-further-analysis)
- [Caveats and Assumptions](#caveats-and-assumptions)
- [Technical Details](#technical-details)
- [Contacts](#contacts)

## Project Background

AO Snack (*pseudonym*), a healthy snack brand, uses Instagram to build brand awareness and engage with its audience. I'm taking a role as a data analyst to extract insights and provide recommendations to the social media and marketing teams to drive higher engagement on the Instagram account.

## Objective

The main objective of this analysis is:

- **Content Engagement Analysis**: To identify and understand post characteristics, including topics, post types, and influencer involvement, that drive high audience engagement.

## Dataset Overview

The analysis is based on public Instagram content data from the AO Snack account, representing posts from December 2021 to March 2025 with details including post ID, timestamp, post owner, post type, and other attributes as shown in the image below.

<p align="center">
  <img width="346" height="931" src="https://github.com/user-attachments/assets/944fc905-0eeb-4a9a-b6ce-26ad6f446396">
</p>

***Disclaimer:*** *All account names and usernames displayed have been replaced with pseudonyms created using ChatGPT to protect the privacy of the original account holders. This anonymization prevents identity tracing, misuse of data, or harm to third parties. There is no association between these aliases and real Instagram accounts.*

## Executive Summary

- Videos tend to attract higher engagement than photos.
- Duration 15 > seconds engages more audience

## Insight Deep-Dive

### Top Posts by Engagement

- 9 out of 10 top-performing posts are videos, with only 1 being a static photo.
- All 10 high-engagement posts involved collaborations – either with influencers or complementary brands aligned with the brand image (e.g., sporty influencers, hampers brand, or sports events where our product adds value).
- Guntur’s appearance in five of the top posts suggests he is a key content creator** contributing significantly to engagement.

<p align="center">
  <img width="830" height="350" src="https://github.com/user-attachments/assets/0b3d04c2-fb3e-4e96-89c4-abbe8bab0a7a">
</p>

### Engagement Trends and Growth Rates

- From December 2021 to March 2025, there are huge spikes in June-July 2023, February 2024, May-June 2024, December 2024, and its increasing now in March 2025, with monthly engagement ranging from ~1.2K to ~368.6K. After those spikes, the engagement mostly has a big dip

### Engagements by Post Type

- There are several viral posts (as indicated by the outliers) with significantly higher engagement in clips compared to photos, and the maximum engagement for clips (222,262) far exceeds that of photos (66,628), indicating that clips have a higher potential for viral reach.
- Clips tend to generate higher engagement than photos, with a median of 361 compared to 129. Half of all clips achieve engagement above 361, while half of the photos fall below 129.
- Based on Q1 to Q3, clips (152-1022) show a broader spread of engagement compared to photos (67-247), meaning the middle 50% of clips have much higher engagement. This suggests clips are more likely to drive higher engagement, though variability is also greater.

<p align="center">
  <img width="913" height="687" src="https://github.com/user-attachments/assets/af2a5550-c1b8-4fb4-9025-e767c025dac3">
</p>

### Characteristics of High-Engagement Videos

- Longer videos tend to generate higher engagement, with the highest median seen in videos over 60 seconds (479), followed by those 45–60 seconds long (417). In contrast, very short videos (0–15 seconds) show the lowest median engagement, indicating that overly brief content may offer less value or appeal to the audience.
- The heatmap of median engagement across posting times suggests no strong pattern. Posting time does not appear to be a key driver of engagement.

### Impact of Video Duration on Completion Rate

- The highest average of completion rate is video with duration > 60 seconds (44.66%), followed by 30-45 seconds (38.96%), 45-60 seconds (38.72%), 0-15 seconds (37.66%), and 15-30 seconds (37.43%).

### Impact of Influencer Collaborations on Engagement

- Most of the time, the total engagement trend is influenced a lot by post with Influencers. For example, the spike through June - August 2023 is happening because post with an influencer.
- Median engagement count of post with inlfuencer approximately 2x higher than post without influencer.
- elziwai, celloszxz, and byoncombat are top 3 influencer that give highest engagement sum up.

## Recommendations

Note:

1. Every recommendation should be tied to an insight that we had. Link what you found to what you recommend.

   - ✅ Given the upward trend in electric letter openers and ... in the technology category. Consider reallocating the marketing budget for the next two years to focus on these products.
   - ❌ Expand Technology offerings: Leverage strong demand for technology products to maintain market leadership.
2. Tip: We can put a simple recommendation first, then put the detailed recommendations after it.
3. Our job is to communicate exactly what we discovered and what someone should do about it. So be specific!

## Clarifying and Key Questions for Further Analysis

- Is there

## Caveats and Assumptions

Note:

1. Contain a note about the data cleaning process that you did including any assumptions you had to make about the data.

## Technical Details

The technical analysis utilized:

- **R** for data cleaning, preparation, and exploratory data analysis. Documentation is available [here](https://rpubs.com/andrewanggoh/InstagramAccountAnalysis).
- **Tableau** for data visualization and an interactive dashboard, which is accessible [here]().

## Contacts

Thank you for reading through this project. Should you have any feedback, suggestions, or wish to collaborate further, feel free to reach out via email or connect with me on LinkedIn.

- LinkedIn: [@andrewoanggoh](https://www.linkedin.com/in/andrewoanggoh/)
- Gmail: andrew.anggoh@gmail.com
