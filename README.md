# Spring Security with OAuth 2.0

Welcome to the Spring Security with OAuth 2.0 demo project, showcasing how to integrate OAuth 2.0 authentication into a basic Spring Boot application.

## Project Overview

This project demonstrates the implementation of Spring Security with OAuth 2.0 for secure user authentication. Users can log in using popular OAuth 2.0 providers like Google, GitHub, or customize authentication providers as needed.

## Features

- **Spring Security:** Secure your application with Spring Security for authentication and authorization.
- **OAuth 2.0 Integration:** Enable users to log in using OAuth 2.0 authentication providers.
- **Customizable Providers:** Easily configure and extend authentication providers, supporting various OAuth 2.0 identity providers.

## Getting Started

1. Clone the repository: `git clone https://github.com/Robbie-Corcoran/Spring-Security-OAuth2.git`
2. Open the project in your preferred IDE.
3. Configure OAuth 2.0 client credentials for your chosen provider in `application.properties`.
4. Run the application.
5. Access the application at `http://localhost:8080`.
6. All users will be able to access the "/" mapping, but only logged-in user will have access to "/secured".

## Supported Providers

- [Google](https://developers.google.com/identity/protocols/oauth2)
- [GitHub](https://docs.github.com/en/developers/apps/authorizing-oauth-apps)
- [Custom Providers](https://docs.spring.io/spring-security-oauth2-boot/docs/current/reference/html5/#boot-features-security-oauth2-oidc-client)

## Further Exploration

Feel free to explore and customize the project based on your authentication requirements. Add additional OAuth 2.0 providers, customize the login flow, or enhance security features according to your application needs.

## Issues and Contributions

If you encounter any issues or have suggestions for improvements, please open an issue or create a pull request. Your contributions are highly appreciated!

Happy coding! 🚀
