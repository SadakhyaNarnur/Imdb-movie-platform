# Imdb-movie-platform
Movie Database is implemented using MongoDB . The system is modularized into Movies, Users and Service Request modules. Each of which are organized into collections and queried. The Users collection follows an embedded document structure with references to the Movies and Service Request collections.

DatasetURL: https://www.kaggle.com/PromptCloudHQ/imdb

1. A registered movie DB user should be able to perform the following activities:
● Access movies hosted by the movie database
● Create upto 5 profiles under one registered user. Each profile can independently choose to
stream their own movies
● Each profile can create their own list called my_list.
● A user pays the monthly bills for the access to continue. And choose to discontinue if
needed. User can choose their own payment method
● Create an SR in order for any kind of request for help from the database owners
2. The service agent who is also the owner of the database, takes the ownership of the following
dependent requirements:
● When a user profile raises a service request, make sure that the complaint is assigned to
an available service agent. At the same time take necessary actions towards that request
3. The application itself will be taking care of the following:
● Each user profile history will be recorded
● Bill will be generated for every month
● Tracks the user registration date
● Tracks the number of profiles created
For the easy and efficient outcome of these duties mentioned above we have used a combination of
both Embedded and Referencing.
All the required operations in the application are done efficiently by our hierarchical approach to the
system. The application is constructed into an embedded collection and in 2 cases references have
been added to the rest of the collections.
