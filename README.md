# jupiter

Jupiter is a Job Recommendation system which realize the feature of search jobs according to your preference and geolocation.

The backend of the project was built on java and the front-end was built with the basics of Html, CSS, JavaScript. 

To realize this simple feature, Github Job Api was used. And items was created according to the returned json files. To recommend
items according to users preference, AWS RDS was used to store the user's the previous like itmes. Then MonkeyLearn API was used
to extract keywords of the liked items. And then the system can recommend items according to the geolocation and keywords of jobs.
