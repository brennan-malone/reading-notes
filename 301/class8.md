# APIs

## API Design Best Practices

What does REST stand for?

Representational State Transfer

REST APIs are designed around a ____.

resources

What is an identifier of a resource? Give an example.

a URI, `https://adventure-works.com/orders/1`

What are the most common HTTP verbs?

GET, POST, PUT, PATCH, DELETE

What should the URIs be based on?

should be focused on the nouns or the resources and not the verbs

Give an example of a good URI.

`https://adventure-works.com/orders // Good`

`https://adventure-works.com/create-order // Avoid`

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

The more requests that happen the more load on the server, so you want to aviod a chatty web API.

What status code does a successful GET request return?

200

What status code does an unsuccessful GET request return?

404, 204

What status code does a successful POST request return?

201, 200, 204

What status code does a successful DELETE request return?

200, 204, 201
