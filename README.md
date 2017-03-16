# Relay Examples Error reproduction fork

Removed all but Star Wars example. Added a field to the graphql schema, which intensionally always throws an error.
Fetching the star wars data works as usual, if the new field is added to the query, graphql returns star wars data and an errors array with the error as expected.
Relay however displays none of the data returned.

What I expected was the same as the GraphQL behavior, that all the data that was correctly fetch was displayed, along with the error.

