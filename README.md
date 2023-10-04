# Wildfires in Greece: Data Contribution to NASA Space Apps Challenge

## Introduction

This repository contains a dataset focusing on wildfires in Greece. The data has been contributed by CERTH-ITI as part of the NASA Space Apps Challenge. The project aims to provide researchers, policy-makers, and the general public with insights into wildfire patterns and their associated risks.

## Data Description

The dataset is in JSON format and consists of 26,605 social media posts collected from the Twitter platform. These posts were gathered based on keywords related to fire danger and high temperatures. The dataset covers the period from May 1 to August 31 in the years 2019, 2020, 2021, and 2022. The primary geographical focus is Greece, including Athens and surrounding areas.

Each entry is a dictionary with the following keys:

- **is_retweet**: Indicates whether the post is a retweet.
- **timestamp**: The time the post was made.
- **postid**: The unique identifier for the post.
- **is_quote**: Indicates whether the post is a quote.
- **lang**: The language in which the post is written.
- **match**: The keywords that led to the post being included in the dataset, typically related to fire danger and high temperatures.
- **concepts**: Any concepts mentioned in the post.
- **sentiment**: The sentiment of the post.
- **sentiment_score**: A numerical score representing the sentiment.
- **location**: The geographical location associated with the post.

| Date Range            | Language | Keywords                                                                                                                                                                         |
|-----------------------|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 May – 31 August 2019 | Greek    | κίνδυνος πυρκαγιάς, κίνδυνος πυρκαγιών, υψηλές θερμοκρασίες πυρκαγιάς, υψηλή θερμοκρασία πυρκαγιάς, καύσωνας πυρκαγιών, καύσωνας πυρκαγιάς, ισχυρός άνεμος πυρκαγιάς, ισχυρός άνεμος πυρκαγιάς, ισχυροί άνεμοι πυρκαγιάς, σχυρών ανέμων πυρκαγιάς, καύσωνας πυρκαγιών |
| 1 May – 31 August 2020 | Greek    | καίγεται φωτιά, καίγεται καπνός, καίγεται πυρκαγιά, καίγονται φωτιά, καίγονται καπνός, καίγονται πυρκαγιά, μυρίζει καμένο, μυρίζει καμένο φωτιά, μυρίζει καπνός, μυρίζει καμμένο, μυρίζει καμμένο φωτιά |
| 1 May – 31 August 2021 | Greek    |                                                                                                                                      |
| 1 May – 31 August 2022 | Greek    |                                                                                                                                      |
|                       | English  | Extreme heat fire, heatwave fire, high temperatures fire, drought fire, high winds fire, strong winds fire, risk fire, wildfire                                                    |
