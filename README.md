# Analysis of Correlation Between Twitter Sentiment and Bitcoin Price

## Overview

The notebook analyzes the relationship between Twitter sentiment about Bitcoin and its closing price, separating users into influencers and non-influencers to examine if different user groups have different predictive power or relationships with BTC price movements.

## Data Preparation and Visualization

1. The analysis divided Twitter users into two groups:

   - **Influencers**: Users with verified accounts or more than 100,000 followers
   - **Non-influencers**: Regular users who don't meet the influencer criteria

2. Daily mean sentiment scores were calculated for both groups and plotted against BTC closing price over time using a dual-axis plot.

## Cross-Correlation Analysis

The notebook performed cross-correlation analysis between sentiment scores and BTC price with lags ranging from -10 to +10 days to identify potential lead-lag relationships:

### Influencer Sentiment and BTC Price

- The cross-correlation between influencer sentiment and BTC price shows varying correlation coefficients across different lag periods.
- The plot shows the relationship between influencer sentiment and future/past BTC price movements.
- Positive lags indicate that sentiment might be leading price (sentiment predicts future price movements).
- Negative lags indicate that price might be leading sentiment (price movements affect future sentiment).

### Non-Influencer Sentiment and BTC Price

- Similar cross-correlation analysis was performed for non-influencer sentiment and BTC price.
- The correlation coefficients also vary across different lag periods.
- The pattern appears to be different from the influencer correlation, suggesting that different user groups may have different relationships with BTC price.

## Key Findings

From the cross-correlation plots:

1. **Lag Relationships**: Both analyses show correlation coefficients at various lag periods, indicating potential temporal relationships between sentiment and price.

2. **Correlation Strength**: The magnitude of correlation coefficients suggests the strength of the relationship between sentiment and price at different time lags.

3. **Pattern Differences**: The patterns in the cross-correlation plots differ between influencer and non-influencer sentiment, suggesting that these user groups may have different relationships with BTC price movements.

4. **Potential Predictive Value**: The presence of significant correlations at certain lags (especially positive lags) might indicate potential predictive value of sentiment for future price movements.

## Implications

1. **Market Sentiment Indicators**: The analysis suggests that Twitter sentiment, particularly when segmented by user influence, could serve as a potential indicator for Bitcoin price movements.

2. **Different User Impact**: The different correlation patterns between influencer and non-influencer sentiment suggest that market participants may react differently to opinions from different user groups.

3. **Trading Strategies**: The lag relationships identified could potentially inform trading strategies that incorporate sentiment analysis, with attention to the appropriate lag periods that show stronger correlations.

4. **Market Efficiency**: The presence of correlations at certain lags may provide insights into the efficiency of the Bitcoin market and how quickly it incorporates sentiment information.

---

This analysis contributes to understanding the complex relationship between social media sentiment and cryptocurrency prices, highlighting the importance of considering user influence when analyzing sentiment as a potential market indicator.
