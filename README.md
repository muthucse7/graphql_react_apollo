# graphql_react_apollo
GraphQL React Apollo

Sample GraphQL Query:

Request:
query{
  user(id: "41"){
    firstName
  }
}

Response:
{
  "data": {
    "user": {
      "firstName": "Nick"
    }
  }
}


