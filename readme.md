

# Learning GraphQL through Profile Creation

### Audit link
https://github.com/01-edu/public/tree/master/subjects/graphql/audit

### Hosting link


## Objectives

The objective of this project is to learn the GraphQL query language by creating your own profile page.

You'll use the GraphQL endpoint provided by the platform (`https://01.kood.tech/api/graphql-engine/v1/graphql`). You'll be able to query your own data to populate your profile page.

To access your data, you'll need to create a login page.

Your profile must display three pieces of information which you may choose. 

- Basic user identification
- XP amount
- Audits

Beside those sections, it will have a mandatory section for the generation of statistic graphs.

### Login Page

You'll need a JWT to access the GraphQL API. A JWT can be obtained from the signin endpoint (`https://01.kood.tech/api/auth/signin`).

You may make a POST request to the signin endpoint, and supply your credentials using Basic authentication, with base64 encoding.

Your login page must function with both:

- username:password
- email:password

If the credentials are invalid, an appropriate error message must be displayed.

You must provide a method to log out.

When making GraphQL queries, you'll supply the JWT using Bearer authentication. It will only allow access to the data belonging to the authenticated user.

You may inspect the JWT to discover the ID of the authenticated user.







