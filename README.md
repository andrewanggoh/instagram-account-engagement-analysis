# Healthy Snack Brand: Instagram Engagement Analysis
Compiled by Andrew Oksner Anggoh | Tools: R and Tableau

### Table of Contents

- [Project Background](#project-background)
- [Objective](#objective)
- [Dataset Overview](#dataset-overview)
- [Executive Summary](#executive-summary)
- [Insights Deep-Dive](#insights-deep-dive)
   - [Top Posts by Engagements](#top-posts-by-engagements)
   - [Engagement Trends and Growth Rates](#engagement-trends-and-growth-rates)
   - [Engagements by Post Types](#engagements-by-post-types)
   - [Engagements and Completion Rates by Video Durations](#engagements-and-completion-rates-by-video-durations)
   - [Engagements by Posting Times](#engagements-by-posting-times)
   - [Impact of Collaborations on Engagements](#impact-of-collaborations-on-engagements)
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

The analysis is based on public Instagram content data from the AO Snack account, representing posts from January 2022 to March 2025 with details including post ID, timestamp, post owner, post type, and other attributes as shown in the image below.

<p align="center">
  <img width="346" height="931" src="https://github.com/user-attachments/assets/944fc905-0eeb-4a9a-b6ce-26ad6f446396">
</p>

***Disclaimer:*** *All account names and usernames displayed have been replaced with pseudonyms created using ChatGPT to protect the privacy of the original account holders. This anonymization prevents identity tracing, misuse of data, or harm to third parties. There is no association between these aliases and real Instagram accounts.*

## Executive Summary

- Videos tend to attract higher engagement than photos.
- Duration 15 > seconds engages more audience

## Insights Deep-Dive

### Top Posts by Engagement

- From Jan 2022 to Mar 2025, 9 out of 10 top-performing posts are videos and only 1 is a photo-type post.
- All 10 high-engagement posts involved collaborations – either with influencers or complementary brands aligned with the brand image (e.g., sporty influencers, hampers brand, or sports events where our product adds value).
- Wilson Nate’s appearance in five of the top posts suggests he is a key content creator contributing significantly to engagement.

<p align="center">
  <img width="830" height="350" src="https://github.com/user-attachments/assets/cb98b6b3-f73f-4c37-8082-7e165bc8ec02">
</p>

### Engagement Trends and Growth Rates

- Between Jan 2022 and Mar 2025, monthly engagement ranged from ~1.2K to ~368.6K.
- Major spikes occurred in Jun–Jul 2023, Feb 2024, May–Jun 2024, Dec 2024, and another rise starting in Mar 2025, with most spikes being followed by sharp declines.
- The highest peak in June–July 2023 exceeded 350K, likely driven by viral content or major campaigns.
- Engagement in 2024 saw multiple peaks (200K–260K), suggesting an event-driven or seasonal trend, which will be discussed further in the *[Engagements by Collaborations](#engagements-by-collaborations)* section below.

<p align="center">
  <img width="750" height="650" src="https://github.com/user-attachments/assets/781e0775-aec6-4d45-96d8-50467009d79c">
</p>

### Engagements by Post Types

- Overall engagement trends are largely driven by video-type posts. The spikes that appear are dominantly influenced by engagement from video-type posts.
- There are several viral posts with significantly higher engagement in clips compared to photos, and the maximum engagement for clips (222,262) far exceeds that of photos (66,628), indicating that clips have a higher potential for viral reach.
- Clips tend to generate higher engagement than photos, with a median of 361 compared to 129. Half of all clips achieve engagement above 361, while half of the photos fall below 129.
- Based on Q1 to Q3, clips (152-1022) show a broader spread of engagement compared to photos (67-247), meaning the middle 50% of clips have much higher engagement. This suggests clips are more likely to drive higher engagement, though variability is also greater.
- Statistical analysis confirms that the difference in engagement between clips and photos is significant, reinforcing that clips are generally more effective at driving interactions.

<p align="center">
  <img width="913" height="687" src="https://github.com/user-attachments/assets/af2a5550-c1b8-4fb4-9025-e767c025dac3">
</p>

### Engagements and Completion Rates by Video Durations

- Videos longer than 15 seconds generally drive higher engagement, with medians ranging from 315 to 479, while videos shorter than 15 seconds record the lowest median engagement (148). This indicates that longer formats can generate roughly 2-3x more interactions, suggesting overly brief content may offer less value or appeal to the audience.
- The highest average completion rate is for videos over 60 seconds (44.66%), while the other durations fall within 37.43%–38.96%, indicating that videos of 60 seconds or longer tend to deliver a 5–7% higher retention rate.

<p align="center">
  <img width="913" height="687" src="https://github.com/user-attachments/assets/2d29304c-a61f-4f35-995c-f508046f37d9">
</p>

### Engagements by Posting Times

- The heatmap of median engagement across posting times suggests no consistent pattern. While certain time slots (e.g., 4 AM Sunday and 3 AM Tuesday) show higher median engagement, posting time does not appear to be a dominant driver of engagement.

### Engagements by Collaborations

- Engagement patterns frequently align with influencer-driven posts. Notably, the spike observed in Jun–Jul 2023 was largely the result of content collaborations with influencers.
- During the peak in Jun-Jul 2023, Elziwai is involved in ~575K out of the total ~607K engagement.
- Most engagement from Jun-Dec 2024 related to Byon, contributing ~392K out of the total ~1,108K engagement.
- Posts featuring influencers have a much higher median engagement count (518.5) compared to posts without influencers (162.5), representing around a 3x increase.
- elziwai, celloszxz, byoncombat, randpunk, and tya magdalena are the top influencers contributing the highest total engagement, with each generating over 77K.

## Recommendations

### Optimizing Content Format

- **Prioritize Video Content**: Focus on producing video posts, as they consistently generate higher engagement than photos.
- **Optimize Video Length**: Create videos longer than 15 seconds, since these tend to receive 2–3× more engagement than short clips. Maintain high content quality and storytelling value since length alone does not guarantee performance.
- **Content Duration Testing (A/B Testing)**: Post and compare videos with durations especially above 15 seconds (e.g., 15-30s, 30-45s) to identify the optimal balance between engagement, viewer retention, and cost efficiency.
- **Refine Drivers Beyond Timing**: Since posting time is not a strong engagement factor, focus future optimizations on content type, duration, audience targeting, and creative execution.

### Maintaining & Expanding Collaborations

- **Leverage Proven Influencers**: Consider allocating budget to continue collaborating with high-performing influencers such as Elziwai, Byon, and Guntur, especially for campaigns during high-traffic periods.
- **Sustain Engagement via Long-Term Partnerships**: Build ongoing collaboration programs instead of one-off campaigns to prevent post-peak engagement drops.
- **Co-Branding Opportunities**: Consider partnering with complementary brands (e.g., sports events, hampers) that align with the brand image to expand audience reach.

### Sustaining Engagement Momentum

- **Plan for Post-Peak Content**: Design and post follow-up content series after major engagement spikes (e.g., behind-the-scenes, user-generated content, or recap videos) to sustain audience momentum and reduce steep declines.
- **Optimize Audience Retargeting**: Retarget viewers and engagers from peak periods with tailored content to extend their activity cycle.

## Clarifying and Key Questions for Further Analysis

- Is there

## Caveats and Assumptions

Note:

1. Contain a note about the data cleaning process that you did, including any assumptions you had to make about the data.

## Technical Details

The technical analysis utilized:

- **R** for data cleaning, preparation, and exploratory data analysis. Documentation is available [here](https://rpubs.com/andrewanggoh/InstagramAccountAnalysis).
- **Tableau** for data visualization and an interactive dashboard, which is accessible [here]().

## Contacts

Thank you for reading through this project. Should you have any feedback, suggestions, or wish to collaborate further, feel free to reach out via email or connect with me on LinkedIn.

- LinkedIn: [@andrewoanggoh](https://www.linkedin.com/in/andrewoanggoh/)
- Gmail: andrew.anggoh@gmail.com
