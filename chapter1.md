## Chapter 1: Requests

Este capítulo foi pensado para que a gente consiga cobrir algumas questões importantes a respeito de requests, que estão espalhados pelas nossas aplicações e que são a base entre nossa comunicação frontend com o nosso backend (ou algum [bff](https://samnewman.io/patterns/architectural/bff/), iremos passar por isso mais lá pra frente).

### What's that?

- A way to exchange data between a client and server
- Client sends the request
- Send to a specific URL
- Server responds to the request
- Message returned by server is called the response

Sending only
- URL Parameters 
  Example: foo.com/api?lorem=ipsum
- Form data
- JSON
- Files

Request Types
- https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods

Headers
- Type of data you are sending
- Authentication (ex. https://oauth.net/2/)
- More detailed infos (https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)

Response components
- Data returned by the server
  Example: accessing some web page is a get request that server responses is the web page

- Status code (https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- Response Headers

CORS:
In this mdn section, you can find valuable infos about CORS, it's very recommended to read and understant about
and take the time that you need for that.

https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS