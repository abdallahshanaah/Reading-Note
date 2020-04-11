# EJS 
Every request your application sends to the Books API needs to identify your application to Google. There are two ways to identify your application: using an OAuth 2.0 token (which also authorizes the request) and/or using the application's API key. Here's how to determine which of those options to use:

If the request requires authorization (such as a request for an individual's private data), then the application must provide an OAuth 2.0 token with the request. The application may also provide the API key, but it doesn't have to.
If the request doesn't require authorization (such as a request for public data), then the application must provide either the API key or an OAuth 2.0 token, or both—whatever option is most convenient for you.
**Google Books IDs**
You need to specify ID fields with certain API method calls. There are three types of IDs used within Google Books:

1. Volume IDs - Unique strings given to each volume that Google Books knows about. An example of a volume ID is _LettPDhwR0C. You can use the API to get the volume ID by making a request that returns a Volume resource; you can find the volume ID in its id field.
2. Bookshelf IDs - Numeric values given to a bookshelf in a user's library. Google provides some pre-defined shelves for every user with the following IDs:
Favorites: 0
Purchased: 1
To Read: 2
Reading Now: 3
Have Read: 4
Reviewed: 5
Recently Viewed: 6
My eBooks: 7
3. User IDs - Unique numeric values assigned to each user.
and more information about google doc and api 
next will be how to download it using this command 
**$ npm install ejs**
and some tag you can use with like 
+ <% 'Scriptlet' tag, for control-flow, no output
+ <%_ ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it
+ <%= Outputs the value into the template (HTML escaped)
+ <%- Outputs the unescaped value into the template
+ <%# Comment tag, no execution, no output
+ <%% Outputs a literal '<%'
+ %> Plain ending tag
+ -%> Trim-mode ('newline slurp') tag, trims following newline
+ _%> ‘Whitespace Slurping’ ending tag, removes all whitespace after it
and more 