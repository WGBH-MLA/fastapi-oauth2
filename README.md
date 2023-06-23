# fastapi-oauth2

Easy to setup OAuth2 social authentication mechanism with support for several auth providers.

## Demo

This sample application is made to demonstrate the use of the [**fastapi-oauth2**](./fastapi_oauth2) package.

## Running the application

```bash
uvicorn main:app --reload
```

## TODO

- Make the [**fastapi-oauth2**](./fastapi_oauth2) depend
  on (overuse) the [**social-core**](https://github.com/python-social-auth/social-core)

## Features

- Integrate with any existing FastAPI project (no dependencies of the project should stop the work of
  the `fastapi-oauth2`)
- Use multiple OAuth2 providers at the same time
- Token to user data, user data to token easy conversion
- Customize OAuth2 routes
