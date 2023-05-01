HIGH LEVEL APPROACH:
My strategy was primarily linear. I started with the first HTTP request and then parsed the message I received to look for key fields based on the following request. The programme would identify all the links and determine whether they are genuine once I had reached the login page. Valid as in not visited, on the list of places that need to be visited, or not starting with a specific string. The flag tag would then be found and recorded by the function after it had parsed the HTML. This goes on until 5 flags are discovered.

CHALLENGES:
The biggest difficulty was ensuring that I was correctly processing the response and obtaining the appropriate strings for the subsequent request.

TESTING: 
Print statements supported me in the process