## Setup Steps:
* Setup AWS Profile:  [Link](https://docs.google.com/document/d/1v5jpTA9DRPJVrhZnAPFPdtE41J5r_sIsafUBdS-PUl8/edit#heading=h.cms92ljbezks)
* Create a new app using command: [details](https://docs.sst.dev/start/standalone#1-create-a-new-app)
    `npx create-sst@latest app-name`
* Delete files and directories present inside stacks and packages folder as they will have code examples after we setup the app. 


## Folder Structure:

We can have folder structure as suggested in: https://docs.sst.dev/learn/project-structure#monorepo

* Inside our stack directory, We typically group related resources together into stacks.
* Inside our packages directory, we put everything that powers our backend. This includes GraphQL API, lambda functions, also all your business logic, and whatever else we need, the URL: https://docs.sst.dev/learn/project-structure#packages talks about it in more detal

## CircleCI
* Update CircleCI file (we would need to create a bucket for handling env vars). [details](https://docs.google.com/document/d/1v5jpTA9DRPJVrhZnAPFPdtE41J5r_sIsafUBdS-PUl8/edit#heading=h.3ecw62gmwfhd)
