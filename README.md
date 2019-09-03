# Getting Started
to access graphql web console navigate to link:
http://localhost:8080/graphiql

* GraphQl queries:
 ```
     {
       findAllApplications {
         id
         owner
         description
       }
     }
 ```
 * MUTATION OPERATIONS
 ```
     mutation {
       newApplication(
         name: "TrackingZilla",
         owner: "Ion",
         description: "An application to track bugs") {
           id
           name
           owner
           description     
       }
     }
```
