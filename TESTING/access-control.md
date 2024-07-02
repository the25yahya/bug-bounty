- setup headers : pointers (leads) / accounts  / mechanisms / objects
- first thing is , identify how the app is validating user data and pulling user related data from the backend ,
is it validated in the front end or the backend ? and how is it validated
- highlight sent back data form the server , and use exclusion to determine the cookies that are responsible for fetching data
- when analyzing mechanisms and actions the user can make , keep not of :  wich crud they use , and how is it actually happening
- identify objects , user object , cart object …
- look for unique identifiers of your user object within the application and look for mechanisms that use that identifier.
- beware of false positives and attack vectors that dont access data on the backend
  ###
- if the application has different user roles : 
- map out different mechanisms that each user role can do , analyze them and test for function level access control  
