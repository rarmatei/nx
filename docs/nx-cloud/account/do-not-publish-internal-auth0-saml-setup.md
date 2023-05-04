1. Generate a unique name for the connection, that includes the company name, such as `saml-cisco`, and give it to the customer. This can be any string.
2. Ask them to follow the setup instructions. They will provide to you:
   3. a public certificate
   4. a Single-Sign-On URL
2. Open the [SAML connections page](https://manage.auth0.com/dashboard/us/nrwl-staging/connections/enterprise/samlp) and add a new one
2. The `Connection name` needs to match the exact string you gave to the customer in step 1.
3. Set the `Sign In URL` and upload certificate with the values you got from the customer.
4. Save it!
5. On the "Login experience" page you get redirected to, enter their "Identity provider domain"
   6. This will be the email domain to use to sign-in. For example, "amanda@cisco.com", will be "cisco.com".
6. Save it again and that's it!
7. Now whenever someone will try to login with an "@cisco.com" email, they will get redirected to their SAML provider.
