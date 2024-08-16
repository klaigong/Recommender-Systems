
We exist in a technological era where there is far too much content (movies, news articles, shopping products, websites, etc.) for individual items to receive our consideration. For example, consider that the average Google search returns well over 1 million results, yet when was the last time you looked at the websites past the first page?  This fact is often illustrated by what is known as the "long tail problem" (represented in the figure above), where tracking user engagement with items in a large content repository sees a small number of these items receiving a disproportionate amount of attention. In contrast, the majority of items remain unexplored. The truth is that a user doesn't know of each item that exists, nor has the time to inspect each item even if it were known. 

In light of the above challenge, a natural question for service providers becomes: "How do I ensure that an individual is shown a manageable portion of the total content I have available while also ensuring that this content is relevant to and desired by them?" This question turns out to be extremely valuable, both economically and within society. Luckily for us, decades of hard work by very intelligent individuals have largely answered this question through a collection of algorithms and computing techniques known as recommender systems.


Simply put, a recommender system functions by predicting a user’s rating or preference for an item. This allows a service provider to build up a catalogue of items it believes the user will want to examine, thereby increasing their engagement with the service and allowing a wider array of content to be considered.


Within this train, we will review some fundamental concepts upon which recommender systems operate. We will also learn how to implement one of the two dominant methods currently studied in relation to recommender systems, referred to as content-based filtering. 

Let's dive in!  

This repository contains sample recommender systems.
Currently, there is only one notebook, but two other samples shall be uploaded soon.
Current - Model based collaborative recommender system.
          The current notebook combines several models from the surprise module and
          generates an average of ratings from all models employed. The best
          hyperparameters are found using GridsearchCV.
