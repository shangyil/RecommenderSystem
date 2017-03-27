# RecommenderSystem

Item-item collaborative filtering

Item-item collaborative filtering, or item-based, or item-to-item, is a form of collaborative filtering for recommender systems based on the similarity between items calculated using people's ratings of those items.

Item-item collaborative filtering was invented and used by Amazon.com in 1998.[1] It was first published in an academic conference in 2001. The authors of that paper, Badrul Sarwar, George Karypis, Joseph Konstan, and John Riedl, won the 2016 Test of Time Award for their paper Item-based collaborative filtering recommendation algorithms. The International World Wide Web Conference committee stated that "this outstanding paper has had a considerable real-world impact".[2]

Earlier collaborative filtering systems based on rating similarity between users (known as user-user collaborative filtering) had several problems:

systems performed poorly when they had many items but comparatively few ratings
computing similarities between all pairs of users was expensive
user profiles changed quickly and the entire system model had to be recomputed
Item-item models resolve these problems in systems that have more users than items. Item-item models use rating distributions per item, not per user. With more users than items, each item tends to have more ratings than each user, so an item's average rating usually doesn't change quickly. This leads to more stable rating distributions in the model, so the model doesn't have to be rebuilt as often. When users consume and then rate an item, that item's similar items are picked from the existing system model and added to the user's recommendations.
