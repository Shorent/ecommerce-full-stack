
# This project will...

- Contain security functionality
- Run two separate backends
- Contain Authentication & Authorization functionality
- Contain product functionality
- Contain order functionality
- Look nice, hopefully

# The Two Backends

This project will contain three front end applications and 4 backend 
applications;

**Frontend** 
- User frontend
- Group frontend
- Admin Frontend

**Backend**
- User Backend 
- Group Backend 
- Admin Backend 
- Product Backend
- Authentication & Authorization Backend

One to provide 
information for users/customers, the second to provide functionality to 
groups/brands, the third to provide useful functionality to admins and managers.

## The User Stack

**The User Stack will...**
- Allow an unauthenticated user to sign up or in
- Allow an authenticated user to sign out
- Allow an authenticated user to read and write products to their order
- Allow a user to search all products
- Allow a user to view popular products, new products, and clearance products
- Prompt an unauthenticated user to sign up when they attempt to add an item to 
  their cart
- Allow an authenticated user to checkout an order and use some payment 
  processing method (stripe?)
- Allow an authenticated user to view all of a groups/brands products 
- Allow an authenticated user to create an issue-report

## The Group Stack 

**The Group Stack will...**
- Allow an unauthenticated vendor to do nothing
- Allow an authenticated vendor to read and write products to their
  assigned group
- Allow an authenticated vendor to view their group's sales
- Allow an authenticated vendor to exchange inventory with the user stack's
  distributor
- Allow an authenticated vendor to log and inventory exchange
- Allow an authenticated vendor to create an issue-report

## The Admin Stack

- Allow an authenticated group-admin to read/write groups
- Allow an authenticated user-admin to read/write users and their logs
- Allow an authenticated product-admin to read/write products
- Allow an authenticated user-manager to read/write users with USER roles
- Allow an authenticated product-manager to report products
- Allow an authenticated group-manager to report groups
