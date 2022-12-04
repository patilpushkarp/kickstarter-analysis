# About

## About the company - Kickstarter

Kickstarter is an American public benefit corporation based in Brooklyn, New York, that maintains a global crowdfunding platform focused on creativity. Kickstarter exists to help bring creative projects to life. It was launched on April 28, 2009, by Perry Chen, Yancey Strickler, and Charles Adler. Creators categorize their projects into one of 13 categories and 36 subcategories. They are Art, Comics, Dance, Design, Fashion, Film and Video, Food, Games, Music, Photography, Publishing, Technology and Theater {cite}`kickstarter_2022`.

---

## About the data

### Introduction

The data has been sourced from [Kaggle](https://www.kaggle.com/datasets/thedevastator/most-kickstarter-campaigns-fail-here-s-why?select=kickstarter_data_with_features.csv), which is licensed under Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0). It contains data on 20,632 projects as of February 1st, 2017.
By analyzing the data for different categories of projects, Kickstarter could see which categories are the most popular and adjust their website and/or marketing strategy to target those categories. Additionally, by using the data on successful campaigns, Kickstarter could attempt to replicate those campaigns that are most successful. Furthermore, Kickstarter could use this data to better understand why some campaigns are unsuccessful and provide advice or resources for future campaign creators to increase their chances of success.

### Research Ideas

- Data can be used to analyze failed projects to understand the reasons for project failures and then plan accordingly to improve the chance of success.
- This data can also be used to prioritize categories and then adjust the website.

### Data Dictionary

There are 61 columns present in the dataset, which are as follows:

|Feature|Description|
|:--|:--|
|name|The name of the project|
|blurb|A short description of the project|
|goal|The funding goal of the project|
|pledged|The amount of money that project was able to raised|
|state|The state of the project. Whether the project was able to raise successfully or not|
|slug|Unique identifier of the project|
|disable_communication|Whether the communication is disabled or enabled|
|country|Country of the owners of the project|
|currency|Currecy of the country in which the owners are present|
|currency_trailingcode|Whether the currency has the trailing code or not|
|deadline|The date at which the project will stop raising|
|state_changed_at|The date at which the state of the project was changed for the first time|
|created_at|The date at which the project was created on the platform|
|launched_at|The date at which the project was launched for raising the fund|
|staff_pick|Whether the project was picked by staff or not|
|backers_count|Number of backers of the project|
|static_usd_rate|The currency exchange rate with respect to the US Dollar|
|usd_pledged|The amount raised converted to US Dollar|
|category|The category of the project|
|spotlight|Whether the project could find the place in the spotlight section of the platform or not|
|source_url|The source URL of the project|
|name_len|The length of the project name|
|name_len_clean|The lenght of the project name after cleaning|
|blurb_len|The length of thr project blurb|
|blurb_len_clean|The length of the project blurb after cleaning|