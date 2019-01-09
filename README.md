# sanfrancisco-bikeshare
Evaluated commuter trips and subscriber types of the San Francisco Bikeshare service using Google BigQuery SQL in a Jupyter Notebook to see how Ford GoBike's could increase subscribers.

* Datasource: https://cloud.google.com/bigquery/public-data/bay-bike-share
* Ford GoBike Company Website: https://www.fordgobike.com/

## Evaluation
Began with evaluating commuting using the bike share service in San Francisco. First, defined top commuting times of day in the morning and evening, and then evaluated top trips within those peak times for morning an evening. The top 5 morning commute starting stations are the same as the top 5 evening commute ending stations. These stations make up ~46% of the starting station rides in the morning and ending station rides in the evening. Therefore, somewhere between 40% and 50% of bikeshare users ride almost daily to and from work. In order to increase subscribership, I would also encourage Ford GoBike to market towards prospects near these top stations.

Then I evaluated customer behavior itself looking at types of trips overtime (customer vs. subscriber) as well as trip duration and common days of the week for trips. The periods of extreme decline in total ridership are the holiday time periods of each year as riders are mostly using the service for commuting to and from work.

## Conclusion
From a Ford GoBike deal perspective, I would recommend that the company offers a flat price for a single one-way trip and an annual membership. Of the subscribers, many seem to be using the service for commuting, so we can assume that they are using it often for shorter, purposeful trips to get from point A to point B.

Of the customers (as opposed to subscribers), which there are far fewer of, many seem to be using the service a bit more for leisure as more of their rides happen on the weekends, are longer in duration on average, and are more likely to start and end at the same station. As the average ride is 27 minutes, unlimited 30-minute rides for 24 hours likely will not work as many customers ride for more than 30 minutes. We should be marketing to customers to try the service on a weekend afternoon to tour San Francisco, or even target tourists specifically. Therefore, I would recommend offering a single one-way trip to customers.

I would recommend that Ford GoBike operate fewer bikes during holiday time periods and/or use this time for annual maintenance.
