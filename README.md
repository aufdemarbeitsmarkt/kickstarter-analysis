# Kickstarting with Excel

## Overview of Project

At the outset of this project, we performed exploratory analysis of a sample of 4114 Kickstart campaigns with particular focus on campaigns in the "theater" category and "plays" subcategory. We aimed to provide our client with insight into this distribution of outcomes as well as descriptive statistics of Pledge and Goal amounts for these types of campaigns.

Equipped with this analysis, our client launched her own campaign for the play, _Fever_, which at this time, has come close to meeting its fundraising goal.

### Purpose

With the campaign for _Fever_ in progress, we would like to perform an analysis and visualize campaign outcomes based on their launch dates and funding goals.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The chart below shows the number of campaigns in the 'theater' category by outcome based on launch date.

resources/Theater_Outcomes_vs_Launch.png

Reviewing this data, we see that May has the highest number of successful campaigns. While May also has the highest number of failed campaigns, note that the number of successful campaigns becomes increasingly closer to the number of failed campaigns in the final few months of the year (October through December).

With this, we feel confident that late-spring is likely the best time to begin a campaign. It is recommended to avoid starting campaigns in the fall and winter months, particularly October through December.

Note that this data does not take into consideration the length of time a campaign is live. Some additional research may be warranted to better understand the interaction of creation date and the length of a campaign. For notes on this, see #4 in the [Results](#results) section below.

### Analysis of Outcomes Based on Goals

The chart below shows the percentage of successful, failed, and canceled campaigns in the 'plays' subcategory, broken up into goal ranges.

##### _note:_ 'Percentage Canceled' was 0% for all goal ranges, thus no results show on this chart.  

resources/Outcomes_vs_Goals.png

The highest percentages of successful campaigns fall within the 'Less than 1000' and '1000 to 4999' ranges -- 76% and 73% of campaigns in these ranges were successful, respectively.

There is a spike in 'Percentage Successful' in the '35000 to 39999' and '40000 to 44999' ranges, however, the actual number of campaigns is quite low.

'Percentage Failed' values are at their highest in the '25000 to 29999', '30000 to 34999', '45000 to 49999' ranges.

With this, we can comfortably recommend that campaigns with fundraising goals of less than 5000 are likely to succeed. When creating a campaign with a goal higher than this recommendation, additional care and research are warranted.

Note that this data does not take into consideration currency conversion, e.g. a campaign with a goal of NOK 40000 will fall into the same bucket as a USD $40000 campaign; in reality, NOK 40000 is roughly equivalent to USD $4600.


### Challenges and Difficulties Encountered

No explicit challenges or difficulties encountered with this particular analysis. That said, please see my thoughts on the limitations of this dataset in #3 of the [Results](#results) section.


## Results

#### 1. What are two conclusions you can draw about the Outcomes based on Launch Date?

1. As above, creators will likely have the best chance for success starting their campaign in May.
2. A creator should especially avoid creating campaigns from October through December.

#### 2. What can you conclude about the Outcomes based on Goals?

Campaigns with a goal less than 5000 are most likely to succeed. If a higher goal is desired, campaign creators should conduct additional analysis.

#### 3. What are some limitations of this dataset?

* At this point in time, the data set is a bit dated -- the most recent campaign was created about 5 years before this analysis. Ideally, more up-to-date campaign data would be available to bolster confidence in the any conclusions.
* Currency conversion data is not available in this dataset. Ideally, conversion values for a single currency, e.g. USD, would be gathered when doing this, particularly for the 'Outcomes Based on Goals' analysis.

#### 4. What are some other possible tables and/or graphs that we could create?

* Investigation into the number of backers for campaigns, broken up by outcomes and goal amounts. With the analysis as-is, it's unclear how number of backers might impact a campaigns success.
* With regard to 'Theater Outcomes by Launch Date', a more robust way to look at this data would be to calculate percentages for failures, successes, and cancellations.
* Visualize the length of time for campaigns by outcome. Provide descriptive statistics for this data as well.  
