# Artblocks Stats

## Overview

This repo provides:
(i) historical price data for all ArtBlocks Curated Collections, and
(ii) histograms for each collection showing all sales, current floor price, and average sale price over the selected interval (all in both ETH and USD).

## Instructions

Pre-generated price charts can be found in the /price_charts directory. All historical data can be found in the /price_histories directory.

Technical users may wish to adjust parameters and generate charts of their own. A few notes:
- In order to query OpenSea's API, you will need to provide your own OpenSea API Key in Cell 2 of artblocks_stats.ipynb.
- You can generate your own plots by updating Cell 2 of artblocks_processing.ipynb. Here, you can adjust the start_date, update the price of ETH, and select the collection for which you'd like to generate a chart. When generating your own plots, you may wish to optimize the histogram bin size for the collection you are interested in.

## Acknowledgements

This project was inspired by [a request from DCinvestor.eth](https://twitter.com/iamdcinvestor/status/1522210591250780160?s=21&t=8M0Dkpmhc8PhQY30X2spUA) and the NFT Statistics threads of [NFTStatistics.eth](https://twitter.com/punk9059).