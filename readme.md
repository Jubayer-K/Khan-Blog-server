# Khan Blog Server

Welcome to Khan Blog Server! This server-side component is essential for managing the backend functionalities of the Khan Blog application. It provides the necessary APIs, authentication mechanisms, and database integration to support the blogging platform's operations.

## Features

- **Express Framework:** Khan Blog Server utilizes the Express framework to handle HTTP requests and routing, ensuring efficient and scalable backend operations.
- **Authentication:** User authentication is implemented using JSON Web Tokens (JWT), providing a secure and seamless login experience for users.
- **Database Integration:** Khan Blog Server integrates with MongoDB, a popular NoSQL database, for storing and managing blog posts, user data, and other application-related information.
- **Middleware Support:** Middleware packages such as `cookie-parser` and `cors` are utilized to enhance functionality and security in handling cookies, cross-origin resource sharing, and other HTTP-related tasks.
- **Environment Variables:** Dotenv is used for managing environment variables, allowing for easy configuration and deployment across different environments.

## Dependencies

- **[cookie-parser](https://www.npmjs.com/package/cookie-parser)**: ^1.4.6
- **[cors](https://www.npmjs.com/package/cors)**: ^2.8.5
- **[dotenv](https://www.npmjs.com/package/dotenv)**: ^16.4.5
- **[express](https://www.npmjs.com/package/express)**: ^4.19.2
- **[jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)**: ^9.0.2
- **[mongodb](https://www.npmjs.com/package/mongodb)**: ^6.6.1

