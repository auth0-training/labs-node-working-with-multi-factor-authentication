![Auth0 Open Source Software](https://cdn.auth0.com/resources/oss-source-large-2x.png)

# Expenses API Express 

The Expenses API is an example application that implements oAuth 2 API protection.

## Version 2.0

This version of the expense api reflects the midpoint for the state of the api in the A0FUN-M06-L01 Working with APIs lab.

### Run Local:

```bash
ISSUER_BASE_URL=https://your-tenant.region.auth0.com \
npm start
```

### Required Scopes

| Endpoint   | Secure | Scopes         |
| ---------- | ------ | -------------- |
| `/`        | ❌     |                |
| `/total`   | ❌     |                |
| `/reports` | ✅     | `read:reports` |
