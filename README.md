# Wildfires in Greece: Data Contribution to NASA Space Apps Challenge

## Introduction

This repository contains a dataset focusing on wildfires in Greece. The data has been contributed by CERTH-ITI as part of the NASA Space Apps Challenge. The project aims to provide researchers, policy-makers, and the general public with insights into wildfire patterns and their associated risks.

## Data Description

The dataset is in JSON format and consists of 26,605 social media posts collected from the Twitter platform. These posts were gathered based on keywords related to fire danger and high temperatures. The dataset covers the period from May 1 to August 31 in the years 2019, 2020, 2021, and 2022. The primary geographical focus is Greece, including Athens and surrounding areas.


### Fields

Each entry is a dictionary with the following keys:

- **is_retweet**: This field indicates whether the social media post is a retweet or an original tweet. A retweet is essentially re-sharing or re-posting another user's tweet.
- **timestamp**: The time the post was made.
- **postid**: The unique identifier for the post.
- **is_quote**: Indicates whether the post is a quote.
- **lang**: The language in which the post is written.
- **match**: The keywords that led to the post being included in the dataset, typically related to fire danger and high temperatures.
- **concepts**: This field contains a list of keywords derived from images or videos (thumbnails) included in the tweet. Keywords can represent various elements such as "Outdoor," "Cityscape," "City," "Vegetation," or "Landscape." If this field is empty, it means the tweet did not contain any images or videos.
- **sentiment**: This field captures the emotional tone behind the tweet based on sentiment analysis. It can have one of three possible values:
  - `neg`: Indicates a negative sentiment.
  - `neu`: Indicates a neutral sentiment.
  - `pos`: Indicates a positive sentiment.
- **sentiment_score**: This field provides a numeric value that quantifies the sentiment expressed in the tweet. It assigns numerical values to the sentiment categories:
  - `Positive`: Numeric value indicating the degree of positive sentiment.
  - `Negative`: Numeric value indicating the degree of negative sentiment.
  - `Neutral`: Numeric value indicating the degree of neutral sentiment.
- **location**: The geographical location associated with the post.

## Keywords Used for Data Collection

<table class="tg" style="undefined;table-layout: fixed; width: 931px">
<colgroup>
<col style="width: 187.2px">
<col style="width: 105.2px">
<col style="width: 375.2px">
<col style="width: 263.2px">
</colgroup>
<thead>
  <tr>
    <th class="tg-baqh">Timespan</th>
    <th class="tg-baqh">Language</th>
    <th class="tg-baqh">Keywords</th>
    <th class="tg-baqh">Location</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow" rowspan="3">1 May – 31 August 2019<br><br><span style="font-weight:400;font-style:normal;text-decoration:none">1 May – 31 August 2020</span><br><br><span style="font-weight:400;font-style:normal;text-decoration:none">1 May – 31 August 2021</span><br><br><span style="font-weight:400;font-style:normal;text-decoration:none">1 May – 31 August 2022</span><br></td>
    <td class="tg-c3ow">Greek</td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal;text-decoration:none">κίνδυνος πυρκαγιάς, κίνδυνος πυρκαγιών, υψηλές θερμοκρασίες πυρκαγιάς, υψηλή θερμοκρασία πυρκαγιάς, καυσωνας πυρκαγιών, καυσωνας πυρκαγιάς, ισχυρός άνεμος πυρκαγιάς, ισχυρός άνεμος πυρκαγιάς, ισχυροί άνεμοι πυρκαγιάς, σχυρών ανέμων πυρκαγιάς, καύσωνας πυρκαγιών, </span>καίγεται φωτιά,καίγεται καπνός,καίγεται πυρκαγιά,καίγονται φωτιά,καίγονται καπνός,καίγονται πυρκαγιά, μυρίζει καμένο, μυρίζει καμένο φωτιά , μυρίζει καπνός, μυρίζει καμμένο, μυρίζει καμμένο φωτιά</td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal;text-decoration:none">Αθήνα, Αττική,Εύβοια, Στερεά Ελλάδα,  Ελλάδα</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="2"><span style="font-weight:400;font-style:normal;text-decoration:none">English</span></td>
    <td class="tg-c3ow" rowspan="2"><span style="font-weight:400;font-style:normal;text-decoration:none">Extreme heat fire, heatwave fire, high temperatures fire, drought fire, high winds fire, strong winds fire, risk fire, wildfire</span></td>
    <td class="tg-c3ow" rowspan="2"><span style="font-weight:400;font-style:normal;text-decoration:none">Athens, Attica,Euboea, Evia, Sterea Ellada, Greece</span></td>
  </tr>
  <tr>
  </tr>
</tbody>
</table>

## Timeframe

The dataset spans four years, focusing on the wildfire seasons from May 1 to August 31 in 2019, 2020, 2021, and 2022.

## Usage

To work with this dataset, you can clone this GitHub repository to your local machine:

```bash
git clone https://github.com/AlexEco1/Wildfires_in_Greece.git
```
## Acknowledgements
This work was supported by the EU’s Horizon 2020 research and innovation programme under grant agreement H2020-101004152 CALLISTO.

## Disclaimer
- **Post IDs Only**: Please note that this dataset contains only the Post IDs and not the full text of the tweets. To access the full text, you'll need to hydrate the IDs using Twitter's API in accordance with their terms of service.