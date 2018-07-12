# npm-auth
To get auth token of your npm user

> This is based on https://www.npmjs.com/package/registry-auth-token. run node index.js to get auth toke and its type

#### To use in your CI upodate .npmrc file with 

```
//YOUR_NPM_REGISTRY/:_authToken="PROVIDE_AUTH_TOKEN_HERE"

```

#### .npmrc file will look like

```
registry=YOUR_NPM_REGISTRY
//YOUR_NPM_REGISTRY/:_authToken="PROVIDE_AUTH_TOKEN_HERE"
_auth="YOUR_NPM_REGISTRY"
always-auth=true
email=YOUR_EMAIL_ID

```

**note** : Yes! you have to keep commented portion commented in .npmrc, that does make difference :stuck_out_tongue:
