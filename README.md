# Jins-Unit-14.1-Exercises
Unit 14.1 Exercises
Part 1:

HTTP—or Hypertext Transfer Protocol—is one set of rules by which different machines and web servers make and receive file requests.
A URL—Uniform Resource Locater—is the human-friendly way to make a request of a server (usually using HTTP or HTTPS). URLs are often used in browsers.
DNS—the Domain Name System—is the collection (or a collection) of which domain names resolve into which IP addresses, functioning as a “phone book” of sorts for the Web.
A query string is a set of key=value pairs joined by ampersands added to the end of a URL that supply additional information to a server such as search terms or form input.
Two HTTP request verbs are GET (which facilitates a request made to a server without changing any data on the server) and POST (which facilitates a request made to a server that changes data on that server).
An HTTP request is the way that a client machine connected to a server can get or change information on that server using the HTTP rules set.
An HTTP response is what the server that a client machine makes a request of sends back to that client machine; it includes a response message and headers, among other things.
An HTTP header is part of an HTTP request or response that supplies important information to the server or client, respectively. Some examples of HTTP headers are Accept-Language (for human languages) and Accept (for HTML-JSON-XML).
When you type http://somesite.com/some/page.html into a browser and press Enter, the browser makes a HTTP request of the server of hostname somesite.com for the content it thinks is located at /some/page.html. If that content exists at the location the browser expects, the server for that hostname sends the content located at that location; the browser may also make separate requests for stylesheets, script files, and images that will also have their own responses. If that content does not exist at that location but has been moved to another spot, there will be two requests and responses—the first set for the given URL, and the second set for the actual URL of the content. If there is an error—for example, the content is not found at the given location or any location (404) or the server encounters an error (5XX), the server will likely send back an error page.
