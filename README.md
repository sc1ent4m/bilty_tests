This is simple Cypress API tests (both positive and negative).

Covered routes:
* Retrieve Bitlinks by Group - GET /v4/groups/{group_guid}/bitlinks
* Update a Bitlink - PATCH /v4/bitlinks/{bitlink}

To install dependencies execute following code in project root directory:
```
npm install
```
To run tests execute following code in project root directory:
```
npx cypress run
```
