# TikTok-TikTok---Hypothesis-Test-Verified-Unverified-Accounts
In this activity, you will showcase your ability to use statistical methods to analyze and interpret data. In particular, you will use descriptive statistics and hypothesis testing. You will also update team members through an executive summary, demonstrating your ability to organize and communicate key information. 
______________________________________________
## Scenario
The TikTok data analytics team has completed the first three milestones of the claims classification project and is nearing the halfway point. So far, the team has completed a project proposal, and used Python to perform exploratory data analysis on the dataset for the claims classification project. The team also produced data visualizations in both Python and Tableau to share with stakeholders. The next step is to use statistical methods to analyze and interpret the claims classification data.

You receive a new email from Mary Joanna Rodgers, one of TikTok’s project management officers. Mary Joanna informs the data team about a new request: to determine whether there is a statistically significant difference in the number of views for TikTok videos posted by verified accounts versus unverified accounts. You also receive follow-up emails from Data Science Manager, Rosie Mae Bradshaw and Data Science Lead, Willow Jaffey. These emails share the details of the analysis. A final email from Data Scientist, Orion Rainier, details your next assignment: to conduct a hypothesis test on verified versus unverified accounts in terms of video view count.

Note: Team member names used in this workplace scenario are fictional and are not representative of TikTok.
______________________________________________
## Hypothesis

1) Do videos from verified accounts and videos unverified accounts have different average view counts?

2) Is there a relationship between the account being verified and the associated videos' view counts?
______________________________________________
## Data Dictionary
This project uses a dataset called tiktok_dataset.csv. It contains synthetic data created for this project in partnership with TikTok. Examine each data variable gathered. 

19,383 rows – Each row represents a different published TikTok video in which a claim/opinion has been made.

12 columns 

| Column Name             | Type | Description                                                                                           |
|-------------------------|------|-------------------------------------------------------------------------------------------------------|
| #                       | int  | TikTok assigned number for video with claim/opinion.                                                  |
| claim_status            | obj  | Indicates whether the published video has been identified as an "opinion" or a "claim."              |
| video_id                | int  | Random identifying number assigned to a video upon publication on TikTok.                             |
| video_duration_sec      | int  | Duration of the published video measured in seconds.                                                  |
| video_transcription_text| obj  | Transcribed text of the words spoken in the published video.                                           |
| verified_status         | obj  | Indicates the verification status of the TikTok user who published the video.                         |
| author_ban_status       | obj  | Indicates the permission status of the TikTok user who published the video.                            |
| video_view_count        | float| Total number of times the published video has been viewed.                                             |
| video_like_count        | float| Total number of times the published video has been liked by other users.                               |
| video_share_count       | float| Total number of times the published video has been shared by other users.                              |
| video_download_count    | float| Total number of times the published video has been downloaded by other users.                          |
| video_comment_count     | float| Total number of comments on the published video.                                                       |
