# graphql_react_apollo
GraphQL React Apollo

Sample GraphQL Query:


Add new user:
*************
mutation{
  addUser(firstName:"Vidarth Sastik", age:22, companyId:"2"){
    id
    firstName
  }
}

Get User name by filtering by ID:
*********************************
query{
  user(id:"1nwRf7U9"){
    firstName
    company {
      id
    }
  }
}


Delete user bu ID:
******************
mutation{
  deleteUser(id:"1nwRf7U9"){
    firstName
  }
}


