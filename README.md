# Movie Streaming Management System
The goal of the project was to build a scalable system that could handle multiple users streaming movies simultaneously. The project used a combination of C# and distributed systems to achieve this goal.

Features:

- **SQL queries**: The system used SQL to store and manage movie data, including information about movie titles, genres, actors, and ratings. SQL queries were used to retrieve information from the database and to optimize database performance.
For example, one query was used to retrieve the top-rated movies for a given genre, while another query was used to calculate the average rating for a given movie.
- **Distributed system**: To handle multiple users streaming movies at the same time, the project implemented a distributed system. This involved breaking up the system into smaller, independent components that could be run on different machines.
For example, one component was responsible for storing and retrieving movie data from the database, while another component was responsible for streaming the actual movie to the user's device. The components communicated with each other over a network, using protocols like HTTP and TCP/IP.
- **Load balancing**: To ensure that the system could handle a large number of users, the project implemented load balancing. This involved distributing user requests across multiple instances of the system, so that no single instance would become overloaded.
For example, when a user requested to stream a movie, the request would be routed to one of several instances of the movie streaming component. If one instance became overloaded, the load balancer would route requests to a different instance.
- **Caching**: To improve performance and reduce database load, the project implemented caching. This involved storing frequently accessed movie data in memory, so that it could be retrieved quickly without accessing the database.
For example, when a user requested information about a movie, the system would check the cache first. If the information was not in the cache, it would be retrieved from the database and added to the cache.
