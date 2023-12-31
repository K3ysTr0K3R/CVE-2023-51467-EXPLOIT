# CVE-2023-51467 - Apache OFBiz Authentication Bypass

This flaw enables attackers to bypass authentication, leading to a Server-Side Request Forgery (SSRF) exploit. When sending a web request to the specific path /webtools/control/ping?USERNAME&PASSWORD=test&requirePasswordChange=Y, the server responds with the word "PONG." This response indicates that the vulnerability has been triggered.

# Disclaimer
This PoC/scanner is only meant for educational purposes. You are responsible for your own actions.
