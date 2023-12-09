# Multitouch Attribution Modelling
Advertisers use a variety of online marketing channels to reach consumers and they typically want to know how much each channel contributes to their marketing success. This is what is known as multi-channel attribution. In many cases, advertisers approach this problem using some simple heuristical models that often underestimate the importance of different marketing channels. In general, there are different types of attribution models:

- First Touch Conversion: A user's conversion is attributed to the first channels/touchpoints.
- Last Touch Conversion: A user's conversion is attributed to the last channels/touchpoints.
- Linear Touch Conversion: All channels/touchpoints are given equal credit to a user's conversion.
- Markov Chain: A probabilistic model that represents the buyer's journey as a graph, with the nodes representing different channels/touchpoints, and the connecting lines being observed transitions between them. The number of times buyers have transitioned between two states is converted into a probability, which can then be used to measure the importance of each channel and the most likely channel paths to success.

Example Markov Chain where C denotes the marketing channel:

![multitouch](https://github.com/TrangHaQuach/Multitouch-Attribution-Modelling/assets/102645482/eef25ba4-1b4d-4ceb-9b67-5e8803d56fcc)
