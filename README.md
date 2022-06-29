OIDC App
======

## Purpose
* Demo OIDC login flow

## How to run backend
```
npm i               ## install dependencies
npm start           ## run (in production mode)
npm run start:dev   ## run (in dev mode)
```

## How to test
* Run backend
* Browse 'http://localhost:8000' on web browser
1. Click '1 - Discovery' button
  - Fill Issuer as 'https://dev-console.myinitial.io/kc/auth/realms/vc-authn'
  - Click 'Load OpenID Provider Configuration' button
  - Check OpenID Provider Configuration
2. Click '2 - Authentication' button
  - Fill client_id as 'oidc-client-react'
  - Fill scope as 'openid'
  - Click 'Generate Authentication Request' button
  - Check Authentication Request
  - Click 'Send Authentication Request' button
  - Check Authentication Response
3. Click '3 - Token' button
  - Click 'Send Token Request' button
  - Check ID Token and Payload

## Tools
* node v14.18.2

## Ref
* https://github.com/PacktPublishing/Keycloak-Identity-and-Access-Management-for-Modern-Applications.git
