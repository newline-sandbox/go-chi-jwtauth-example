# Go and `chi` JWT Authentication

This project demonstrates a JWT authentication flow with Go, [`chi`](https://github.com/go-chi/chi) and [`jwtauth`](https://github.com/go-chi/jwtauth).

## Get Started

1. Replace `<jwt-secret>` in `main.go` with a secret key that is private to you.

   Example:

   ```go
   const Secret = "42a00d84-9914-4a77-b6bd-d2a9d09c6795"
   ```

2. Install the dependencies:

   ```shell
   $ make install_deps
   ```

3. Run the service:

   ```shell
   $ make run_service
   ```

Feel free to clone this project and build upon it!