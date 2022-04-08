# URL-test-with-Curl-using-Proxy-authentication


Sample output below -

************************************************************** 
*                       Proxy Test with Curl                 * 
*  Visit https://github.com/sanjib-chowdhury for more tools  * 
************************************************************** 
curl -v -i -U user:password --proxy http://proxy:80 google.com 
HTTP/1.1 301 Moved Permanently
Location: http://www.google.com/
Content-Type: text/html; charset=UTF-8
BFCache-Opt-In: unload
Date: Thu, 31 Mar 2022 12:35:01 GMT
Expires: Sat, 30 Apr 2022 12:35:01 GMT
Cache-Control: public, max-age=2592000
Server: gws
Content-Length: 219
X-XSS-Protection: 0
X-Frame-Options: SAMEORIGIN
Proxy-Connection: Keep-Alive
Connection: Keep-Alive
Age: 712790

<HTML><HEAD><meta http-equiv="content-type" content="text/html;charset=utf-8">
<TITLE>301 Moved</TITLE></HEAD><BODY>
<H1>301 Moved</H1>
The document has moved
<A HREF="http://www.google.com/">here</A>.
</BODY></HTML>
************************************************************** 
