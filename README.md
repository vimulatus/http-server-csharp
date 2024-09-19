# An HTTP/1.1 Server in C#

# RFC 2616
## Terminology
Connection
: A transport layer virtual circuit established between two programs for the purpose of communication.

Message
: The basic unit of HTTP communication, consisting of a structured sequence of octets matching the syntax defined in [#Http Message] and transmitted via the connection.

Request
: An HTTP request message, as defined in [#Request]

Response
: An HTTP response message, as defined in [#Response]

resource
: A network data object or service that can be identified by a URI, as defined in [#Uniform Resource Identifiers]. Resources may be available in multiple representations (e.g. multiple languages, data formats, size, and resolutions) or vary in other ways.
