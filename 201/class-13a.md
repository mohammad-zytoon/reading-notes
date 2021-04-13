# The Past, Present and Future of Local Storage for Web Applications
__________________________________________________________________________________

- This article begins talking about storage. What kind of storage? Well, 
 web storage of course and because we access the web on remote servers, 
 there are factors that slow down browser response and factors that have
 bogged down browsers pre HTML5. Cookies collect data on users and 
 transmit data on how a user interacts with a site. Two points of 
 distinction: Local Server: refers to your hard drive on a comuter. 
 Remote Server: Where web data is stored.

- Progress has been made over the years as new technology has become more 
 efficient with user data. Many 3rd party plugins have provided capabilities in
 browsers over the years that have had limitations. HTML5 provided at 
 standardization of user data collection that doesn't rely on 3rd party plugins.


**HTML5 Storage**
__________________________________________________________________________________

- HTML5 storage means web storage is a way for web pages to store user information
 locally inside the user's web browser. This information is not transmitted to the 
 web server unless it is send manually. Because it is not transmitting information, 
 browser response will be quicker. All major web browsers use this type of storage.


**Using HTML5 Storage**
__________________________________________________________________________________

- HTML5 storage is based off naming key/value pairs. Data storage is based on a 
  named key, then you can retrieve that data with the same key. Data can be any type 
  supported by Javascript that includes strings, booleans, integers or floats. Data is 
  stored in a strings and if you are retrieveing anything other than strings, you'll need
  to use functions to coerce the retrieved data into the expected JavaScript datatype. 
  There are ways to access a localStorage object using methods and getItem and setItems.


**Tracking changes to the Storage Area**
__________________________________________________________________________________

- To keep track of when the storage area changes, you can 'trap' the event. The storage event
 is supported everywhere the loacalStorage event object is supported.

- This article was abstract and I would probably have to re-read this over the next 5 years to make sense of it.

