# Microservice Architecture -: 

## Monolithic Architecture
* A single large application where all components (UI, business logic, and database) are tightly coupled.

* Changes in one part require redeploying the entire app.

* Hard to scale and maintain as it grows.

✅ Example: E-commerce App (Monolithic)

* A single codebase handling user authentication, product catalog, payments, and order management.

* If one feature fails, the whole app might crash.


## Microservices Architecture

* Application is divided into small, independent services communicating via APIs.

* Each service can be developed, deployed, and scaled independently.

* Improves flexibility, scalability, and fault isolation.

✅ Example: E-commerce App (Microservices)

* Separate services for authentication, product management, payment, and orders.

* If the payment service fails, other services keep running.

## Why Choose Microservices Over Monolithic?
1) Scalability – Scale only required services, not the whole app.

2) Faster Development – Multiple teams can work on different services independently.

3) Fault Isolation – A failure in one service won’t crash the entire system.

4) Technology Flexibility – Different services can use different tech stacks.

5) Easier Deployment – Deploy individual services without redeploying the entire app. 

## Big Companies Using Microservices

✅ Netflix – Manages millions of streaming requests efficiently.

✅ Amazon – Handles different services like product catalog, recommendations, and payments separately.

✅ Uber – Uses microservices for handling rides, payments, and driver tracking.

✅ Spotify – Different services for playlists, recommendations, and user management.

## Learnings throughout this project
1) React js 
2) Next js
3) Node js
1) Express js 
2) Mongodb js
3) Redis js
1) Docker 
2) Kubernates
3) TypeScript