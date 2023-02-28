## Server Side Request Forgery SSRF

Is a vulnerability that allows a malicious user to cause the webserver to make an additional or edited HTTP request to the resource of the attacker's choosing.

# Types of SSRF

There are two types of SSRF vulnerability:<br>
  First is a regular SSRF where data is returned to the attacker's screen.<br> 
  Second is a Blind SSRF vulnerability where an SSRF occurs, but no information is returned to the attacker's screen.

# What's the impact?
A successful SSRF attack can result in any of the following: 

Access to unauthorised areas.
Access to customer/organisational data.
Ability to Scale to internal networks.
Reveal authentication tokens/credentials.
