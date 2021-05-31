# CRUD


# Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:
   
   - 100’s = informational response – the request was received, continuing process.
   - 200’s = successful – the request was successfully received, understood, and accepted.
   - 300’s = redirection – further action needs to be taken in order to complete the request.
   - 400’s = client error – the request contains bad syntax or cannot be fulfilled.
   - 500’s =  server error – the server failed to fulfil an apparently valid request.


2. What is a status code 202?

  - is intentionally non-committal. Its purpose is to allow a server to accept a 
    request for some other process (perhaps a batch-oriented process that is only run 
    once per day) without requiring that the user agent's connection to the server persist 
    until the process is completed.


3. What is a status code 308?

  - Permanent Redirect redirect status response code indicates that the resource requested
    has been definitively moved to the URL given by the Location headers.


4. What code would you use if an update didn’t return data to a client?

  -  204 No Content - A proper code for updates that don't return data to the client.


5. What code would you use if a resource used to exist but no longer does?

  - 410 code is an explicit indication that the requested resource used to exist, but 
    it has since been permanently removed and will not be available in the future.


6. What is the ‘Forbidden’ status code?

  - client error status response code indicates that the server understood the request 
    but refuses to authorize it.





