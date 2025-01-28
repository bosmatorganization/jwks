# jwks

example

https://keytool.online/ 

Payload: { "sub":"admin@admin.com", "role":"admin", "team":"admins" }.

According to ChatGPT, we must use the following Public Exponent value 65537 (F4) .
The value of e should be a base64url-encoded unsigned integer representing the RSA public exponent, commonly "AQAB" (65537 in decimal) for most keys.

Click on generate keypair.

Copy the public JWK (JSON Web Key).

For url: Create a file in arbitrary github repo: https://bosmatorganization.github.io/jwks/jwks.json
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site 

For manual upload certs use the public PEMs (The web offer two different PEM keys)

Go to Management api and paste in the authorization input the JWT that was in the bottom of the online tool.

