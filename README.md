# voting-app

1. Voting-App: Front-end of the application written in python flask framework, which allows the users to cast their votes.
2. Redis: Redis: An in-memory data structure store, used as a temporary database to store the votes cast by the users.
3. Worker: service written in .NET, that retrieves the votes data from Redis and stores it into PostgreSQL DB service.
4. PostgreSQL DB: PostgreSQL DB used as persistent storage database.
5. Result-app: service written in NodeJS, displays the voting results to the user.
