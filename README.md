# Integrated auth service based on oauth 2.0

This is a go application developed to integrate and manage verification, membership registration, sign in, authorization, authentication, etc. through micro service.  

The authentication-related mechanism is based on oauth 2.0 and implemented using the go language.

- easy implementation
- all basic requirements are included
- everything can be customized

## When is it useful?

- when creating a server that supports **self-login, membership registration, and OAuth** in the go
- when you want to build an auth micro service that can be used **together on the web and application**
- when you want to support **both http and grpc** protocols

## Features

### Sign in and Sign up

1. Local
    - email verification
    - phone verification
2. Use external provider
    - google
    - naver
    - kakao

### Authority and Authentication

1. Authority
    - user
    - admin
2. Local authentication
    - [Password Grant](https://oauth.net/2/grant-types/password/)
3. External provider authentication
    - [Authorzation Code Grant](https://oauth.net/2/grant-types/authorization-code/)
