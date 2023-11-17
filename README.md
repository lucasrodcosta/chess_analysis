# Chess Analysis

Jupyter notebooks to get some metrics about the players over the years, just for fun :)

## Summary and Findings

### An overview in ratings over time

![Ratings from 2000 to 2023](/img/ratings_all_time.png "Ratings from 2000 to 2023")

There was a considerable rating inflation until the last months of 2011.

The moment when ratings became more stable coincides with that one in which Magnus Carlsen began his dynasty in top 1.

### Carlsen's Era (2011 - now)

![Ratings in Carlsen's era](/img/ratings_carlsen_era.png "Ratings in Carlsen's era")

When we zoom in to take a deeper look in Carlsen's era, we can see some interesting things:
  - in fact, the ratings looks like more stable;
  - looks like the percentiles and avg rating of top-100 players dropped a bit;

To confirm (or not) the second hypothesys, let's take a look in some graphs:

![p50 of top-100 players](/img/p50.png "p50 of top-100 players")

![p75 of top-100 players](/img/p75.png "p75 of top-100 players")

![p95 of top-100 players](/img/p95.png "p95 of top-100 players")

![avg of top-100 players](/img/avg.png "avg of top-100 players")

Note that all the percentiles and average rating of top-100 players are now smaller than its historical average. It may indicate a slight deflation in ratings.

But these metrics may be affected by Magnus Carlsen, who is an exception. So let's analyze again without Carlsen:

![p50 of top-99 players (without Carlsen)](/img/p50_without_carlsen.png "p50 of top-99 players (without Carlsen)")

![p75 of top-99 players (without Carlsen)](/img/p75_without_carlsen.png "p75 of top-99 players (without Carlsen)")

![p95 of top-99 players (without Carlsen)](/img/p95_without_carlsen.png "p95 of top-99 players (without Carlsen)")

![avg of top-99 players (without Carlsen)](/img/avg_without_carlsen.png "avg of top-99 players (without Carlsen)")

Looks like we can say with a high level of confidence that there is a small deflation of ratings in top-100.

### Is it fair to say that "Magnus Carlsen is no longer the same"?

I don't think so.

![Difference between top 1 and top 2](/img/distance_top_1_2.png "Difference between top 1 and top 2")

The graph above shows the difference between Magnus Carlsen and the top-2 player in the world.

There were moments when this difference was very small (especially in 2011 and july/august/2018). But in november 2023, this difference is at a very safe level (for Carlsen, of course).
