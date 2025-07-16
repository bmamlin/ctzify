# ctzify
Redirect to url with added client timezone (ctz) parameter. Useful for sending people to a 
Google Calendar URL showing in the client's timezone. Especially useful when using an 
embedeed Google Calendar within an IFRAME. Instead of fixing to a single timezone, Google will 
display the embedded calendar in the client browser's timezone. If any errors occur or the `url`
parameter is misssing, an error is shown to the user.

Usage
Get a URL-encoded version of your destination URL using a tool like https://www.urlencoder.org/

Pass your target URL in URL-encoded form:

`https://bmamlin.github.io/ctzify/?url={URLENCODED-URL}`

The browser should redirect to the target URL with a client timezone (`ctz`) parameter added. 
