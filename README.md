# mertonno

PoC for playing around with different technologies.

# Technologies

- SPA
    - React
    - with a generated typed client for the graphql api;
    - oauth tokens should not be accessible by JS to prevent XSS, only allow in a secure and http only cookie ussing the BFF (backend for frontend) pattern.
    - using Graphql fragments for queries and mutations.
      
- Azure Entra Id
    - app registrations
    - enterprise applications
    - scopes
    - api permissions
    - app roles  
    - frontend / SPA user authentication 
    - app to app authentication with on-behalf-of flow, so one app calls a downstream api using the OAuth2.0 On-Behalf-Of flow.
    - confidental apps

- GraphQL with https://github.com/graphql/composite-schemas-wg
  - where schema comes from different services
  - schema stiching
  - fragments
  - subscriptions
 
- .NET 8.0

- .NET Aspire

- Azure Container Apps

- Open Telemetry with Azure Monitor
 
## Bonus

- Use vector db for search using Weviate. Expose via graphql.
 
# Project

**ToDo what are we building?**

We are building a simple webshop for books...

What are the requirements?

Which service is responsible for what?

- Frontend App
- Graphql Gateway
- Service X
- Service Y
